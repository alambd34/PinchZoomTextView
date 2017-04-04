PinchZoomTextView Library
=============

This library allows you to have a TextView that will grow/shrink the font size using gestures from the user.

Usage
-----

To have access to the library, add the dependency to your build.gradle:

```java
	compile 'com.androidessence:pinchzoomtextview:1.0.2'
```

If you are interested in using this in a Kotlin project, you can add the following dependency:

```java
	compile 'com.androidessence:pinchzoomtextview-kotlin:1.0.2'
```

Developer Notes
---------------

By default, the zoom feature is always enabled. If for any reason you want to disable it, simply call the `PinchZoomTextView#setZoomEnabled(boolean enabled)` method.

Sample
-----

To see the library in action, here is a sample of the text size changing:

<img src='sample.gif' width='400' height='640' />

Version History
---------------

#### 1.0.2
 - Closed [Issue #2](https://github.com/androidessence/PinchZoomTextView/issues/2) and added a Kotlin module.

#### 1.0.1
 - Closed [Issue #1](https://github.com/androidessence/PinchZoomTextView/issues/1) to kill the glyph cache.

#### 1.0.0
 - Initial release.

Credits & Contact
-----------------

PinchZoomTextView was created by:

- [Adam McNeilly](https://github.com/AdamMc331)

With special thanks to [Eric Cugota](https://github.com/tryadelion) for helping me get this into Bintray and make it available for you.

And it's released under [Android Essence blog](http://androidessence.com/).

License
-------

PinchZoomTextView is available under the [MIT License](https://opensource.org/licenses/MIT). You are free to do with it what you want. If you submit a pull request, please add your name to the credits section. :)
