_This project has been started because, the developer of "php-mobile-detect" does not fix or support his version_

Description
Mobile Detect 2 is a simple PHP class for easy detection of the most popular mobile devices platforms:
  * Android
  * Blackberry
  * iPhone
  * iPad
  * Opera Mini
  * Palm
  * Windows Mobile
  * as well as generic ones.

Usage
Include and instantiate the class:
```
include("Mobile_Detect.php");
$detect = new Mobile_Detect();
```

Check for a specific platform:

```
if ($detect->isAndroid()) {
    // code to run for the Google Android platform
}
```

Available methods are isAndroid(), isBlackberry(), isOpera(), isPalm(), isWindows(), isGeneric(). Alternatively, if you are only interested in checking to see if the user is using a mobile device, without caring for specific platform:

```
if ($detect->isMobile()) {
    // any mobile platform
}
```

Personal blog: http://sjevsejev.blogspot.com