# AndroidTip
安卓积累

* dexCount插件使用
``` gradle
apply plugin: 'com.getkeepsafe.dexcount'

buildscript {
    repositories {
        jcenter()
    }
    dependencies {
        classpath 'com.getkeepsafe.dexcount:dexcount-gradle-plugin:0.7.3' //  /app/build/outputs/dexcount/debug.txt dex func count
    }
}

```
