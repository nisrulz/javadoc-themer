# **Javadoc Themer**

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
