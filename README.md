# Install scripts to facilitate pushing artifacts to JCenter/Bintray

Add the following to the end of the library module build.gradle file to access the install scripts 

```
// Place it at the end of the file
apply from: 'https://raw.githubusercontent.com/nisrulz/JCenter/master/installv1.gradle'
apply from: 'https://raw.githubusercontent.com/nisrulz/JCenter/master/bintrayv1.gradle'
```

# License

Apache 2.0
