MyCordovaShop
=============

Example code for PayPal [Mobile SDK Cordova/Phonegap Plugin](https://github.com/paypal/PayPal-Cordova-Plugin)

* Make sure you have cordova installed if you have node just run `sudo npm install -g cordova` else read [here](http://cordova.apache.org/docs/en/4.0.0/guide_cli_index.md.html)
* For security reasons, by default the environment is NoNetwork.
* If you want to try sandbox and/or live enter your client ids [here](https://github.com/romk1n/MyCordovaShop/blob/master/www/js/index.js#L53) and set environment to _PayPalEnvironmentProduction_ or _PayPalEnvironmentSandbox_ [here](https://github.com/romk1n/MyCordovaShop/blob/master/www/js/index.js#L113)

Usage
-----

```bash
$ git clone https://github.com/romk1n/MyCordovaShop.git
$ cordova plugin add org.apache.cordova.console
$ cordova plugin add com.paypal.cordova.mobilesdk
$ cordova platform add ios
$ cordova platform add android   
# for ios
$ cordova run ios
# for android
$ cordova run android
``` 
