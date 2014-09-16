angular-htaccess
================

.htaccess required for Angular JS HTML5 Mode, Routing (Pretty URLs)

Additional Notes

1. base href="/" goes inside the HEAD tag before importing external (local) stylesheets and script files. Required for deep linking

2. in the module configuration, set html5mode to TRUE i.e. $locationProvider.html5Mode(true).hashPrefix('!');
