This is a Kotlin Multiplatform project targeting Android, Web, and Desktop.

The project follows the recommended Kotlin Multiplatform structure by keeping shared code separate from platform entry points:

* `/composeApp` contains shared Compose UI.
* `/shared` contains shared application logic and platform-specific implementations.
* `/androidApp` contains the Android application entry point and resources.
* `/desktopApp` contains the desktop application entry point and packaging configuration.
* `/webApp` contains the Wasm application entry point and web resources.

Learn more about [Kotlin Multiplatform](https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html),
[Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform/#compose-multiplatform),
[Kotlin/Wasm](https://kotl.in/wasm/)…

We would appreciate your feedback on Compose/Web and Kotlin/Wasm in the public Slack channel [#compose-web](https://slack-chats.kotlinlang.org/c/compose-web).
If you face any issues, please report them on [GitHub](https://github.com/JetBrains/compose-multiplatform/issues).

You can open the web application by running the `:webApp:wasmJsBrowserDevelopmentRun` Gradle task.