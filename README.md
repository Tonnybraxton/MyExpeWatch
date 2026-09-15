# MyExpeWatch

An incomplete Android project scaffold for an expense-tracking application, using Kotlin and Gradle configuration.

## Current state

The repository contains top-level build configuration and a task list. The settings refer to an `app` module, but the module source, Gradle wrapper directory, and version catalogue are missing from this checkout. It cannot currently build or launch an Android app.

The Gradle settings still use the name `SpendLess`; [TODO.md](TODO.md) records planned MyExpeWatch naming and interface fixes. Those referenced interface files are not present here.

## Repository contents

| File | Purpose |
| --- | --- |
| [build.gradle.kts](build.gradle.kts) | Top-level Android and Kotlin plugin declarations |
| [settings.gradle.kts](settings.gradle.kts) | Plugin repositories and module configuration |
| [gradle.properties](gradle.properties) | Gradle settings |
| [TODO.md](TODO.md) | Outstanding implementation notes |

## Continuing development

1. Restore the application source and missing Gradle wrapper/version catalogue files from the original project.
2. Configure the Android SDK for your own machine; the checked-in local SDK path is machine-specific.
3. Open the completed project in Android Studio and synchronize Gradle.
4. Work through the task list, then document the verified build command and add screenshots of the running app.

## Contributing

Include the restored module structure and Android Studio/Gradle versions with any proposed build fix. Report only checks that you actually ran.

## License

See the existing [GNU GPL v3 license text](LICENSE.md).
