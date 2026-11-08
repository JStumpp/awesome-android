# Awesome Android [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/jstumpp/awesome-android/main/awesome-android.png">](https://github.com/jstumpp/awesome-android)

<p align="center">
  <a href="https://github.com/sindresorhus/awesome"><img alt="awesome" src="https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" /></a>
  <a href="https://github.com/JStumpp/awesome-android/actions/workflows/awesome-lint.yml"><img alt="Awesome Lint" src="https://github.com/JStumpp/awesome-android/actions/workflows/awesome-lint.yml/badge.svg" /></a>
  <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" />
</p>

A curated list of awesome Android libraries and resources. For general Java libraries have a look at [awesome-java](https://github.com/akullpp/awesome-java).

Awesome-Android is an amazing list for people who need a certain feature on their app, so the best ways to use are:
- Simply press <kbd>Ctrl</kbd> + <kbd>F</kbd> (or <kbd>⌘</kbd> + <kbd>F</kbd> on macOS) to search for a keyword
- Go through our Content Menu

## Contents
- [Emulators](#emulators)
- [Libraries](#libraries)
	- [Jetpack Compose](#jetpack-compose)
	- [Architecture](#architecture)
	- [Charts](#charts)
	- [Data binding](#data-binding)
	- [Dependency Injection](#dependency-injection)
	- [Game Development](#game-development)
	- [Security](#security)
	- [GUI](#gui)
	- [JSON](#json)
	- [Crash monitoring](#crash-monitoring)
	- [Networking](#networking)
	- [Logger](#logger)
	- [Database](#database)
	- [Testing](#testing)
	- [Tracking](#tracking)
	- [Maps](#maps)
	- [Utility](#utility)
	- [Debugging Tools](#debugging-tools)
	- [Wireless](#wireless)
	- [Chat & Messaging](#chat--messaging)
	- [Date & Time](#date--time)
	- [Payments](#payments)
	- [Google Play](#google-play)
	- [Code Quality](#code-quality)
	- [Other](#other)
- [Resources](#resources)
	- [Code examples](#code-examples)
	- [Podcasts](#podcasts)
	- [More lists of libraries](#more-lists-of-libraries)
- [Development Alternatives](#development-alternatives)
	- [Cross-Platform](#cross-platform)
	- [Kotlin Multiplatform](#kotlin-multiplatform)
- [Build & Performance](#build--performance)
- [Other Awesome Lists](#other-awesome-lists)

## Emulators
- [Android Emulator](https://developer.android.com/studio/run/emulator) - Official Android emulator integrated into Android Studio.
- [Genymotion](https://www.genymotion.com)

## Libraries

### Jetpack Compose

- [Jetpack Compose](https://developer.android.com/compose) - Modern toolkit for building native Android UI with declarative Kotlin APIs and Material 3 support.

### Architecture

- [Circuit](https://github.com/slackhq/circuit) - Modern architecture framework for building Android apps with Compose.
- [Decompose](https://github.com/arkivanov/Decompose) - Kotlin Multiplatform library for breaking down your code into lifecycle-aware business logic components.

### Charts

- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) - An Android chart and graph library supporting scaling and dragging by gesture.
- [Vico](https://github.com/patrykandpatrick/vico) - Modern chart library with support for both Jetpack Compose and Android Views.

### Data binding

- [Data Binding Library](https://developer.android.com/topic/libraries/data-binding/) - Official Android Data Binding Library to write declarative layouts and minimize the glue code necessary to bind application logic and layouts.

### Dependency Injection

- [Hilt](https://developer.android.com/training/dependency-injection/hilt-android) - Official dependency injection library built on top of Dagger for Android.
- [Dagger 2](https://github.com/google/dagger) - A fast dependency injector for Android and Java.
- [Koin](https://insert-koin.io/) - Lightweight dependency injection framework for Kotlin.

### Game Development

- [Libgdx](https://libgdx.com/) - Cross-platform game engine and SDK. [Open Source](https://github.com/libgdx/libgdx)
- [Vuforia](https://www.ptc.com/en/products/vuforia) - Augmented Reality library.
- [Unity](https://unity.com/features/multiplatform) - Cross-platform game creation system.
- [Godot](https://github.com/godotengine/godot) - Cross-platform 2/3D game engine with an IDE and under MIT license.

### Security

- [Google Tink](https://github.com/tink-crypto/tink-java) - Multi-language cross-platform cryptography library providing secure APIs for common cryptographic tasks.

### GUI

- [Material Components for Android](https://github.com/material-components/material-components-android) - Modular and customizable Material Design UI components for Android.
- [Navigation](https://developer.android.com/guide/navigation) - Framework for building in-app navigation with type-safe argument passing.
- [Pull to refresh](https://developer.android.com/reference/androidx/swiperefreshlayout/widget/SwipeRefreshLayout) - A swipe refresh layout is available in AndroidX.
- [TapTargetView](https://github.com/KeepSafe/TapTargetView) - An implementation of tap targets from the Material Design guidelines for feature discovery.
- [Litho (By Meta)](https://github.com/meta/litho) - A declarative framework for building efficient UIs on Android.
- [Liquid-Glass-Android](https://github.com/QWEA0/Liquid-Glass-Android) - Liquid glass effect for the Android View system.
- [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer) - Simple take on a material design navigation drawer.
- [AppIntro](https://github.com/AppIntro/AppIntro) - Library for creating beautiful intro slides for your app.
- [Lottie](https://github.com/airbnb/lottie-android) - Library for rendering After Effects animations natively on Android.
- [Android View Animations](https://github.com/daimajia/AndroidViewAnimations) - Cute view animation collection.
- [Compressor](https://github.com/zetbaitsu/Compressor) - Lightweight and powerful Android image compression library.
- [Material Dots Indicators](https://github.com/tommybuonomo/dotsindicator) - Three Material Dots Indicators styles for View Pagers.
- [Glide](https://github.com/bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling, Recommended by Google.
- [Fresco](https://github.com/meta/fresco) - An Android library for managing images and the memory they use.
- [Coil](https://github.com/coil-kt/coil) - Image loading for Android backed by Kotlin Coroutines.
- [Media3 (ExoPlayer)](https://github.com/androidx/media) - Jetpack Media3 support libraries for media use cases, including ExoPlayer, an extensible media player for Android.
- [CameraX](https://developer.android.com/training/camerax) - Jetpack library that makes camera app development easier with consistent API across devices.


### JSON

- [kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) - Kotlin multiplatform serialization library with JSON support.
- [Gson](https://github.com/google/gson) - Java library used for serializing and deserializing Java objects from and into JSON.
- [Jackson JSON Processor](https://github.com/FasterXML/jackson) - High-performance JSON processor.
- [Moshi](https://github.com/square/moshi) - A modern JSON library for Android and Java.
### Crash monitoring

- [Bugsnag](https://www.bugsnag.com/) - Cross platform error monitoring. Free tier. Support for SDK & NDK. Error reports include data on device, release, user, and allows arbitrary data.
- [Luciq](https://www.luciq.ai/) - Bug reporting, Crash Reporting, In-app Feedback (formerly Instabug).
- [Firebase Crashlytics](https://firebase.google.com/products/crashlytics) - Easy crash reporting solution. *Commercial (has free tier)*
- [Measure](https://github.com/measure-sh/measure/) - Open source tool to monitor crashes, ANRs, and performance of mobile apps. Can be self-hosted.
- [Sentry Android](https://github.com/getsentry/sentry-java) - Open source error tracking with real-time crash reporting. *Commercial (has free tier)*

### Networking

- [Retrofit](https://github.com/lysine-dev/retrofit) - Turns your REST API into a Java interface (continued project).
- [OkHttp](https://github.com/lysine-dev/okhttp) - An HTTP+SPDY client for Android and Java applications (continued project).
- [Ktor Client](https://github.com/ktorio/ktor) - Asynchronous HTTP client for Kotlin with multiplatform support.
- [Apollo Kotlin](https://github.com/apollographql/apollo-kotlin) - Strongly-typed GraphQL client for Kotlin and Java.
- [Android Volley](https://google.github.io/volley/) - Official Android HTTP library that makes networking for easier and faster.
- [Fast-Android-Networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking) - A Complete Fast Android Networking Library that also support HTTP/2.

### Logger
- [timber](https://github.com/JakeWharton/timber) - A logger with a small, extensible API which provides utility on top of Android's normal Log class.
- [Kermit](https://github.com/touchlab/Kermit) - Kotlin Multiplatform logging library with support for multiple platforms.
- [logger](https://github.com/orhanobut/logger) - Simple, pretty and powerful logger for Android.
- [LoggingInterceptor](https://github.com/ihsanbal/LoggingInterceptor) - An OkHttp interceptor which pretty logs request and response data.
- [Logback Android](https://github.com/tony19/logback-android) - Logback port to Android which provides a highly configurable logging framework for Android apps.
- [LogDog](https://log.dog) - Remote debugging/logging sdk (iOS and Android) with a web ui. Captures all logs and requests in real-time and allows to intercept them. 

### Database
- [Room](https://developer.android.com/training/data-storage/room) - Official SQLite object mapping library with compile-time verification of SQL queries.
- [SQLDelight](https://github.com/sqldelight/sqldelight) - Generates typesafe Kotlin APIs from SQL statements with Kotlin Multiplatform support.
- [ObjectBox](https://github.com/objectbox/objectbox-java) - Simple but powerful object database, optimized for performance & mobile.
- [requery](https://github.com/requery/requery) - Compile time ORM and SQL query library for Java & Android.
- [DBFlow](https://github.com/agrosner/DBFlow) - Fast and powerful ORM with compile-time annotation processing.
- [DbInspector](https://github.com/infinum/android_dbinspector) - Provides a simple way to view the contents of the in-app database for debugging purposes.
- [Nitrite Database](https://github.com/nitrite/nitrite-java) - A NoSQL embedded document store for Android with MongoDB like API.

### Testing

- [Espresso](https://developer.android.com/training/testing/espresso) - Official Android UI testing framework for writing reliable UI tests.
- [AndroidX Test](https://github.com/android/android-test) - Testing libraries for Android including JUnit rules and Espresso APIs.
- [Roboletric](https://robolectric.org/) - Unit test framework to run tests inside the JVM on your workstation, not in the emulator.
- [MockK](https://github.com/mockk/mockk) - Mocking library for Kotlin with natural syntax and comprehensive DSL.
- [Turbine](https://github.com/cashapp/turbine) - Testing library for Kotlin Flows with simple and expressive assertions.
- [Kotest](https://github.com/kotest/kotest) - Flexible and comprehensive testing framework for Kotlin with multiple testing styles.
- [Maestro](https://github.com/mobile-dev-inc/maestro) - Mobile UI testing framework for end-to-end testing with simple YAML-based syntax.
- [Paparazzi](https://github.com/cashapp/paparazzi) - Render Android screens as images for snapshot testing without a device or emulator.
- [Roborazzi](https://github.com/takahirom/roborazzi) - Screenshot testing library for Android using Robolectric.
- [Ghost in the Droid](https://github.com/ghost-in-the-droid/android-agent) - Python MCP server for AI agent control of Android and iOS devices via ADB and WebDriverAgent.
- [Droidline](https://github.com/KnifeLemon/Droidline) - Automate real Android phones from Python, Node.js, C# or a CLI over Wi-Fi, without ADB or root.

### Tracking

- [Mixpanel](https://mixpanel.com/) - Analytics platform to analyze the users.
- [Countly](https://countly.com/) - Open source mobile & web analytics, push notifications and crash reporting platform, based on Node.js, MongoDB and Linux.
- [CleverTap](https://clevertap.com) - Analytics platform and user-engagement platform with 1 million free events.

### Maps

- [android-maps-utils](https://github.com/googlemaps/android-maps-utils) - Utility library for Google Maps Android API with features like marker clustering and heat maps.
- [Maps Compose](https://github.com/googlemaps/android-maps-compose) - Jetpack Compose components for Google Maps.
- [GLMap](https://globus.software) - Crossplatform offline vector map with MapCSS styling. Offline search and offline navigation are included.

### Utility
- [Byte Buddy](https://bytebuddy.net) - Runtime code generation library with support for Android.
- [LeakCanary](https://github.com/square/leakcanary) - Catch memory leaks as they occur.
 
### Debugging Tools

- [Linx](https://github.com/pedrovgs/Lynx) - Show logcat inside the device for debug builds.
- [Chucker](https://github.com/ChuckerTeam/chucker) - An HTTP inspector for Android & OkHTTP (like Charles but on device).
- [Android Debug Database](https://github.com/amitshekhariitbhu/Android-Debug-Database) - Powerful library for debugging databases and shared preferences in Android applications.
- [Android Debug Bridge - ADB](https://github.com/mzlogin/awesome-adb/blob/master/README.en.md) - A command-line tool to assist in debugging Android-powered devices.
- [ADB Enhanced](https://github.com/ashishb/adb-enhanced) - A command-line wrapper around ADB for developers, so that, developers don't have to remember esoteric version-dependent commands.
- [handsets](https://github.com/elliotgao2/handsets) - Android control CLI that drives devices over ADB with no APK required.
- [Pidcat](https://github.com/JakeWharton/pidcat) - A colored command-line ADB wrapper that only shows log entries for a specific application package.
- [AppSpector](https://www.appspector.com/) - Remote Android and iOS debugging and data collection service. You can debug networking, logs, SQLite and mock device's geo location.


### Wireless

- [Kable](https://github.com/JuulLabs/kable) - Kotlin Asynchronous Bluetooth Low Energy library for Android and other platforms.
- [Nordic Android-BLE-Library](https://github.com/NordicSemiconductor/Android-BLE-Library) - Android BLE library from Nordic Semiconductor for reliable BLE communication.

### Chat & Messaging

- [Qiscus SDK](https://github.com/qiscus/qiscus-sdk-android) - Lightweight and powerful Android chat library. Allows you to easily integrating Qiscus engine with your apps to make cool chatting application.
- [Stream Chat](https://getstream.io/chat/sdk/android/tutorial/compose/) - Comprehensive SDK & Components for real-time chat, powered by [Stream](https://getstream.io/chat/).

### Date & Time

- [kotlinx-datetime](https://github.com/Kotlin/kotlinx-datetime) - A multiplatform Kotlin library for working with date and time.

### Payments

- [Square In-App Payments for Android](https://developer.squareup.com/docs/in-app-payments-sdk/build-on-android) - Integrate Square payments into your mobile app with Digital wallet and stored card support for quick checkout.

### Google Play

- [Google Play Billing](https://developer.android.com/google/play/billing) - Official library for in-app purchases and subscriptions on Google Play.
- [In-App Updates](https://developer.android.com/guide/playcore/in-app-updates) - Keep your app up to date with flexible and immediate in-app update flows.
- [In-App Review](https://developer.android.com/guide/playcore/in-app-review) - Prompt users to submit Play Store ratings and reviews without leaving your app.

### Code Quality

- [Detekt](https://github.com/detekt/detekt) - Static code analysis tool for Kotlin with over 200 built-in rules.
- [ktlint](https://github.com/ktlint/ktlint) - Anti-bikeshedding Kotlin linter with built-in formatter.
- [Spotless](https://github.com/diffplug/spotless) - Code formatter that supports multiple languages and can enforce consistent formatting in builds.

### Other

- [AndroidX](https://developer.android.com/jetpack/androidx) - The modern Android development toolkit that replaces the Android Support Library, providing backward-compatible versions of Android framework APIs.
- [Kotlin Coroutines](https://github.com/Kotlin/kotlinx.coroutines) - Library for asynchronous programming with coroutines and Flow for reactive streams.
- [WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager) - Schedule deferrable and guaranteed background work with a flexible API.
- [Paging](https://developer.android.com/topic/libraries/architecture/paging/v3-overview) - Load and display pages of data from a larger dataset with efficient memory usage.
- [DataStore](https://developer.android.com/topic/libraries/architecture/datastore) - Modern data storage solution using Kotlin coroutines and Flow to replace SharedPreferences.
- [Arrow](https://github.com/arrow-kt/arrow) - Functional companion to Kotlin's Standard Library with typed functional programming support.
- [KSP](https://github.com/google/ksp) - Kotlin Symbol Processing API for writing lightweight compiler plugins with better performance than kapt.
- [Google Play Services](https://developers.google.com/android/guides/overview) - Library to access Google services, such as account syncing, Google+ (sharing, single sign-on), Google Maps, Location APIs, Google Play Games, Cloud Messaging, Android Device Manager, and others.
- [ML Kit](https://developers.google.com/ml-kit) - Mobile SDK for machine learning tasks like barcode scanning, text recognition, and face detection.
- [Google Code Scanner](https://developers.google.com/ml-kit/vision/barcode-scanning/code-scanner) - High-quality barcode scanning without requiring app permissions using Google Play Services.
- [Guava: Google Core Libraries for Java](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth.
- [RxJava](https://github.com/ReactiveX/RxJava) - Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM.
- [RxAndroid](https://github.com/ReactiveX/RxAndroid) - Adds minimum RxJava bindings for easy writing of reactive Android java code.
- [AboutLibraries](https://github.com/mikepenz/AboutLibraries) - Automatically generates an About this app section, with a list of used libraries.
- [refreshVersions](https://github.com/Splitties/refreshVersions) - A Kotlin dsl to simplify dependencies management.
- [Licensee](https://github.com/cashapp/licensee) - Gradle plugin which validates the licenses of your dependency graph match what you expect, or it fails your build!

## Resources

- [Programming Community Curated Resources for Learning Android Development](https://hackr.io/tutorials/learn-android-development) - Android Tutorials & Courses submitted and voted by the programming community.
- [Vogella Tutorials](https://www.vogella.com/tutorials/android.html) - Very good tutorials by Lars Vogel.
- [Android API Levels](https://apilevels.com/) - A quick reference table of Android versions with SDK & API levels, version codes, codenames, cumulative usage, and more.
- [Android Hive Tutorials](https://www.androidhive.info) - Very good tutorials for beginners.
- [Android Weekly](https://androidweekly.net) - Newsletter with weekly information about Android.
- [Android Asset Studio](https://romannurik.github.io/AndroidAssetStudio/) - Generator for icons and other assets.
- [Device Art Generator](https://developer.android.com/distribute/marketing-tools/device-art-generator) - Wraps app screenshots in real device artwork.
- [Pencil Project](https://pencil.evolus.vn/) - An open source prototyping software.
- [Future Studio](https://futurestud.io/tutorials/tag/android) - Extensive Android tutorials on Retrofit, Glide & Gson.
- [Android Tips & Tricks](https://github.com/nisrulz/android-tips-tricks) - Cheatsheet about tips and tricks for Android Development.
- [Google Developers Training](https://developer.android.com/courses/) -  Google Developers Official Training page has list of various useful learning resources for beginner as well seasoned developer.
- [Mindorks](https://mindorks.com/) - Become a complete and happy Android developer.
- [AndroidVille](https://ayusch.com/) - Become a better Android Engineer. A website dedicated to Android Development covering advanced topics such as RxJava, Android Zygote and much more.
- [Android Stack Weekly](https://canopas.com/tagged/canopas-android-weekly) - A weekly newsletter on new development and updates of Android universe.
- [Roadmap.sh Android Roadmap](https://roadmap.sh/android) - Community-created Android developer roadmap.

### Code examples
- [Now in Android](https://github.com/android/nowinandroid) - Official sample app demonstrating modern Android development best practices.
- [Compose Samples](https://github.com/android/compose-samples) - Official sample apps showcasing Jetpack Compose UI toolkit.
- [Android Architecture Blueprints](https://github.com/android/architecture-samples) - The Android Architecture Blueprints project demonstrates strategies to help solve or avoid common Android problems.

### Podcasts
- [Fragmented](https://fragmentedpodcast.com/) - Is the Android developer podcast where Donn Felker and Kaushik Gopal talk about building good software and becoming better Android developers.
- [Android Developers Backstage](https://androidbackstage.blogspot.com/) - Is a podcast by and for Android developers. Hosted by developers from the Android engineering team, this show covers topics of interest to Android programmers, with in-depth discussions and interviews with engineers on the Android team at Google.
- [Android Dialogs](https://www.youtube.com/channel/UCMEmNnHT69aZuaOrE-dF6ug/feed) - Is a video based podcast, where they have bite-sized conversations with people from the Android community.
- [Talking Kotlin](https://talkingkotlin.com/) - A Podcast on Kotlin and more.
- [Android Authority](https://www.androidauthority.com/podcast/) - Is a weekly Android podcast hosted by Adam Doud, Joe Hindy, and Jonathan Feist from the Android Authority team.

### More lists of libraries
- [Square libraries](https://square.github.io/) - Multiple high quality libraries by square.
- [Awesome Android @LibHunt](https://android.libhunt.com) - Your go-to Android Toolbox.
- [Android Store](https://mindorks.com/android/store) - Search Android Libraries, Projects, and Tools.

## Development Alternatives

My personal recommendation is (for now) to use the Android SDK to build a native app. Scala and Kotlin are both options; multidex requirements depend on an app's method-reference count and minimum SDK level, not its language. Cross-platform alternatives can also be useful when they fit a project's requirements.

### Cross-Platform

- [Flutter](https://flutter.dev/) - Google's mobile app SDK for high-quality native interfaces for Android and iOS in very quick time.
- [React Native](https://github.com/react/react-native) - A framework for building native apps with React.
- [.NET MAUI](https://github.com/dotnet/maui) - .NET Multi-platform App UI, the evolution of Xamarin.Forms, for building native cross-platform apps with .NET and C#.
- [NativeScript](https://nativescript.org/) - An open-source framework to build native iOS and Android apps with JavaScript from a single code base.
- [Ionic Framework](https://ionicframework.com) - A framework to build hybrid apps with mobile-optimized HTML, CSS and JS with AngularJS.
- [Apache Cordova](https://github.com/apache/cordova-android) - Cordova based applications are, at the core, applications written with web technology: HTML, CSS and JavaScript.
- [Capacitor](https://github.com/ionic-team/capacitor) - Build cross-platform Native Progressive Web Apps for iOS, Android, and the web. Very promising Cordova alternative.
- [Solar2D](https://github.com/coronalabs/corona) - Cross-platform framework for creating 2D games and apps (formerly Corona SDK).
- [BeeWare](https://github.com/beeware/toga) - Write native Android apps in Python using Toga and Briefcase.
- [Flet](https://github.com/flet-dev/flet) - Build Flutter apps using Python.
- [Kivy](https://github.com/kivy/kivy) - Open source Python framework for Android apps, packaged with Buildozer.
- [Macroid](https://github.com/47deg/macroid) - A modular functional UI language for Android.

### Kotlin Multiplatform
- [Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform) - Jetpack Compose for iOS, Desktop, and Web built on Kotlin Multiplatform.
- [KuiklyUI](https://github.com/Tencent-TDS/KuiklyUI) - Kotlin Multiplatform UI framework supporting Android, iOS, and other platforms.
- [Kotlin coding challenges](https://github.com/igorwojda/kotlin-coding-challenges) - Set of programming challenges thats helps to improve whiteboard coding and problem-solving skills.

## Build & Performance

- [R8](https://developer.android.com/topic/performance/app-optimization/enable-app-optimization) - Default code shrinker and optimizer for Android apps.
- [ProGuard](https://www.guardsquare.com/proguard) - Open-source Java bytecode optimizer and shrinker for Android apps.
- [ProGuard Playground](https://playground.proguard.com/) - Interactive online tool for visualizing and testing ProGuard and R8 keep rules.
- [Booster](https://github.com/didi/booster) - An optimization toolkit for Android applications.

## Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.
