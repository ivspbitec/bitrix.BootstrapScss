# bitrix_setup
bitrix_setup
## Установка BOOTSTRAP с SASS

SASS - bootstrap custom

1. Создать папки
Папка /local/templates/site/scss/
Папка /local/templates/site/css/

2. Скопировать из Bootstrap _variables.scss - /local/templates/site/scss/
3. Создать custom.scss 

// Required
@import "../../../assets/vendor/twbs/bootstrap/scss/functions";
@import "_bootstrap_variables";
@import "../../../assets/vendor/twbs/bootstrap/scss/variables";
@import "../../../assets/vendor/twbs/bootstrap/scss/mixins";


// Optional   
@import "../../../assets/vendor/twbs/bootstrap/scss/reboot";
@import "../../../assets/vendor/twbs/bootstrap/scss/type";
@import "../../../assets/vendor/twbs/bootstrap/scss/images";
@import "../../../assets/vendor/twbs/bootstrap/scss/code";
@import "../../../assets/vendor/twbs/bootstrap/scss/grid";
@import "../../../assets/vendor/twbs/bootstrap/scss/badge";
@import "../../../assets/vendor/twbs/bootstrap/scss/print";
@import "../../../assets/vendor/twbs/bootstrap/scss/tables";
@import "../../../assets/vendor/twbs/bootstrap/scss/forms";
@import "../../../assets/vendor/twbs/bootstrap/scss/buttons";
@import "../../../assets/vendor/twbs/bootstrap/scss/transitions";
@import "../../../assets/vendor/twbs/bootstrap/scss/dropdown";
@import "../../../assets/vendor/twbs/bootstrap/scss/button-group";
@import "../../../assets/vendor/twbs/bootstrap/scss/alert";
@import "../../../assets/vendor/twbs/bootstrap/scss/input-group";
@import "../../../assets/vendor/twbs/bootstrap/scss/custom-forms";
@import "../../../assets/vendor/twbs/bootstrap/scss/nav";
@import "../../../assets/vendor/twbs/bootstrap/scss/navbar";
 
@import "../../../assets/vendor/twbs/bootstrap/scss/card";
@import "../../../assets/vendor/twbs/bootstrap/scss/breadcrumb";
@import "../../../assets/vendor/twbs/bootstrap/scss/pagination";
@import "../../../assets/vendor/twbs/bootstrap/scss/badge";
@import "../../../assets/vendor/twbs/bootstrap/scss/jumbotron";
 
@import "../../../assets/vendor/twbs/bootstrap/scss/progress";
@import "../../../assets/vendor/twbs/bootstrap/scss/media";
@import "../../../assets/vendor/twbs/bootstrap/scss/list-group";
@import "../../../assets/vendor/twbs/bootstrap/scss/close";
@import "../../../assets/vendor/twbs/bootstrap/scss/modal";
@import "../../../assets/vendor/twbs/bootstrap/scss/tooltip";
@import "../../../assets/vendor/twbs/bootstrap/scss/popover";
@import "../../../assets/vendor/twbs/bootstrap/scss/carousel";
@import "../../../assets/vendor/twbs/bootstrap/scss/utilities";
 
// Local
@import "template_styles";
 
4.Редактировать 
4.1 _bootstrap_variables.scss
4.1 _template_styles.scss

5. Запустить
cd /local/templates/site/css/

sass --watch scss:css --style compressed

На выходе компрессированный css
