ModBot
======

Introduction
------------

Automated moderation for VBulletin based forums using the
[VBulletin Mobile API][api]. This application makes use of the Mobile API
included in VBulletin forums running version 4.1 and later. The Mobile API must
be enabled by the administrator and an API key must be generated.

The full list of available methods that the Mobile API may utilise can be found
[here][methodlist].

The application has been developed using the [Model–view–controller][mvc]
pattern.

Building
--------

[Gradle][gradle] is used as the build system. Java 8 ([Oracle Java][oracle]) or
[OpenJDK][openjdk] on Linux is required.

Run `gradle` to build the application.

Running
-------

The application takes two program arguments:

* `url` The website URL the forum is installed on.
* `apikey` The API key generated by the forum administrator via ACP.

Dependencies
------------

The following Java libraries are used by the application:

* [Google Gson][gson]
* [Google Guava][guava]
* [SLF4J][slf4j]
* [Twinkle][twinkle]

Credits
-------

### Contributors

* [Michael Bull][mikebull94]
* [Cube][cube]

### Miscellaneous Credits

* [Heinrich Spreiter][spreiter301] - author of the Twinkle library used for
displaying notifications.
* [Hai Trieu][haitrieu] - sample code for the VBulletin Mobile API.
* All of the contributors behind [Google Gson][gsoncontributors] &
[Google Guava][guavacontributors].

Screenshots
------------

<p align="center">
  <img src="https://raw.githubusercontent.com/MikeBull94/modbot/master/img/screenshot1.png">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/MikeBull94/modbot/master/img/screenshot2.png">
</p>

[api]: http://www.vbulletin.com/vbcms/content.php/334-mobile-api
[methodlist]: http://www.vbulletin.com/vbcms/content.php/352-Method-List
[mvc]: http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller
[gradle]: http://www.gradle.org/
[oracle]: http://www.oracle.com/technetwork/java/javase/downloads/index.html
[openjdk]: http://openjdk.java.net/
[gson]: https://code.google.com/p/google-gson/
[guava]: https://code.google.com/p/guava-libraries/
[slf4j]: http://www.slf4j.org/
[twinkle]: http://www.swingfx.ch/
[mikebull94]: https://github.com/MikeBull94
[cube]: https://github.com/cubeee
[spreiter301]: https://github.com/spreiter301
[haitrieu]: http://ios4vn.com/?p=55
[gsoncontributors]: https://code.google.com/p/google-gson/people/list
[guavacontributors]: https://code.google.com/p/guava-libraries/people/list
