# restfull-api

Step 1. Add it in your root build.gradle at the end of repositories:
```
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```
Step 2. Add the dependency
```
dependencies {
        implementation 'com.github.yeild-android:restfull-api:${Tag}'
}
```

Step 3. 在app的build.gradle文件中配置使用java8编译：
```
android {
  ...
  compileOptions {
    sourceCompatibility JavaVersion.VERSION_1_8
    targetCompatibility JavaVersion.VERSION_1_8
  }
}
```
