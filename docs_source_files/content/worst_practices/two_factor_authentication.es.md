---
title: "Two Factor Authentication"
weight: 1
---

{{% notice info %}}
<i class="fas fa-language"></i> Page being translated from 
English to Spanish. Do you speak Spanish? Help us to translate
it by sending us pull requests!
{{% /notice %}}

Two Factor Authentication shortly know as _2FA_ is a authorization 
mechanism where One Time Password(OTP) is generated using "Authenticator" 
mobile apps such as "Google Authenticator", "Microsoft Authenticator" 
etc., or by SMS, e-mail to authenticate. Automating this seamlessly 
and consistently is a big challenge in Selenium. There are some ways 
to automate this process. But that will be another layer on top of our 
Selenium tests and not secured as well.  So, you can avoid automating 2FA.

There are few options to get around 2FA checks:

* Disable 2FA for certain Users in the test environment, so that you can 
use those user credentials in the automation.
* Disable 2FA in your test environment.
* Disable 2FA if you login from certain IPs. That way we can configure our 
test machine IPs to avoid this.

Update two_factor_authentication.es.md

La autenticación de dos factores, conocida en breve como 2FA, es un mecanismo de autorización en el que se genera una contraseña única (OTP) mediante aplicaciones móviles de "Autenticador" como "Google Authenticator", "Microsoft Authenticator", etc., o por SMS, correo electrónico para autenticarse. Automatizar esto de manera transparente y consistente es un gran desafío en Selenium. Hay algunas formas de automatizar este proceso. Pero esa será otra capa además de nuestras pruebas de selenio y tampoco asegurada. Por lo tanto, puede evitar la automatización de 2FA. Hay algunas opciones para sortear los controles 2FA:
