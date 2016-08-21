# **Javadoc Themer**
Give your boooring javadocs a splash of colors!

Goto [webapp](http://javadocthemer.crushingcode.co/)

### Featured in
[![AndroidDev Digest](https://img.shields.io/badge/AndroidDev%20Digest-%2399-blue.svg)](https://www.androiddevdigest.com/digest-99/)

### Show some :heart:
[![GitHub stars](https://img.shields.io/github/stars/nisrulz/javadoc-themer.svg?style=social&label=Star)](https://github.com/nisrulz/javadoc-themer) [![GitHub forks](https://img.shields.io/github/forks/nisrulz/javadoc-themer.svg?style=social&label=Fork)](https://github.com/nisrulz/javadoc-themer/fork) [![GitHub watchers](https://img.shields.io/github/watchers/nisrulz/javadoc-themer.svg?style=social&label=Watch)](https://github.com/nisrulz/javadoc-themer) [![GitHub followers](https://img.shields.io/github/followers/nisrulz.svg?style=social&label=Follow)](https://github.com/nisrulz/javadoc-themer)  
[![Twitter Follow](https://img.shields.io/twitter/follow/nisrulz.svg?style=social)](https://twitter.com/nisrulz) 

## Web app screenshot

![screenshot](https://github.com/nisrulz/javadoc-themer/raw/master/img/javadocthemer.png)


## Output

![screenshotdiff](https://github.com/nisrulz/javadoc-themer/raw/master/img/javadocdiff.png)

###*Command line arguments*

```bash
-bootclasspath <location_of_android_sdk>/platforms/android-23/android.jar -encoding UTF-8 -docencoding utf-8 -charset utf-8 -stylesheetfile <location_of_generated_stylesheet>/javadoc_stylesheet.css

```
If you want to use/include custom tags in your javadoc, use `-tag custom.<tagname>:a:"<Tag_Title_in_Javadoc>"` i.e
```bash
-tag custom.package:a:"Package" -tag custom.company:a:"Company" 

```

hence your complete command line arguments becomes
```bash
-bootclasspath <location_of_android_sdk>/platforms/android-23/android.jar -encoding UTF-8 -docencoding utf-8 -charset utf-8 -tag custom.package:a:"Package" -tag custom.company:a:"Company"  -stylesheetfile <location_of_generated_stylesheet>/javadoc_stylesheet.css
```

# Pull Requests
I welcome and encourage all pull requests. It usually will take me within 24-48 hours to respond to any issue or request.


### Created & Maintained By
[Nishant Srivastava](https://github.com/nisrulz) ([@nisrulz](https://www.twitter.com/nisrulz))

License
=======

    Copyright 2016 Nishant Srivastava

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
