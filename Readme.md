# Javadoc Themer

Give your boooring javadocs a splash of colors!

Goto [webapp](https://nisrulz.com/javadoc-themer/)

### Featured in

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-javadoc--themer-green.svg?style=true)](https://android-arsenal.com/details/1/4196) [![AndroidDev Digest](https://img.shields.io/badge/AndroidDev%20Digest-%2399-blue.svg)](https://www.androiddevdigest.com/digest-99/)

### Show some :heart:

[![GitHub stars](https://img.shields.io/github/stars/nisrulz/javadoc-themer.svg?style=social&label=Star)](https://github.com/nisrulz/javadoc-themer) [![GitHub forks](https://img.shields.io/github/forks/nisrulz/javadoc-themer.svg?style=social&label=Fork)](https://github.com/nisrulz/javadoc-themer/fork) [![GitHub watchers](https://img.shields.io/github/watchers/nisrulz/javadoc-themer.svg?style=social&label=Watch)](https://github.com/nisrulz/javadoc-themer) [![GitHub followers](https://img.shields.io/github/followers/nisrulz.svg?style=social&label=Follow)](https://github.com/nisrulz/javadoc-themer)

## Web app screenshot

![screenshot](img/javadocthemer.png)

## Output

![screenshotdiff](img/javadocdiff.png)

### *Command line arguments*

```bash
-encoding UTF-8 -docencoding utf-8 -charset utf-8 \
-stylesheetfile <location_of_generated_stylesheet>/javadoc_stylesheet.css 
```

If you want to use/include custom tags in your javadoc, use `-tag custom.<tagname>:a:"<Tag_Title_in_Javadoc>"` i.e

```bash
-tag custom.package:a:"Package" -tag custom.company:a:"Company"
```

hence your complete command line arguments becomes

```bash
-encoding UTF-8 -docencoding utf-8 -charset utf-8 \
-tag custom.package:a:"Package" -tag custom.company:a:"Company"  \
-stylesheetfile <location_of_generated_stylesheet>/javadoc_stylesheet.css
```

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
