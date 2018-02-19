# first install
add this below _repository_ to build.gradle than `clean & rebuild`
```
allprojects {
    repositories {
        ...
        maven {
            url "https://maven.google.com"
        }
        ...
    }
}
```


