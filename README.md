<script>
jQuery(document).ready(function(){
    var $ = jQuery;
    var suffix = '###';
    jQuery.ajax({
        url:'https://instant24.pl/api/external/ppi/domain/tVNrReAcyNEfrKV4',
        type:'GET',
        dataType: 'json',
        success: function (response){
            jQuery('.domainAddress').attr('href', response+'/'+suffix);
        }
   });
});
</script>
