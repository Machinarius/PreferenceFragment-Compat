Support PreferenceFragment
=====================================

Unofficial PreferenceFragment compatibility layer for Android 1.6 and up.

### About the status of the library
Some people have rightfully forked this repo, those forks may be a better alternative than this repo as I am no longer involved in Android development. 

How to reference this library?
====================================

Make sure you have maven central listed as a repository on your build.gradle like this:

```groovy
repositories {
    mavenCentral()
}
```

Add the dependency to your build.gradle file like this:

```groovy
compile 'com.github.machinarius:preferencefragment:0.1.1'
```
The fix has been deployed, no more @aar suffix

How to use it?
===================================

Just extend PreferenceFragment and follow the Settings developer guide like if this layer wasn't even there to begin with.

http://developer.android.com/guide/topics/ui/settings.html

Roadmap
==================================
- Bump the presentation of the settings on Gingerbread and lower with some Holo love
- Include a handful of useful extra preferences
