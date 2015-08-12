gradle-lintrules-plugin
======================

Lintrules is a [Gradle](https://www.gradle.org) plugin that allows bundling custom lint rules with AARs.

Usage
-----
Add the following to buildscript:
```groovy
buildscript {
    dependencies {
        classpath 'com.kageiit:lintrules:1.+'
    }
}
```

Apply and configure lintrules like so:
```groovy
apply plugin: 'com.kageiit.lintrules'

dependencies {
    lintRules project(':lint')
}
```

License
-------

    Copyright 2015 Gautam Korlam

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
