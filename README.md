AndroidFacebookSDK
==================

The Facebook SDK for Android (3.0.1) adapted to work with 8tracks Android App.

This is mostly the same SDK android publishes, but without all the Test, Samples, etc. folders.
It's also linked with a special compat library: android-support-v4-rev11.jar that lives in its own directory.

I usually check the official Facebook Repo when there's a new "stable version" (i.e.: tagged) and inspect if there are changes outside /res and /src so I can copy those changes to this project. 
Finally just copy all /src /res and replace existing ones. Haven't had any problems so far. 
 
There are **no code changes**. What's buggy is buggy thanks to Facebook ;)