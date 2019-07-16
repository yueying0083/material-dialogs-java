# Material Dialogs


# Sample Project

You can download the latest sample APK from this repo here: https://github.com/afollestad/material-dialogs/blob/master/sample/sample.apk

It's also on Google Play:

<a href="https://play.google.com/store/apps/details?id=com.afollestad.materialdialogssample" target="_blank">
  <img alt="Get it on Google Play"
       src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" height="60"/>
</a>

Having the sample project installed is a good way to be notified of new releases. Although Watching this 
repository will allow GitHub to email you whenever I publish a release.

---

# Gradle Dependency

### Repository

The Gradle dependency is available via [jCenter](https://bintray.com/drummer-aidan/maven/material-dialogs:core/view).
jCenter is the default Maven repository used by Android Studio.

The minimum API level supported by this library is API 14.

### Core

The *core* module contains all the major classes of this library, including `MaterialDialog`.
You can create basic, list, single/multi choice, progress, input, etc. dialogs with core.

```gradle
dependencies {
	// ... other dependencies here
    implementation 'com.afollestad.material-dialogs-java:core:0.9.6.0-androidx'
}
```

### Commons

The *commons* module contains extensions to the library that not everyone may need. This includes the
`ColorChooserDialog`, `FolderChooserDialog`, the Material `Preference` classes, and `MaterialSimpleListAdapter`/`MaterialSimpleListItem`.

```gradle
dependencies {
    // ... other dependencies here
    implementation 'com.afollestad.material-dialogs-java:core:0.9.6.0-androidx'
}
```

It's likely that new extensions will be added to commons later.

---
