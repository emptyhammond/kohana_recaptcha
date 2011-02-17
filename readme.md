#  Kohana_reCAPTCHA


## License:

[The Unlicense](http://unlicense.org) (aka: public domain)

## Changelog:


### v.0.1 : February 17th, 2011
* Kohana_reCAPTCHA is now in the Public Domain

##### Thanks:

emptyhammond

### v0.1 : February 17th, 2011 - Initial release

## Summary:

Kohana_reCAPCTHA is a module that facilitates the use of the reCAPTCHA library as a Kohana module.

## Instructions:
* A default recaptcha.php config file is included but you MUST change the public and private key values for the plugin to work.
* Create an instance of the Kohana Recaptcha object by calling Recaptcha::instance().
* There are only two methods:
	* get_html(﻿publickey) - pass your public key optionally if you want to use a different one from the config file you initilized the Recaptcha object with.
	* ﻿is_valid($privatekey = NULL) - you can override your config private key value here.
* The recaptchalib.php file bundled with the plugin is v1.11
* N.B. Please familiarise yourself with http://code.google.com/apis/recaptcha/docs/php.html

## Releases 

Watch the [current tickets](http://github.com/emptyhammond/kohana_recaptcha/issues) to view the areas of active development.