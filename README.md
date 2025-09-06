<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Formulário</title>
    
    <style>
        /* Importa uma fonte mais moderna do Google Fonts */
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');

        /* Estilos para o corpo da página */
        body.supernova {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(120deg, #f0f4f8, #d9e2ec); /* Gradiente suave */
        }
        
        /* Container principal do formulário */
        .form-all {
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1); /* Sombra suave para efeito de profundidade */
            border-radius: 12px; /* Bordas arredondadas */
            border: 1px solid #dfe6f0;
            padding: 2.5rem; /* Mais espaço interno */
        }

        /* Estilo para os cabeçalhos (Ex: ENVOLVIDO 1) */
        .form-header-group {
            border-bottom: 2px solid #007bff; /* Linha azul para separar seções */
            padding-bottom: 10px;
            margin-bottom: 25px;
        }

        .form-header-group .form-header {
            font-weight: 700;
            color: #333;
        }

        /* Estilo para os campos de texto e caixas de texto */
        .form-textbox, .form-textarea {
            border-radius: 8px !important;
            border: 1px solid #ccc;
            padding: 12px;
            transition: border-color 0.3s, box-shadow 0.3s; /* Transição suave */
        }

        /* Efeito de foco nos campos (quando o usuário clica) */
        .form-textbox:focus, .form-textarea:focus {
            border-color: #007bff;
            box-shadow: 0 0 8px rgba(0, 123, 255, 0.25);
            outline: none; /* Remove a borda padrão do navegador */
        }

        /* Estilos para os botões */
        .form-buttons-wrapper .form-submit-button {
            border-radius: 8px !important;
            border: none;
            padding: 12px 25px;
            font-size: 16px;
            font-weight: 500;
            cursor: pointer;
            transition: background-color 0.3s, transform 0.2s;
        }

        .form-buttons-wrapper .form-submit-button:hover {
            transform: translateY(-2px); /* Efeito de levantar ao passar o mouse */
        }

        /* Botão Enviar (principal) */
        #input_59 {
            background-color: #007bff !important;
            color: white !important;
        }
        #input_59:hover {
            background-color: #0056b3 !important;
        }

        /* Botão Baixar PDF */
        #input_preview_59 {
            background-color: #28a745 !important;
            color: white !important;
        }
        #input_preview_59:hover {
            background-color: #218838 !important;
        }

        /* Botão Limpar */
        #input_reset_59 {
            background-color: #f0f0f0 !important;
            color: #555 !important;
        }
        #input_reset_59:hover {
            background-color: #ddd !important;
        }

    </style>
    <link type="text/css" rel="stylesheet" href="https://cdn.jotfor.ms/stylebuilder/static/form-common.css?v=4794b7e"/>
    <style type="text/css">@media print{*{-webkit-print-color-adjust: exact !important;color-adjust: exact !important;}.form-section{display:inline!important}.form-pagebreak{display:none!important}.form-section-closed{height:auto!important}.page-section{position:initial!important}}</style>
    <link type="text/css" rel="stylesheet" href="https://cdn.jotfor.ms/themes/CSS/defaultV2.css?v=4794b7e"/>
    <link type="text/css" rel="stylesheet" href="https://cdn.jotfor.ms/themes/CSS/548b1325700cc48d318b4567.css?v=3.3.65295&themeRevisionID=64ff099762313412041c01ae"/>
    <link type="text/css" rel="stylesheet" href="https://cdn.jotfor.ms/css/styles/payment/payment_styles.css?3.3.65295" />
    <link type="text/css" rel="stylesheet" href="https://cdn.jotfor.ms/css/styles/payment/payment_feature.css?3.3.65295" />
    <style type="text/css" id="form-designer-style">
        /* O CSS original do Jotform ainda está aqui, mas o nosso bloco acima irá sobrescrever e adicionar novos estilos. */
        .form-all { font-family: Times New Roman, sans-serif; }
        .form-label.form-label-auto { display: block; float: none; text-align: left; width: 100%; }
        .form-line { margin-top: 12px; margin-bottom: 12px; }
        .form-all { max-width: 752px; width: 100%; }
        .form-label.form-label-left, .form-label.form-label-right, .form-label.form-label-left.form-label-auto, .form-label.form-label-right.form-label-auto { width: 230px; }
        .form-all { font-size: 16px }
        .supernova .form-all, .form-all { background-color: #fff; }
        .form-all { color: #010810; }
        .form-header-group .form-header { color: #010810; }
        .form-header-group .form-subHeader { color: #010810; }
        .form-label-top, .form-label-left, .form-label-right, .form-html, .form-checkbox-item label, .form-radio-item label, span.FITB .qb-checkbox-label, span.FITB .qb-radiobox-label, span.FITB .form-radio label, span.FITB .form-checkbox label, [data-blotid][data-type=checkbox] [data-labelid], [data-blotid][data-type=radiobox] [data-labelid], span.FITB-inptCont[data-type=checkbox] label, span.FITB-inptCont[data-type=radiobox] label { color: #010810; }
        .form-sub-label { color: #1b222a; }
        .supernova { background-color: #483D8B; }
        .supernova body { background: transparent; }
        .form-textbox, .form-textarea, .form-dropdown, .form-radio-other-input, .form-checkbox-other-input, .form-captcha input, .form-spinner input { background-color: #fff; }
        .supernova { background-repeat: no-repeat; background-size:cover; background-attachment: fixed; background-position: center top; }
        .supernova, #stage { background-image: url("https://shots.jotform.com/elton/pattern/pattern-eo2z.png"); }
        .form-all { background-image: none; }
        .form-label.form-label-auto { display: block; float: none; text-align: left; width: 100%; }
    </style>
</head>
<body class="supernova">
    <script>window.enableEventObserver=true</script>
    <script src="https://cdn.jotfor.ms/s/static/9bf0bf2ddf8/static/prototype.forms.js" type="text/javascript"></script>
    <script src="https://cdn.jotfor.ms/s/static/9bf0bf2ddf8/static/jotform.forms.js" type="text/javascript"></script>
    <script src="https://cdn.jotfor.ms/s/static/9bf0bf2ddf8/js/vendor/maskedinput_5.0.9.min.js" type="text/javascript"></script>
    <script src="https://cdn.jotfor.ms/s/static/9bf0bf2ddf8/js/jotStorage.js" type="text/javascript"></script>
    <script src="https://cdn.jotfor.ms/s/static/9bf0bf2ddf8/js/vendor/autoFill.min.js" type="text/javascript"></script>
    <script src="https://cdn.jotfor.ms/s/umd/07122680960/for-pdfimporter-patch.js" type="text/javascript"></script>
    <script src="https://cdn.jotfor.ms/s/umd/07122680960/for-form-branding-footer.js" type="text/javascript" defer></script>
    <script src="https://cdn.jotfor.ms/s/static/9bf0bf2ddf8/js/vendor/smoothscroll.min.js" type="text/javascript"></script>
    <script src="https://cdn.jotfor.ms/s/static/9bf0bf2ddf8/js/errorNavigation.js" type="text/javascript"></script>
    <script type="text/javascript"> JotForm.newDefaultTheme = false; JotForm.extendsNewTheme = true; JotForm.CDN_VENDOR_PATH = "https://cdn.jotfor.ms/s/vendor/static"; JotForm.singleProduct = false; JotForm.newPaymentUIForNewCreatedForms = true; JotForm.texts = {"confirmEmail":"E-mail does not match","pleaseWait":"Please wait...","validateEmail":"You need to validate this e-mail","confirmClearForm":"Are you sure you want to clear the form","lessThan":"Your score should be less than or equal to","incompleteFields":"There are incomplete required fields. Please complete them.","required":"This field is required.","requireOne":"At least one field required.","requireEveryRow":"Every row is required.","requireEveryCell":"Every cell is required.","email":"Enter a valid e-mail address","alphabetic":"This field can only contain letters","numeric":"This field can only contain numeric values","alphanumeric":"This field can only contain letters and numbers.","cyrillic":"This field can only contain cyrillic characters","url":"This field can only contain a valid URL","currency":"This field can only contain currency values.","fillMask":"Field value must fill mask.","uploadExtensions":"You can only upload following files:","noUploadExtensions":"File has no extension file type (e.g. .txt, .png, .jpeg)","uploadFilesize":"File size cannot be bigger than:","uploadFilesizemin":"File size cannot be smaller than:","gradingScoreError":"Score total should only be less than or equal to","inputCarretErrorA":"Input should not be less than the minimum value:","inputCarretErrorB":"Input should not be greater than the maximum value:","maxDigitsError":"The maximum digits allowed is","minCharactersError":"The number of characters should not be less than the minimum value:","maxCharactersError":"The number of characters should not be more than the maximum value:","freeEmailError":"Free email accounts are not allowed","minSelectionsError":"The minimum required number of selections is ","maxSelectionsError":"The maximum number of selections allowed is ","pastDatesDisallowed":"Date must not be in the past.","dateLimited":"This date is unavailable.","dateInvalid":"This date is not valid. The date format is {format}","dateInvalidSeparate":"This date is not valid. Enter a valid {element}.","ageVerificationError":"You must be older than {minAge} years old to submit this form.","multipleFileUploads_typeError":"{file} has invalid extension. Only {extensions} are allowed.","multipleFileUploads_sizeError":"{file} is too large, maximum file size is {sizeLimit}.","multipleFileUploads_minSizeError":"{file} is too small, minimum file size is {minSizeLimit}.","multipleFileUploads_emptyError":"{file} is empty, please select files again without it.","multipleFileUploads_uploadFailed":"File upload failed, please remove it and upload the file again.","multipleFileUploads_onLeave":"The files are being uploaded, if you leave now the upload will be cancelled.","multipleFileUploads_fileLimitError":"Only {fileLimit} file uploads allowed.","dragAndDropFilesHere_infoMessage":"Drag and drop files here","chooseAFile_infoMessage":"Choose a file","maxFileSize_infoMessage":"Max. file size","generalError":"There are errors on the form. Please fix them before continuing.","generalPageError":"There are errors on this page. Please fix them before continuing.","wordLimitError":"Too many words. The limit is","wordMinLimitError":"Too few words.  The minimum is","characterLimitError":"Too many Characters.  The limit is","characterMinLimitError":"Too few characters. The minimum is","ccInvalidNumber":"Credit Card Number is invalid.","ccInvalidCVC":"CVC number is invalid.","ccInvalidExpireDate":"Expire date is invalid.","ccInvalidExpireMonth":"Expiration month is invalid.","ccInvalidExpireYear":"Expiration year is invalid.","ccMissingDetails":"Please fill up the credit card details.","ccMissingProduct":"Please select at least one product.","ccMissingDonation":"Please enter numeric values for donation amount.","disallowDecimals":"Please enter a whole number.","restrictedDomain":"This domain is not allowed","ccDonationMinLimitError":"Minimum amount is {minAmount} {currency}","requiredLegend":"All fields marked with * are required and must be filled.","geoPermissionTitle":"Permission Denied","geoPermissionDesc":"Check your browser's privacy settings.","geoNotAvailableTitle":"Position Unavailable","geoNotAvailableDesc":"Location provider not available. Please enter the address manually.","geoTimeoutTitle":"Timeout","geoTimeoutDesc":"Please check your internet connection and try again.","selectedTime":"Selected Time","formerSelectedTime":"Former Time","cancelAppointment":"Cancel Appointment","cancelSelection":"Cancel Selection","confirmSelection":"Confirm Selection","noSlotsAvailable":"No slots available","slotUnavailable":"{time} on {date} has been selected is unavailable. Please select another slot.","multipleError":"There are {count} errors on this page. Please correct them before moving on.","oneError":"There is {count} error on this page. Please correct it before moving on.","doneMessage":"Well done! All errors are fixed.","invalidTime":"Enter a valid time","doneButton":"Done","reviewSubmitText":"Review and Submit","nextButtonText":"Next","prevButtonText":"Previous","seeErrorsButton":"See Errors","notEnoughStock":"Not enough stock for the current selection","notEnoughStock_remainedItems":"Not enough stock for the current selection ({count} items left)","soldOut":"Sold Out","justSoldOut":"Just Sold Out","selectionSoldOut":"Selection Sold Out","subProductItemsLeft":"({count} items left)","startButtonText":"START","submitButtonText":"Submit","submissionLimit":"Sorry! Only one entry is allowed. <br> Multiple submissions are disabled for this form.","reviewBackText":"Back to Form","seeAllText":"See All","progressMiddleText":"of","fieldError":"field has an error.","error":"Error"}; JotForm.newPaymentUI = true; JotForm.importedPDF = "aHR0cHMlM0ElMkYlMkZ3d3cuam90Zm9ybS5jb20lMkZ1cGxvYWRzJTJGU0FMRVNDTEVEU09OJTJGZm9ybV9maWxlcyUyRnBmY19mbF82OGJhZjEyNzA4ZGE5X0JPLUVNLUJSQU5DTy5wZGYlM0ZuYyUzRDE="; JotForm.importedPDFSettings = {"isConnected":"Yes","enableThumbnail":"No","hasPreviewButton":"Yes","startButtonText":"Start Filling","formType":"legacyForm","welcomeThumbnail":""}; JotForm.originalLanguage = "pt-BR"; JotForm.isFormViewTrackingAllowed = true; JotForm.replaceTagTest = true; JotForm.activeRedirect = "thanktext"; JotForm.uploadServerURL = "https://upload.jotform.com/upload"; JotForm.clearFieldOnHide="disable"; JotForm.submitError="jumpToFirstError"; window.addEventListener('DOMContentLoaded',function(){window.brandingFooter.init({"formID":252474593439064,"campaign":"powered_by_jotform_le","isCardForm":false,"isLegacyForm":true,"formLanguage":"pt-BR"})}); JotForm.isFullSource = true; try{ function isTrackingProhibited() { try { var isEUDomain = /(?:eu.jotform)|(?:jotformeu.com)/.test(window.location.host); var isHipaaDomain = /(?:hipaa.jotform)/.test(window.location.host); var isProhibitedParameterExists = /(?:wfTaskID|PCI_preSubmitRequest|wfTaskType)/.test(window.location.search); var isEditMode = JotForm.isEditMode(); var isTrackingProhibited = isEUDomain || isHipaaDomain || isProhibitedParameterExists || isEditMode; return isTrackingProhibited; } catch (e) { console.log(e); return true; } } if (!isTrackingProhibited()) { var sesApiUrl = /jotform.(pro|dev)/.test(window.location.host) ? '/API' : 'https://api.jotform.com'; function sendOpenId(uuid, eventType) { navigator.sendBeacon(sesApiUrl + '/form/' + 252474593439064 + '/event/' + uuid + '/' + eventType, {}); } var formOpenId = ''; if (window.crypto) { formOpenId = window.crypto.getRandomValues(new BigUint64Array(1)).toString(); } else { formOpenId = (Math.random() * 16).toString(16).slice(2); } sendOpenId = sendOpenId.bind(this, formOpenId); function sendOpenIdOnSubmit() { var currentForm = $('252474593439064'); currentForm.addEventListener('submit', function() { sendOpenId('clientSubmitClick_V5'); }); var openIdInput = currentForm.querySelector('[name="formOpenId_V5"]'); if (!openIdInput) { openIdInput = document.createElement('input'); openIdInput.setAttribute('type', 'hidden'); openIdInput.setAttribute('name', 'formOpenId_V5'); currentForm.appendChild(openIdInput); } openIdInput.value = formOpenId; } sendOpenId('clientFormView_V5'); if (document.readyState == 'complete' || (this.jsForm && (document.readyState === undefined || document.readyState === 'interactive'))) { sendOpenIdOnSubmit(); } else { document.ready(sendOpenIdOnSubmit); } } } catch(openIdBlockError) { console.log(openIdBlockError); } 
    JotForm.init(function(){
    if (window.JotForm && JotForm.accessible) $('input_3').setAttribute('tabindex',0);
    JotForm.calendarMonths = ["January","February","March","April","May","June","July","August","September","October","November","December"];
    if (!JotForm.calenderViewMonths) JotForm.calenderViewMonths = {}; JotForm.calenderViewMonths[67] = ["January","February","March","April","May","June","July","August","September","October","November","December"];
    if (!JotForm.calenderViewDays) JotForm.calenderViewDays = {}; JotForm.calenderViewDays[67] = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"];
    JotForm.calendarDays = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"];
    JotForm.calendarOther = {"today":"Today"};
    var languageOptions = document.querySelectorAll('#langList li'); 
    for(var langIndex = 0; langIndex < languageOptions.length; langIndex++) { 
        languageOptions[langIndex].on('click', function(e) { setTimeout(function(){ JotForm.setCalendar("67", false, {"days":{"monday":true,"tuesday":true,"wednesday":true,"thursday":true,"friday":true,"saturday":true,"sunday":true},"future":true,"past":true,"custom":false,"ranges":false,"start":"","end":"","countSelectedDaysOnly":false}); }, 0); });
    } 
    JotForm.onTranslationsFetch(function() { JotForm.setCalendar("67", false, {"days":{"monday":true,"tuesday":true,"wednesday":true,"thursday":true,"friday":true,"saturday":true,"sunday":true},"future":true,"past":true,"custom":false,"ranges":false,"start":"","end":"","countSelectedDaysOnly":false}); });
    if (window.JotForm && JotForm.accessible) $('input_5').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_8').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_9').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_11').setAttribute('tabindex',0);
    JotForm.calendarMonths = ["January","February","March","April","May","June","July","August","September","October","November","December"];
    if (!JotForm.calenderViewMonths) JotForm.calenderViewMonths = {}; JotForm.calenderViewMonths[71] = ["January","February","March","April","May","June","July","August","September","October","November","December"];
    if (!JotForm.calenderViewDays) JotForm.calenderViewDays = {}; JotForm.calenderViewDays[71] = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"];
    JotForm.calendarDays = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"];
    JotForm.calendarOther = {"today":"Today"};
    var languageOptions = document.querySelectorAll('#langList li'); 
    for(var langIndex = 0; langIndex < languageOptions.length; langIndex++) { 
        languageOptions[langIndex].on('click', function(e) { setTimeout(function(){ JotForm.setCalendar("71", false, {"days":{"monday":true,"tuesday":true,"wednesday":true,"thursday":true,"friday":true,"saturday":true,"sunday":true},"future":true,"past":true,"custom":false,"ranges":false,"start":"","end":"","countSelectedDaysOnly":false}); }, 0); });
    } 
    JotForm.onTranslationsFetch(function() { JotForm.setCalendar("71", false, {"days":{"monday":true,"tuesday":true,"wednesday":true,"thursday":true,"friday":true,"saturday":true,"sunday":true},"future":true,"past":true,"custom":false,"ranges":false,"start":"","end":"","countSelectedDaysOnly":false}); });
    if (window.JotForm && JotForm.accessible) $('input_13').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_14').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_15').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_16').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_17').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_18').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_20').setAttribute('tabindex',0);
    JotForm.calendarMonths = ["January","February","March","April","May","June","July","August","September","October","November","December"];
    if (!JotForm.calenderViewMonths) JotForm.calenderViewMonths = {}; JotForm.calenderViewMonths[73] = ["January","February","March","April","May","June","July","August","September","October","November","December"];
    if (!JotForm.calenderViewDays) JotForm.calenderViewDays = {}; JotForm.calenderViewDays[73] = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"];
    JotForm.calendarDays = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"];
    JotForm.calendarOther = {"today":"Today"};
    var languageOptions = document.querySelectorAll('#langList li'); 
    for(var langIndex = 0; langIndex < languageOptions.length; langIndex++) { 
        languageOptions[langIndex].on('click', function(e) { setTimeout(function(){ JotForm.setCalendar("73", false, {"days":{"monday":true,"tuesday":true,"wednesday":true,"thursday":true,"friday":true,"saturday":true,"sunday":true},"future":true,"past":true,"custom":false,"ranges":false,"start":"","end":"","countSelectedDaysOnly":false}); }, 0); });
    } 
    JotForm.onTranslationsFetch(function() { JotForm.setCalendar("73", false, {"days":{"monday":true,"tuesday":true,"wednesday":true,"thursday":true,"friday":true,"saturday":true,"sunday":true},"future":true,"past":true,"custom":false,"ranges":false,"start":"","end":"","countSelectedDaysOnly":false}); });
    if (window.JotForm && JotForm.accessible) $('input_22').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_23').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_24').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_25').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_26').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_27').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_29').setAttribute('tabindex',0);
    JotForm.calendarMonths = ["January","February","March","April","May","June","July","August","September","October","November","December"];
    if (!JotForm.calenderViewMonths) JotForm.calenderViewMonths = {}; JotForm.calenderViewMonths[74] = ["January","February","March","April","May","June","July","August","September","October","November","December"];
    if (!JotForm.calenderViewDays) JotForm.calenderViewDays = {}; JotForm.calenderViewDays[74] = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"];
    JotForm.calendarDays = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"];
    JotForm.calendarOther = {"today":"Today"};
    var languageOptions = document.querySelectorAll('#langList li'); 
    for(var langIndex = 0; langIndex < languageOptions.length; langIndex++) { 
        languageOptions[langIndex].on('click', function(e) { setTimeout(function(){ JotForm.setCalendar("74", false, {"days":{"monday":true,"tuesday":true,"wednesday":true,"thursday":true,"friday":true,"saturday":true,"sunday":true},"future":true,"past":true,"custom":false,"ranges":false,"start":"","end":"","countSelectedDaysOnly":false}); }, 0); });
    } 
    JotForm.onTranslationsFetch(function() { JotForm.setCalendar("74", false, {"days":{"monday":true,"tuesday":true,"wednesday":true,"thursday":true,"friday":true,"saturday":true,"sunday":true},"future":true,"past":true,"custom":false,"ranges":false,"start":"","end":"","countSelectedDaysOnly":false}); });
    if (window.JotForm && JotForm.accessible) $('input_31').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_32').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_33').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_34').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_35').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_36').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_38').setAttribute('tabindex',0);
    JotForm.calendarMonths = ["January","February","March","April","May","June","July","August","September","October","November","December"];
    if (!JotForm.calenderViewMonths) JotForm.calenderViewMonths = {}; JotForm.calenderViewMonths[75] = ["January","February","March","April","May","June","July","August","September","October","November","December"];
    if (!JotForm.calenderViewDays) JotForm.calenderViewDays = {}; JotForm.calenderViewDays[75] = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"];
    JotForm.calendarDays = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"];
    JotForm.calendarOther = {"today":"Today"};
    var languageOptions = document.querySelectorAll('#langList li'); 
    for(var langIndex = 0; langIndex < languageOptions.length; langIndex++) { 
        languageOptions[langIndex].on('click', function(e) { setTimeout(function(){ JotForm.setCalendar("75", false, {"days":{"monday":true,"tuesday":true,"wednesday":true,"thursday":true,"friday":true,"saturday":true,"sunday":true},"future":true,"past":true,"custom":false,"ranges":false,"start":"","end":"","countSelectedDaysOnly":false}); }, 0); });
    } 
    JotForm.onTranslationsFetch(function() { JotForm.setCalendar("75", false, {"days":{"monday":true,"tuesday":true,"wednesday":true,"thursday":true,"friday":true,"saturday":true,"sunday":true},"future":true,"past":true,"custom":false,"ranges":false,"start":"","end":"","countSelectedDaysOnly":false}); });
    if (window.JotForm && JotForm.accessible) $('input_40').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_41').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_42').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_43').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_44').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_45').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_46').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_47').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_50').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_51').setAttribute('tabindex',0);
    if (window.JotForm && JotForm.accessible) $('input_58').setAttribute('tabindex',0);
        JotForm.alterTexts({"ageVerificationError":"Você deve ter mais de {minAge} anos para enviar este formulário.","alphabetic":"Este campo pode conter apenas letras.","alphanumeric":"Este campo pode conter apenas letras e números.","cancelAppointment":"Cancelar Agendamento","cancelSelection":"Cancelar Seleção","ccDonationMinLimitError":"O valor mínimo é de {minAmount} {currency}","ccInvalidCVC":"Código de verificação (CVC) inválido.","ccInvalidExpireDate":"Data de vencimento inválida.","ccInvalidExpireMonth":"Expiration month is invalid.","ccInvalidExpireYear":"Expiration year is invalid.","ccInvalidNumber":"Número do cartão de crédito inválido.","ccMissingDetails":"Please fill up the credit card details.","ccMissingDonation":"Insira valores numéricos para o montante de doação.","ccMissingProduct":"Selecione pelo menos um produto.","characterLimitError":"Excesso de caracteres. O limite é de","characterMinLimitError":"Poucos caracteres. O mínimo é","chooseAFile_infoMessage":"Escolha um arquivo","confirmClearForm":"Tem certeza de que deseja limpar este formulário?","confirmEmail":"E-mail não é correspondente.","confirmSelection":"Confirm Selection","currency":"Este campo pode conter apenas valores monetários.","cyrillic":"Este campo pode conter apenas caracteres cirílicos.","dateInvalid":"Esta data não é válida. O formato da data é {format}.","dateInvalidSeparate":"Esta data não é válida. Insira um {element} válido.","dateLimited":"Esta data não está disponível.","disallowDecimals":"Favor inserir um número inteiro.","doneButton":"Finalizado","doneMessage":"Muito bem! Todos os erros foram corrigidos.","dragAndDropFilesHere_infoMessage":"Arraste e solte seus arquivos aqui","email":"Insira um endereço de e-mail válido.","error":"Erro","fieldError":"campo possui um erro.","fillMask":"Valor do campo deve preencher máscara.","formerSelectedTime":"Horário Anterior","freeEmailError":"Não são permitidas contas de e-mail gratuitas.","generalError":"O formulário contém erros. Por favor, corrija-os antes de continuar.","generalPageError":"Há erros nesta página. Por favor, corrija-os antes de continuar.","geoNotAvailableDesc":"Location provider not available. Please enter the address manually.","geoNotAvailableTitle":"Position Unavailable","geoPermissionDesc":"Check your browser's privacy settings.","geoPermissionTitle":"Permission Denied","geoTimeoutDesc":"Please check your internet connection and try again.","geoTimeoutTitle":"Timeout","gradingScoreError":"Pontuação total deve ser menor ou igual a","incompleteFields":"Há campos obrigatórios incompletos. Por favor, preencha-os.","inputCarretErrorA":"A entrada não deve ser menor que o valor mínimo:","inputCarretErrorB":"A entrada não deve ser maior que o valor máximo:","invalidTime":"Insira um horário válido","justSoldOut":"Acabou de Esgotar","lessThan":"Sua pontuação deve ser inferior ou igual a","maxCharactersError":"The number of characters should not be more than the maximum value:","maxDigitsError":"O número máximo de caracteres permitido é de","maxFileSize_infoMessage":"Tamanho máx.","maxSelectionsError":"O número máximo de seleções permitido é","minCharactersError":"O número de caracteres não deve ser menor que o valor mínimo:","minSelectionsError":"O número mínimo de seleções exigido é","multipleError":"Existem {count} erros nesta página. Corrija-os antes de prosseguir.","multipleFileUploads_emptyError":"{file} está vazio. Por favor, selecione os arquivos novamente.","multipleFileUploads_fileLimitError":"São permitidos apenas {fileLimit} uploads.","multipleFileUploads_minSizeError":"O arquivo {file} é muito pequeno. O tamanho mínimo é de {minSizeLimit}.","multipleFileUploads_onLeave":"O upload de arquivos está em andamento. Se você sair agora, o envio será cancelado.","multipleFileUploads_sizeError":"O arquivo {file} é muito grande. O tamanho máximo é de {sizeLimit}.","multipleFileUploads_typeError":"O arquivo {file} possui uma extensão inválida. São permitidas apenas as extensões {extensions}.","multipleFileUploads_uploadFailed":"Falha no upload do arquivo. Remova-o e envie-o novamente.","nextButtonText":"Próximo","noSlotsAvailable":"Nenhum horário disponível","notEnoughStock":"Não há estoque suficiente para a seleção atual","notEnoughStock_remainedItems":"Não há estoque suficiente para a seleção atual ({count} itens restantes)","noUploadExtensions":"File has no extension file type (e.g. .txt, .png, .jpeg)","numeric":"Este campo pode conter apenas números.","oneError":"Existe {count} erro nesta página. Corrija-o antes de prosseguir.","pastDatesDisallowed":"A data não pode estar no passado.","pleaseWait":"Por favor, aguarde...","prevButtonText":"Anterior","progressMiddleText":"de","required":"Este campo é obrigatório.","requiredLegend":"Todos os campos marcados com * são obrigatórios e devem ser preenchidos.","requireEveryCell":"Toda célula é obrigatória.","requireEveryRow":"Todos as linhas são obrigatórias.","requireOne":"Pelo menos um campo é obrigatório.","restrictedDomain":"This domain is not allowed","reviewBackText":"Voltar ao Formulário","reviewSubmitText":"Revisar e Enviar","seeAllText":"Ver Todos","seeErrorsButton":"Ver Erros","selectedTime":"Horário Selecionado","selectionSoldOut":"Seleção Esgotada","slotUnavailable":"{time} em {date} já foi selecionado e está indisponível. Selecione outro horário.","soldOut":"Esgotado","startButtonText":"COMEÇAR","submissionLimit":"Desculpe! Apenas uma entrada é permitida. &lt;br&gt; A opção de múltiplos envios está desativada para este formulário.","submitButtonText":"Enviar","subProductItemsLeft":"({count} itens restantes)","uploadExtensions":"Somente é possível fazer upload dos seguintes arquivos:","uploadFilesize":"O tamanho do arquivo não pode ser maior que:","uploadFilesizemin":"O ficheiro não pode ser menor que:","url":"Este campo pode conter apenas uma URL válida.","validateEmail":"Você precisa validar este e-mail","wordLimitError":"Excesso de palavras. O limite é de","wordMinLimitError":"Poucas palavras. O mínimo é"});
        setTimeout(function() {
            JotForm.autoFillInitialize({"bindChange":"on","menu":"enable","timeout":"4","ttl":"86400"});
        }, 10);
    });
    setTimeout(function() {
        JotForm.paymentExtrasOnTheFly([null,{"name":"10Bpmpmma","qid":"1","text":"10º BPM/PMMA","type":"control_head"},{"name":"boletimDe","qid":"2","text":"FORMULARIO DE BOLETIM DE OCORRENCIA","type":"control_head"},{"description":"","name":"boN","qid":"3","subLabel":"","text":"BO N°","type":"control_textbox"},null,{"description":"","name":"localDa","qid":"5","subLabel":"","text":"LOCAL DA OCORRENCIA","type":"control_textbox"},null,null,{"description":"","name":"bairro","qid":"8","subLabel":"","text":"BAIRRO","type":"control_textbox"},{"description":"","name":"pontoDe","qid":"9","subLabel":"","text":"PONTO DE REF","type":"control_textbox"},{"name":"envolvido1","qid":"10","text":"ENVOLVIDO 1:","type":"control_head"},{"description":"","name":"nome","qid":"11","subLabel":"","text":"NOME","type":"control_textbox"},null,{"description":"","name":"residencia","qid":"13","subLabel":"","text":"RESIDENCIA","type":"control_textbox"},{"description":"","name":"cidade","qid":"14","subLabel":"","text":"CIDADE","type":"control_textbox"},{"description":"","name":"bairro15","qid":"15","subLabel":"","text":"BAIRRO","type":"control_textbox"},{"description":"","name":"nDa","qid":"16","subLabel":"","text":"N° DA CASA","type":"control_textbox"},{"description":"","name":"nDo","qid":"17","subLabel":"","text":"Nº DO DOCUMENTO","type":"control_textbox"},{"description":"","name":"profissao","qid":"18","subLabel":"","text":"PROFISSAO","type":"control_textbox"},{"name":"envolvidos19","qid":"19","text":"ENVOLVIDO 2:","type":"control_head"},{"description":"","name":"nome20","qid":"20","subLabel":"","text":"NOME","type":"control_textbox"},null,{"description":"","name":"residencia22","qid":"22","subLabel":"","text":"RESIDENCIA","type":"control_textbox"},{"description":"","name":"cidade23","qid":"23","subLabel":"","text":"CIDADE","type":"control_textbox"},{"description":"","name":"bairro24","qid":"24","subLabel":"","text":"BAIRRO","type":"control_textbox"},{"description":"","name":"n25","qid":"25","subLabel":"","text":"N° DA CASA","type":"control_textbox"},{"description":"","name":"n26","qid":"26","subLabel":"","text":"N° DO DOCUMENTO","type":"control_textbox"},{"description":"","name":"profissao27","qid":"27","subLabel":"","text":"PROFISSAO","type":"control_textbox"},{"name":"envolvidos28","qid":"28","text":"ENVOLVIDOS 3:","type":"control_head"},{"description":"","name":"nome29","qid":"29","subLabel":"","text":"NOME","type":"control_textbox"},null,{"description":"","name":"residencia31","qid":"31","subLabel":"","text":"RESIDENCIA","type":"control_textbox"},{"description":"","name":"cidade32","qid":"32","subLabel":"","text":"CIDADE","type":"control_textbox"},{"description":"","name":"bairro33","qid":"33","subLabel":"","text":"BAIRRO","type":"control_textbox"},{"description":"","name":"n34","qid":"34","subLabel":"","text":"N° DA CASA","type":"control_textbox"},{"description":"","name":"n35","qid":"35","subLabel":"","text":"N° DO DOCUMENTO","type":"control_textbox"},{"description":"","name":"profissao36","qid":"36","subLabel":"","text":"PROFISSAO","type":"control_textbox"},{"name":"envolvidos37","qid":"37","text":"ENVOLVIDO 4:","type":"control_head"},{"description":"","name":"nome38","qid":"38","subLabel":"","text":"NOME","type":"control_textbox"},null,{"description":"","name":"residencia40","qid":"40","subLabel":"","text":"RESIDENCIA","type":"control_textbox"},{"description":"","name":"cidade41","qid":"41","subLabel":"","text":"CIDADE","type":"control_textbox"},{"description":"","name":"bairro42","qid":"
