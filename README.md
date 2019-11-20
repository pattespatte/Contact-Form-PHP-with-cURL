
# AjaxContactForm

### [DEMO](https://dev.raspgot.fr/github/contact-form-recaptcha-v3)
SMTP email sending system with ajax and recaptcha v3 for PHP.

![raspgot](https://dev.raspgot.fr/AjaxContactForm-PHPMailer/screen.jpg)

## Description
* SMTP Authentication
* Google reCAPTCHA v3
* Validation and input's security

## Installation
Direct download [HERE](https://github.com/raspgot/AjaxContactForm-PHPMailer-reCAPTCHA-v3/archive/master.zip)
Or use git :
```
git clone https://github.com/raspgot/AjaxContactForm-PHPMailer-reCAPTCHA-v3.git
composer install
```

## Configuration
Captcha key -> [HERE](https://www.google.com/recaptcha/intro/v3.html)
SMTP sender -> [HERE](https://www.ovh.com/fr/emails/email-pro/)

**AjaxForm.php**
```
protected $host     = 'pro1.mail.ovh.net';
protected $username = 'hello@raspgot.fr';
protected $password = '';
private $secret     = '';
```

**AjaxForm.js**
```
const publicKey = '';
```

**index.html**
```
<script src="https://www.google.com/recaptcha/api.js?render=MY_GOOGLE_KEY"></script>
```

#### Optionnal
If you wanna update vendor folder use the update [composer](https://getcomposer.org/) commande
```
composer update
```
## Author
![raspgot](https://dev.raspgot.fr/AjaxContactForm-PHPMailer/raspgot.png)

You can visit my [Portfolio](https://raspgot.fr)

## Dependencies
* [PHPMailer](https://github.com/PHPMailer/PHPMailer)
* [reCAPTCHA PHP client library](https://github.com/google/recaptcha)
* [Bootstrap](https://getbootstrap.com/)
* [Jquery](https://jquery.com/)
