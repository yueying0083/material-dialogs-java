# Material Dialogs Java
Based on <a href="https://github.com/afollestad/material-dialogs" target="_blank">afollestad's material-dialogs v0.9.6.0</a> change android support to androidx

# Gradle Dependency

### Repository

The Gradle dependency is available via [jCenter](https://bintray.com/devyy093/material-dialogs-java/core).
jCenter is the default Maven repository used by Android Studio.

The minimum API level supported by this library is API 14.

### Core

The *core* module contains all the major classes of this library, including `MaterialDialog`.
You can create basic, list, single/multi choice, progress, input, etc. dialogs with core.

```gradle
dependencies {
	// ... other dependencies here
	// not available right now
    implementation 'com.afollestad.material-dialogs-java:core:0.9.6.0-androidx'
}
```

### Commons

The *commons* module contains extensions to the library that not everyone may need. This includes the
`ColorChooserDialog`, `FolderChooserDialog`, the Material `Preference` classes, and `MaterialSimpleListAdapter`/`MaterialSimpleListItem`.

```gradle
dependencies {
    // ... other dependencies here
    // not available right now
    implementation 'com.afollestad.material-dialogs-java:core:0.9.6.0-androidx'
}
```
