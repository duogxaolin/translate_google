# translate_google
- Các chức năng chính:
 + Dịch toàn bộ trang web với google dịch
 + Loại bỏ hết hiệu ứng, logo của google gây vướng víu

```php
<link href="duogxaolin.css?t=1685691435175" rel="stylesheet" type="text/css" /> //thêm css để loại bỏ logo
<script type="text/javascript"> //script dịch
    function googleTranslate() {
        new google.translate['TranslateElement']({
            pageLanguage: 'vi'
        }, 'button_translate');
    }
</script>
<script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslate"></script> //script của google dịch
 
     <!-- Thêm phần tử cho Google Translate -->
   <div id="button_translate"></div>


