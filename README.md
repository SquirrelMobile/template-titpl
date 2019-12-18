# Empty Template titpl

If you want create a PR to add your own template in generator-titpl here : https://github.com/SquirrelMobile/generator-titpl you can use this default template to do it.

# Required files

The generator-titpl ask some question during the initialization. So, you must add these file into your template :

## app/config.json

In this file, there is 3 variables that must be present :

`<%= MAINCOLOR %>` => main color of your app

`<%= MAINCOLOR2 %>` => second main color of your app

`<%= BASEURL %>` => base url of your API

## tiapp.xml

`<%= ID %>` => APP ID of the application

`<%= APPNAME %>` => App's name of the application

`<%= PUBLISHER %>` => Publisher's name

`<%= URL %>` => URL of your company

`<%= DESCRIPTION %>` => Description of the application

`<%= COPYRIGHT %>` => Copyright

`<%= IDMANIFEST %>` => APP ID of the manifest for Android

`<%= SDK %>` => Titanium SDK version

## package.json

`<%= APPNAME %>` => App's name of the application

`<%= SDK %>` => Titanium SDK version

## \_gitignore and \_prettierrc

These 2 files must be name like this

This is the minimum configuration, you can add the modules you want and the code in app/ folder.
Once your template is done, feel free to add a pull request into the generator-titpl : https://github.com/SquirrelMobile/generator-titpl/pulls
