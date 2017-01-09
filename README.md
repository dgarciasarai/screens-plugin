# Nativescript plugin with Liferay Screens
This plugin contains Liferay Screens for Nativescript iOS apps.

Follow this steps to add this plugin to your application:
* Open your terminal and move to your app folder
* Execute: `tns plugin add /path/to/screens-plugin`
* Then, build your iOS app: `tns build ios`
* Finally, run your app: `tns run ios`

You can now use all the screenlets for your iOS app from Nativescript code.

## Example

If you want to display a `LoginScreenlet`, you have to do the following:
```swift
let superview = app.ios.rootController.view;

//Change CGRectMake values to configure the size of your LoginScreenlet
let login = new LoginScreenlet(CGRectMake(10, 30, 355, 700));

superview.addSubview(login);
```
