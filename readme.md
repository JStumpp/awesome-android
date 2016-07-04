# Awesome Android [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Android [libraries](#libraries) and [resources](#resources). For general Java libraries have a look at [awesome-java](https://github.com/akullpp/awesome-java).

- [Emulators](#emulators)
- [Libraries](#libraries)
    - [Charts](#charts)
    - [Cloud Services](#cloud-services)
    - [Dependency Injection](#dependency-injection)
    - [Game Development](#game-development)
    - [GUI](#gui)
        - [ActionBar](#actionbar)
        - [Navigation](#navigation)
        - [Animations](#animations)
        - [Images](#images)
        - [Inputs](#inputs)
        - [Loading images](#loading-images)
    - [JSON](#json)
    - [Crash monitoring](#crash-monitoring)
    - [Networking](#networking)
    - [Notifications](#notifications)
    - [Database](#database)
        - [ORM](#orm)
    - [REST](#rest)
    - [Testing](#testing)
    - [Tracking](#tracking)
    - [Maps](#maps)
    - [Utility](#utility)
    - [Debugging tools](#debugging-tools)
    - [Wireless](#wireless)
    - [Chat and Messaging](#chat--messaging)
    - [Other](#other)
- [Resources](#resources)
    - [More lists of libraries](#more-lists-of-libraries)
- [Development Alternatives](#development-alternatives)
    - [C#](#c)
    - [HTML, CSS and Javascript](#html-css-and-javascript)
    - [Lua](#lua)
    - [Scala](#scala)
    - [Groovy](#groovy)
    - [Kotlin](#kotlin)
- [Performance](#performance)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Emulators
- [AMIDuOS](https://www.amiduos.com)
- [AndY](http://andyroid.net)
- [ARChon](https://archon-runtime.github.io)
- [BlueStacks](http://www.bluestacks.com)
- [Droid4X](http://www.droid4x.com)
- [Genymotion](https://www.genymotion.com)
- [nox](http://en.bignox.com)
- [Xamarin](https://www.xamarin.com)

## Libraries

### Charts

- [AChartEngine](https://github.com/ddanny/achartengine) - Charting Engine.
- [EazeGraph](https://github.com/blackfizz/EazeGraph) - Chart and graph library.
- [WilliamChart](https://github.com/diogobernardino/WilliamChart) - Chart library with good motion capabilities.
- [HelloCharts](https://github.com/lecho/hellocharts-android) - Chart and graph library with support for scaling, scrolling and animations.
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) - An Android chart and graph library supporting scaling and dragging by gesture.

### Cloud Services

* [CloudRail](https://cloudrail.com) - Unified API Library for: Cloud Storage, Social Profiles, Payment, Email, SMS & POIs.

### Data binding

- [Anvil](https://github.com/zserge/anvil) - A small library to create reactive UI components, inspired by React. Provides data binding and event listener binding, fits well for MVVM.
- [RoboBinding](https://github.com/RoboBinding/RoboBinding) - A data-binding Presentation Model (MVVM) framework for the Android platform.
- [Data Binding Library](https://developer.android.com/topic/libraries/data-binding/index.html) - Official Android Data Binding Library to write declarative layouts and minimize the glue code necessary to bind application logic and layouts.

### Dependency Injection

- [RoboGuice](https://github.com/roboguice/roboguice) - Dependency injection framework for Android.
- [Dagger](https://github.com/square/Dagger) - Dependency injection framework for Java and Android.
- [Dagger 2](https://github.com/google/dagger) - A fast dependency injector for Android and Java.
- [Butter Knife](http://jakewharton.github.io/butterknife/) - View "injection" library for Android.
- [AndroidAnnotations](https://github.com/excilys/androidannotations) - Java annotations with dependency injection at compile time.

### Game Development

- [AndEngine](http://www.andengine.org/) - Free, Fun and Fast Android 2D OpenGL Game Engine.
- [Libgdx](https://libgdx.badlogicgames.com/) - Cross-platform game engine and SDK. [Open Source](https://github.com/libGDX/libGDX)
- [Vuforia](https://www.vuforia.com/) - Augmented Reality library.
- [Unity](http://unity3d.com/unity/multiplatform) - Cross-platform game creation system.
- [Rajawali](https://github.com/Rajawali/Rajawali) - Android OpenGL ES 2.0/3.0 Engine

### GUI

- [Pull to refresh](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html) - A swipe refresh layout is available in the v4 support library.
- [Cardslib](https://github.com/gabrielemariotti/cardslib) - Android Library to build a UI Card.
- [AndroidStaggeredGrid](https://github.com/etsy/AndroidStaggeredGrid) - Grid view which supports multiple columns with rows of varying sizes.
- [AndroidQuery](https://github.com/androidquery/androidquery) - Android-Query (AQuery) is a light-weight library for doing asynchronous tasks and manipulating UI elements in Android.
- [Flow](https://github.com/square/flow) - Library that helps with describing an app as a collection of moderately independent screens.
- [Crouton](https://github.com/keyboardsurfer/Crouton) - Context sensitive notifications for Android
- [DragSortListView](https://github.com/bauerca/drag-sort-listview) - Extension of the Android ListView that enables drag-and-drop reordering (No longer maintained).
- [MaterialProgressBar](https://github.com/DreaminginCodeZH/MaterialProgressBar) - Material design ProgressBar with consistent appearance.
- [AndroidFillableLoaders](https://github.com/JorgeCastilloPrz/AndroidFillableLoaders) - Fillable progress view working with SVG paths. Nice option too for creating interesting app logos.
- [NexusDialog](https://github.com/dkharrat/NexusDialog) - Allows you to easily and quickly create forms in Android with little code.
- [Snap RecyclerView Utils](https://prashantsolanki.com/Snap-RecyclerView-Utils/) - Populate Single or multiple Layout RecyclerView without creating an Adapter.
- [SwipeableCard](https://github.com/michelelacorte/SwipeableCard) - Implementation of swipe card like StreetView!!
- [ElasticProgressBar](https://github.com/michelelacorte/ElasticProgressBar) - Beautiful loading bar.
- [EntryScreenManager](https://github.com/kunall17/EntryScreenManager) - Intro/Entry/Walkthrough/Starting Screens.
- [Material-Calendar-View](https://github.com/BlackBoxVision/material-calendar-view) - Material Design Calendar compatible with API 8+
- [SectionedRecyclerViewAdapter](https://github.com/luizgrp/SectionedRecyclerViewAdapter) - An Adapter that allows a RecyclerView to be split into Sections with headers and/or footers.
- [DragListView](https://github.com/woxblom/DragListView) - Drag and drop to reorder items in a list, grid or board.

#### ActionBar
- [ActionBarSherlock](http://actionbarsherlock.com) - ActionBar for older Android versions.
- [FadingActionBar](https://github.com/ManuelPeinado/FadingActionBar) - Fading action bar effect that can be seen in the new Play Music app.

#### Navigation
- [SlidingMenu](https://github.com/jfeinstein10/SlidingMenu) - Library to create applications with slide-in menus.
- [SlidingTutorial](https://github.com/Cleveroad/slidingtutorial-android) - Simple library that helps to create awesome sliding android app tutorials.
- [PagerSlidingTabStrip](https://github.com/astuetz/PagerSlidingTabStrip) - An interactive indicator to navigate between the different pages of a ViewPager.
- [Page View indicator](https://github.com/JakeWharton/ViewPagerIndicator) - Support for horizontally scrolling ViewPager.
- [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer) - Simple take on a material design navigation drawer.

#### Animations
- [NineOldAndroids](https://github.com/JakeWharton/NineOldAndroids) - Library for using the Honeycomb animation API on all versions of the platform back to 1.0.
- [Rebound](https://github.com/facebook/rebound) - Rebound is a java library that models spring dynamics.
- [Android View Animations](https://github.com/daimajia/AndroidViewAnimations) - Cute view animation collection.
- [Android-Transition](https://github.com/kaichunlin/android-transition) - Allows the easy creation of view transitions that react to user inputs.
- [Android-View-Actions](https://github.com/dtx12/AndroidAnimationsActions) - Makes creating complex animations for views easy.

#### Images

- [android-crop](https://github.com/jdamcd/android-crop) - Library project for cropping images.
- [CircularImageView](https://github.com/Pkmmte/CircularImageView) - Custom view for circular images while maintaining the best draw performance.
- [Android-Image-Filter](https://github.com/ragnraok/android-image-filter) - Library project for applying image filters easily.
- [Compressor](https://github.com/zetbaitsu/Compressor) - Compressor is a lightweight and powerful android image compression library.

#### Inputs

- [FloatingLabel](https://github.com/hardik-trivedi/FloatingLabel) - FloatingLabel Allows you to create a blow kind of EditText. *Doesn't have Gradle or Maven Support.*
- [MaterialEditText](https://github.com/rengwuxian/MaterialEditText) - Supporting Floating Labels, Single Line Ellipsis, Max/Min Characters, Helper Text and Error Text with Custom Colors.
- [Emojicon](https://github.com/rockerhieu/emojicon) - Adds emoticons to your app

#### Loading Images

- [Picasso](https://github.com/square/picasso) - A powerful image downloading and caching library for Android.
- [Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) - Asynchronous, out of the box loading and caching of images.
- [Glide](https://github.com/bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling,Recommended by google.
- [Fresco](https://github.com/facebook/fresco) - An Android library for managing images and the memory they use.
- [Glide Bitmap Pool](https://github.com/amitshekhariitbhu/GlideBitmapPool) - Glide Bitmap Pool is a memory management library for reusing the bitmap memory.

### JSON

- [Gson](https://github.com/google/gson) - Gson is a Java library used for serializing and deserializing Java objects from and into JSON.
- [Jackson JSON Processor](https://github.com/FasterXML/jackson) - High-performance JSON processor.

### Crash monitoring

- [Fabric Crashlytics](https://get.fabric.io/) - Easy crash reporting solution.
- [HockeyApp](https://www.hockeyapp.net/) - Distribution, Crash Reports, Feedback and Analytics
- [Splunk MINT](https://mint.splunk.com/) - Monitoring, Crash Reports, Real tima data, Statistic.
- [Bugsnag](https://bugsnag.com/) - Cross platform error monitoring.

### Networking

- [Ion](https://github.com/koush/ion) - Good networking library for android.
- [OkHttp](https://github.com/square/okhttp) - An HTTP+SPDY client for Android and Java applications.
- [Asynchronous Http Client](https://github.com/loopj/android-async-http) - An Asynchronous HTTP Library.
- [RoboSpice](https://github.com/stephanenicolas/robospice) - Library that makes writing asynchronous network requests easy.
- [IceNet](https://github.com/anton46/IceNet) - Fast, Simple and Easy Networking for Android
- [Android Volley](https://developer.android.com/training/volley/index.html) - Official Android HTTP library that makes networking for easier and faster.
- [IceSoap](https://github.com/AlexGilleran/IceSoap) - Easy, asynchronous, annotation-based SOAP for Android.
- [node-android](https://github.com/InstantWebP2P/node-android) - Run Node.js on Android.
- [HappyDns](https://github.com/qiniu/happy-dns-android) - A Dns library, user can use custom dns server, dnspod httpdns. Only support A record.
- [RESTMock](https://github.com/andrzejchm/RESTMock) - HTTP Web server for mocking API responses in Android Instrumentation tests.
- [AndroidNetworking](https://github.com/amitshekhariitbhu/AndroidNetworking) - Android Networking is a powerful library for doing any type of networking in Android applications.

### Notifications
- [android-remote-notifications](https://github.com/kaiwinter/android-remote-notifications) - Pulls notifications from a remote JSON file and shows them in your app.
- [Android HeartBeat Fixer](https://github.com/joaopedronardari/AndroidHeartBeatFixer) - Way to set heartbeat interval and users receive PushNotifications from GCM.

### Database
- [Cupboard](https://bitbucket.org/littlerobots/cupboard) - Access the sqlite easily via direct database access or through the ContentProvider framework.
- [DbInspector](https://github.com/infinum/android_dbinspector) - Provides a simple way to view the contents of the in-app database for debugging purposes.
- [Realm](https://github.com/realm/realm-java) - The alternative to SQLite and ORMs: Simple, modern and fast! Object oriented API and multi platform support.
- [RestorableSQLiteDatabase](https://github.com/yaa110/RestorableSQLiteDatabase) - A wrapper to replicate android's SQLiteDatabase with restoring capability.

#### ORM

- [requery](https://github.com/requery/requery) - Compile time ORM and SQL query library for Java & Android.
- [GreeDAO](http://greenrobot.org/greendao/) - Light & fast ORM solution.
- [ORMLite](http://ormlite.com/sqlite_java_android_orm.shtml) - Lightweight ORM Java package for JDBC and Android.
- [ActiveAndroid](http://www.activeandroid.com) - Active record style ORM.
- [Sugar ORM](http://satyan.github.io/sugar/) - Insanely easy way to work with Android Databases.
- [DBFlow](https://github.com/Raizlabs/DBFlow) - Fast and powerful ORM with compile-time annotation processing.
- [NexusData](https://github.com/dkharrat/NexusData) - Object graph and persistence framework for Android.
- [SimpleNoSQL](https://github.com/Jearil/SimpleNoSQL) - A simple NoSQL client for Android. Meant as a document store using key/value pairs and some rudimentary querying. Useful for avoiding the hassle of SQL code.
- [RxSimpleNoSQL](https://github.com/xmartlabs/RxSimpleNoSQL) - Reactive extensions for SimpleNoSQL. Manipulate entities using Observables.

### REST

- [Retrofit](http://square.github.io/retrofit/) - Retrofit turns your REST API into a Java interface.

### Testing

- [Robotium](https://github.com/robotiumtech/robotium) - Test automation framework for black-box UI tests.
- [Roboletric](http://robolectric.org/) - Unit test framework to run tests inside the JVM on your workstation, not in the emulator.
- [AssertJ Android](https://github.com/square/assertj-android) - AssertJ assertions geared towards Android.

### Tracking

- [MobileAppTracking](https://www.tune.com/) - Tracking your marketing campaigns across multiple ad networks.
- [Mixpanel](https://mixpanel.com/) - Analytics platform to analyze the users.
- [Countly](https://count.ly) - Open source mobile & web analytics, push notifications and crash reporting platform, based on Node.js, MongoDB and Linux.
- [CleverTap](https://clevertap.com) - Analytics platform and user-engagment platform with 1 million free events

### Maps

- [Google-Directions-Android](https://github.com/jd-alexander/Google-Directions-Android) - Allows you to calculate the direction between two locations and display the route on a Google Map using the Google Directions API.
- [Android Maps Extensions](https://github.com/mg6maciej/android-maps-extensions) - Extending capabilities of Google Maps Android API v2, adding marker clustering among other things
- [Clusterkraf](https://github.com/twotoasters/clusterkraf) - Clustering library for the Google Maps Android API v2

### Utility

- [EventBus](http://greenrobot.github.io/EventBus/) - EventBus is a library that simplifies communication between different parts of your application.
- [Otto](https://github.com/square/otto) - Event Bus for Android.
- [Weak handler](https://github.com/badoo/android-weak-handler) - Memory safer implementation of android.os.Handler.
- [Byte Buddy](http://bytebuddy.net) - Runtime code generation library with support for Android.
- [Secure Preference Manager](https://prashantsolanki.com/Secure-Pref-Manager/) - Secure Preference Manager for android. It uses various Encryption to protect your application's Shared Preferences.
- [LeakCanary](https://github.com/square/leakcanary) - Catch memory leaks as they occur.
- [Drekkar](https://github.com/coshx/drekkar) - An Android event bus for WebView and JS.
- [Androl4b](https://github.com/sh4hin/Androl4b) - A vm for assessing android applications.
- [DroidMVP](https://github.com/andrzejchm/DroidMVP) - Android library to help you incorporate MVP along with Passive View and Presentation Model patterns into your app.

### Debugging Tools

- [Linx](https://github.com/pedrovgs/Lynx) - Show logcat inside the device for debug builds
- [Scalpel](https://github.com/JakeWharton/scalpel) - View the entire hierarchy in 3d in the phone.
- [Stetho](https://github.com/facebook/stetho) - Debug hierarchy and network from chrome.

### Wireless

- [SmartGattLib](https://github.com/movisens/SmartGattLib) - Simplifies the work with Bluetooth SMART devices (a.k.a. Bluetooth Low Energy in Bluetooth 4.0).

### Chat & Messaging

- [Applozic Android Chat SDK](https://github.com/AppLozic/Applozic-Android-SDK) - Android Chat and Messaging SDK for adding real time chat and in-app messaging into your android application.


### Other

- [Android Support library](https://developer.android.com/topic/libraries/support-library/index.html) - The Android Support Library package is a set of code libraries that provide backward-compatible versions of Android framework API.
- [Google Play Services](https://developers.google.com/android/guides/overview) - Library to access Google services, such as account syncing, Google+ (sharing, single sign-on), Google Maps, Location APIs, Google Play Games, Cloud Messaging, Android Device Manager, and others.
- [Tape](https://github.com/square/tape) - A lightning fast, transactional, file-based FIFO for Android and Java.
- [Guava: Google Core Libraries for Java](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth.
- [Android Scripting](https://github.com/damonkohler/sl4a) - Allows to run scripting languages on Android.
- [Android Priority Job Queue](https://github.com/path/android-priority-jobqueue) - Implementation of a Job Queue to easily schedule jobs (tasks) that run in the background, improving UX and application stability.
- [RateMeMaybe](https://github.com/Kopfgeldjaeger/RateMeMaybe) - Asks the user if (s)he wants to open the Play Store to rate your application.
- [Easy Rating Dialog](https://github.com/fernandodev/easy-rating-dialog) - Lib provides a simple way to display an alert dialog for rating app.
- [ZXing Android-Integration](https://github.com/zxing/zxing) - Integration with Barcode Scanner via Intent.
- [Gradle Retrolambda Plugin](https://github.com/evant/gradle-retrolambda) - Java 8 Lambdas on Android!
- [RxJava](https://github.com/ReactiveX/RxJava)- RxJava – Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM.
- [Caffeine](https://github.com/percolate/caffeine) - A collection of utility classes that help make Android development faster.
- [AboutLibraries](https://github.com/mikepenz/AboutLibraries) - Automatically generates an About this app section, with a list of used libraries.
- [AudioPlayerView](https://github.com/HugoMatilla/AudioPlayerView) - A view that loads audio from an url and have basic playback tools.
- [andle](https://github.com/Jintin/andle) - command line tool help you sync dependencies, sdk or build tool version.
- [Typography](https://github.com/workarounds/typography) - An Android library that makes it easy to use custom fonts in views.
- [transai](https://github.com/Jintin/transai) - command line tool help you manage localization string files.

## Resources

- [Vogella Tutorials](http://www.vogella.com/tutorials/android.html) - Very good tutorials by Lars Vogel.
- [Android Design in Action Video series] (https://www.youtube.com/playlist?list=PLWz5rJ2EKKc8j2B95zGMb8muZvrIy-wcF) The video series by Android Design Team of Google.
- [Android Design in Action slides] (https://play.google.com/store/apps/details?id=com.astuetz.android.adia&feature=md)- The application that gives you access to the slides of the video series.
- [Android DevBytes Video Series] (https://www.youtube.com/playlist?list=PLWz5rJ2EKKc_XOgcRukSoKKjewFJZrKV0) - It is the technical counterpart of Android Design in Action series.
- [Developing for Android](https://medium.com/google-developers/developing-for-android-introduction-5345b451567c) - A series of articles from Googler [Chet Hasae](https://plus.google.com/+ChetHaase/posts/5grfChTEvQ9) and others, answering most commonly asked question: "What are some of the important rules to keep in mind when developing Android applications?".
- [Android Hive Tutorials](http://www.androidhive.info) - Very good tutorials for beginners.
- [Android Weekly](http://androidweekly.net) - Newsletter with weekly information about android.
- [Android Asset Studio](http://romannurik.github.io/AndroidAssetStudio/) - Generator for icons and other assets.
- [Android Action Bar Style Generator](http://jgilfelt.github.io/android-actionbarstylegenerator/).
- [Device Art Generator](https://developer.android.com/distribute/tools/promote/device-art.html) - Wraps app screenshots in real device artwork.
- [Android UI design resources] (https://androiduiux.com/free-design-resources/) - Gives you wide variety of design resources form a Google Developer Expert in UI/UX.
- [Pencil Project] (http://pencil.evolus.vn/) - An open source prototyping software.
- [Google Wear App](https://github.com/mbcrump/FirstGoogleWearableApp) - This is an open source Google Wear App that uses speech recognition to calculate a tip.
- [How to Make Android Apps](https://www.youtube.com/playlist?list=PLGLfVvz_LVvSPjWpLPFEfOCbezi6vATIh) - Video tutorials by Derek Banas.
- [android-blogs](https://github.com/vbauer/android-blogs) - List with blogs about Android.

### More lists of libraries
- [The Android Arsenal](http://android-arsenal.com) - Large list of android libraries
- [DevAppsDirect - Demo Market](https://play.google.com/store/apps/details?id=com.inappsquared.devappsdirect) - App that demonstrates different libraries.
- [Square libraries](http://square.github.io/#android) - Multiple high quality libraries by square.
- [Awesome Android @LibHunt](https://android.libhunt.com) - Your go-to Android Toolbox.

## Development Alternatives

My personal recommendation is (for now) to use the android api to build a native app. Scala can help to build this native apps with cleaner code. But there are also use cases where alternatives like cross-platform development can be useful.

### C&#35;

- [Xamarin](https://www.xamarin.com/) - Framework to create native iOS, Android, Mac and Windows apps in C#.

### HTML, CSS and Javascript

- [PhoneGap](http://phonegap.com) - Open source framework by Adobe to create cross platform mobile apps using HTML, CSS, and JavaScript.
- [Titanium](http://www.appcelerator.com/mobile-app-development-products/) - Open-source framework to create 'native' cross platform apps using JavaScript.
- [NativeScript](https://www.nativescript.org/) - An open-source framework to build native iOS and Android apps with JavaScript from a single code base.
- [React Native](https://github.com/facebook/react-native) - A framework for building native apps with React by Facebook.
- [Ionic Framework](http://ionicframework.com) - A framework to build hybrid apps with mobile-optimized HTML, CSS and JS with AngularJS.
- [Apache Cordova](https://github.com/apache/cordova-android) - Cordova based applications are, at the core, applications written with web technology: HTML, CSS and JavaScript.
- [Reapp.io](http://reapp.io/) - Cordova based framework to build hybrid apps with mobile-optimized HTML, CSS and JS with ReactJS.

### Lua
- [Corona SDK](https://coronalabs.com/corona-sdk/) - Framework to create native iOS and Android Apps (especially Games).

### Scala
- [Scala on Android](http://macroid.github.io/ScalaOnAndroid.html) - Introduction to Scala on Android.
- [Scaloid](https://github.com/pocorall/scaloid) - Library for less painful Android development with Scala.
- [Macroid](https://github.com/47deg/macroid) - A modular functional UI language for Android.

### Groovy
- [Groovy on Android](http://melix.github.io/blog/2014/06/grooid.html) - Introduction to Groovy on Android.
- [Groovy Language Support for Android](https://github.com/groovy/groovy-android-gradle-plugin) - Gradle Plugin for Compiling Groovy for Android.
- [SwissKnife](https://github.com/Arasthel/SwissKnife) - A multi-purpose Groovy library containing view injection and threading for Android using annotations.

### Kotlin
- [Anko](https://github.com/Kotlin/anko) - DSL for Android written in Kotlin by JetBrains.
- [Kotterknife](https://github.com/JakeWharton/kotterknife) - Android view injection writen in Kotlin based on ButterKnife
- [Android Kotlin Samples](https://github.com/irontec/android-kotlin-samples) - Some basic Android code samples writen in Kotlin.
- [KAndroid](https://github.com/pawegio/KAndroid) - Lightweight library providing useful extensions to eliminate boilerplate code in Android SDK.
- [RxKotlin/Pocket](https://github.com/RxKotlin/Pocket) - This app help user to save links easily, and can export to Evernote as weekly.

# Performance
- [awesome-android-performance](https://github.com/Juude/awesome-android-performance) - A list of awesome Android tutorials, videos and tools for performance optimization.

# Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.
