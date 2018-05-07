# SizesDP
Customizable Sizes


### Follow these steps to use this library:
#### In build.gradle (Project)

``` gradle
allprojects {
    repositories {
        ...
        maven { url "https://jitpack.io" }
    }
}
``` 

And then in the other gradle file(may be your app gradle or your own module library gradle, but never add in both of them to avoid conflict.)

``` gradle
dependencies {
	        implementation 'com.github.kapilmhr:SizesDP:1.0'
          }
```
