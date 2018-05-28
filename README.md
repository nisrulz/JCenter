# Install scripts to facilitate pushing artifacts to JCenter/Bintray

> [Read the blogpost here](http://crushingcode.nisrulz.com/publish-your-android-library-via-jcenter/)

Add the below to your root `build.gradle` file

```
// Required plugins added to classpath to facilitate pushing to Jcenter/Bintray
classpath 'com.jfrog.bintray.gradle:gradle-bintray-plugin:1.8.0'
classpath 'com.github.dcendents:android-maven-gradle-plugin:2.1'
```

Add the following to the end of the library module build.gradle file to access the install scripts

```
// Place it at the end of the file
apply from: 'https://raw.githubusercontent.com/nisrulz/JCenter/master/installv1.gradle'
apply from: 'https://raw.githubusercontent.com/nisrulz/JCenter/master/bintrayv1.gradle'
```

> This repository is maintained by [Nishant Srivastava](https://github.com/nisrulz) ([@nisrulz](https://www.twitter.com/nisrulz))

# License

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
