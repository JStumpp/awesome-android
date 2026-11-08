# Awesome Android [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/jstumpp/awesome-android/main/awesome-android.png">](https://github.com/jstumpp/awesome-android)

<p align="center">
  <a href="https://github.com/sindresorhus/awesome"><img alt="awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" /></a>
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
	- [Charts](#charts)
	- [Data binding](#data-binding)
	- [Dependency Injection](#dependency-injection)
	- [Android Services](#android-services)
	- [Game Development](#game-development)
	- [Security](#security)
	- [GUI](#gui)
	- [JSON](#json)
	- [Crash monitoring](#crash-monitoring)
	- [Networking](#networking)
	- [Logger](#logger)
	- [Notifications](#notifications)
	- [Database](#database)
	- [REST](#rest)
	- [Testing](#testing)
	- [Tracking](#tracking)
	- [Maps](#maps)
	- [Utility](#utility)
	- [Debugging Tools](#debugging-tools)
	- [Wireless](#wireless)
	- [Chat & Messaging](#chat--messaging)
	- [Version Checking](#version-checking)
	- [Date & Time](#date--time)
	- [Runtime Permissions](#runtime-permissions)
	- [Payments](#payments)
	- [Other](#other)
- [Resources](#resources)
- [Development Alternatives](#development-alternatives)
	- [C#](#c)
	- [HTML, CSS and JavaScript](#html-css-and-javascript)
	- [Lua](#lua)
	- [Python](#python)
	- [Scala](#scala)
	- [Groovy](#groovy)
	- [Kotlin](#kotlin)
	- [Flutter](#flutter)
- [Performance](#performance)
- [Shrinking](#shrinking)
- [Other Awesome Lists](#other-awesome-lists)

## Emulators
- [ARChon](https://archon-runtime.github.io)
- [BlueStacks](https://www.bluestacks.com)
- [Genymotion](https://www.genymotion.com)
- [nox](https://www.bignox.com)

## Libraries

### Charts

- [AChartEngine](https://github.com/ddanny/achartengine) - Charting Engine.
- [EazeGraph](https://github.com/blackfizz/EazeGraph) - Chart and graph library.
- [WilliamChart](https://github.com/diogobernardino/williamchart) - Chart library with good motion capabilities.
- [HelloCharts](https://github.com/lecho/hellocharts-android) - Chart and graph library with support for scaling, scrolling and animations.
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) - An Android chart and graph library supporting scaling and dragging by gesture.
- [ArcChartView](https://github.com/imaNNeoFighT/ArcChartView) - Draw Creative Statistic Arc Charts.
- [AnyChart](https://github.com/AnyChart/AnyChart-Android) - Data visualization library, Interactive charts.

### Data binding

- [Anvil](https://github.com/anvil-ui/anvil) - A small library to create reactive UI components, inspired by React. Provides data binding and event listener binding, fits well for MVVM.
- [Data Binding Library](https://developer.android.com/topic/libraries/data-binding/) - Official Android Data Binding Library to write declarative layouts and minimize the glue code necessary to bind application logic and layouts.

### Dependency Injection

- [Dagger 2](https://github.com/google/dagger) - A fast dependency injector for Android and Java.
- [ActivityStarter](https://github.com/MarcinMoskala/ActivityStarter) - Android Library that provide simpler way to start the Activities with multiple arguments.
- [Toothpick](https://github.com/stephanenicolas/toothpick) - A scope tree based Dependency Injection (DI) library for Java.

### Android Services
- [Remoter](https://github.com/josesamuel/remoter) - An alternative to Android AIDL for Android Remote IPC services using plain java interfaces.
- [Service Connector](https://github.com/josesamuel/serviceconnector) - Bind Android services and callbacks to fields and methods.

### Game Development

- [Libgdx](https://libgdx.com/) - Cross-platform game engine and SDK. [Open Source](https://github.com/libgdx/libgdx)
- [Vuforia](https://www.vuforia.com/) - Augmented Reality library.
- [Unity](https://unity3d.com/unity/features/multiplatform) - Cross-platform game creation system.
- [Rajawali](https://github.com/Rajawali/Rajawali) - Android OpenGL ES 2.0/3.0 Engine.
- [Cocos2d-x](https://cocos2d-x.org/) - Cross-platform 2d game framework.
- [JustWeEngine](https://github.com/lfkdsk/JustWeEngine) - An easy open source Android Native Game FrameWork.
- [Godot](https://github.com/godotengine/godot) - Cross-platform 2/3D game engine with an IDE and under MIT license.

### Security

- [Themis](https://github.com/cossacklabs/themis) - Multi-language framework for making typical encryption schemes easy to use: data at rest, authenticated data exchange, transport protection, authentication, and so on.

### GUI

- [Pull to refresh](https://developer.android.com/reference/androidx/swiperefreshlayout/widget/SwipeRefreshLayout) - A swipe refresh layout is available in AndroidX.
- [Cardslib](https://github.com/gabrielemariotti/cardslib) - Android Library to build a UI Card.
- [SortableTableView](https://github.com/ISchwarz23/SortableTableView) - An Android library containing a simple TableView and an advanced SortableTableView providing a lot of customisation possibilities to fit all needs.
- [MaterialProgressBar](https://github.com/zhanghai/MaterialProgressBar) - Material design ProgressBar with consistent appearance.
- [AndroidFillableLoaders](https://github.com/JorgeCastilloPrz/AndroidFillableLoaders) - Fillable progress view working with SVG paths. Nice option too for creating interesting app logos.
- [NexusDialog](https://github.com/dkharrat/NexusDialog) - Allows you to easily and quickly create forms in Android with little code.
- [Snap RecyclerView Utils](https://github.com/prashantsolanki3/Snap-RecyclerView-Utils) - Populate Single or multiple Layout RecyclerView without creating an Adapter.
- [MultiSnapRecyclerView](https://github.com/TakuSemba/MultiSnapRecyclerView) - Android library for multiple snapping of RecyclerView.
- [SwipeableCard](https://github.com/michelelacorte/SwipeableCard) - Implementation of swipe card like StreetView.
- [ElasticProgressBar](https://github.com/michelelacorte/ElasticProgressBar) - Beautiful loading bar.
- [EntryScreenManager](https://github.com/kunall17/EntryScreenManager) - Intro/Entry/Walkthrough/Starting Screens.
- [Material-Calendar-View](https://github.com/BlackBoxVision/material-calendar-view) - Material Design Calendar compatible with API 8+.
- [CrunchyCalendar](https://github.com/CleverPumpkin/CrunchyCalendar) - A material calendar widget with infinite scrolling, date range selection and color customization.
- [SmoothOverscrollableScrollView](https://github.com/vovaksenov99/OverscrollableScrollView) - Small custom view with smooth overscroll. You can add header with scale background.
- [DragListView](https://github.com/woxblom/DragListView) - Drag and drop to reorder items in a list, grid or board.
- [TastyToast](https://github.com/yadav-rahul/TastyToast) - Toasts with icons and color.
- [DotLoader](https://github.com/bhargavms/DotLoader) - A customizable loading animation with Dots.
- [PodSlider](https://github.com/bhargavms/PodSLider) - A customizable slider widget adhering to material design specs.
- [TapTargetView](https://github.com/KeepSafe/TapTargetView) - An implementation of tap targets from the Material Design guidelines for feature discovery.
- [MaterialIntroScreen](https://github.com/TangoAgency/material-intro-screen) - Material Intro Screen implementation with easily extensible API.
- [FloatingView](https://github.com/UFreedom/FloatingView) - Can make the target view floating above the anchor view with cool animation.
- [Bubbles for Android](https://github.com/txusballesteros/bubbles-for-android) - Facebook like chat bubble library.
- [Litho (By Facebook)](https://github.com/facebook/litho) - A declarative framework for building efficient UIs on Android.
- [LGSnackbar](https://github.com/loregr/LGSnackbar) - An easy to use and customisable wrapper of the native Android Snackbar which stays visible across multiple activities.
- [ShimmerLayout](https://github.com/team-supercharge/ShimmerLayout) - Memory efficient shimmering effect for Android applications.
- [CircleProgressBar](https://github.com/emre1512/CircleProgressBar) - A simple library for creating circular progressbars for Android.
- [Easy-Signature-Android](https://github.com/smalam119/Easy-Signature-Android) - An simple ui library that provides a plugable signature view.
- [Flashbar](https://github.com/aritraroy/Flashbar) - A highly customizable, powerful and easy-to-use alerting library for Android.
- [YuanaItemSettingView](https://github.com/andhikayuana/YuanaItemSettingView) - Customizable Item Setting View for Android.
- [Gradients](https://github.com/bakhtiyork/gradients) - A curated collection of splendid gradients.
- [Liquid-Glass-Android](https://github.com/QWEA0/Liquid-Glass-Android) - Liquid glass effect for the Android View system.
- [OneAdapter](https://github.com/ironSource/OneAdapter) - RecyclerView Adapter with multiple modules and hooks to simplify and enhance the use while preventing common mistakes.

#### ActionBar
- [FadingActionBar](https://github.com/ManuelPeinado/FadingActionBar) - Fading action bar effect that can be seen in the new Play Music app.

#### Navigation
- [SlidingMenu](https://github.com/jfeinstein10/SlidingMenu) - Library to create applications with slide-in menus.
- [SlidingTutorial](https://github.com/Cleveroad/SlidingTutorial-Android) - Simple library that helps to create awesome sliding Android app tutorials.
- [PagerSlidingTabStrip](https://github.com/astuetz/PagerSlidingTabStrip) - An interactive indicator to navigate between the different pages of a ViewPager.
- [RecyclerTabLayout](https://github.com/nshmura/RecyclerTabLayout) - An efficient TabLayout library implemented with RecyclerView.
- [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer) - Simple take on a material design navigation drawer.
- [Floating-Navigation-View](https://github.com/andremion/Floating-Navigation-View) - A simple Floating Action Button that shows an anchored Navigation View.

#### Animations
- [SmoothMotion](https://github.com/abdullahalhakimi/SmoothMotion) - Kotlin library for simplifying animations and transitions in Jetpack Compose.
- [Rebound](https://github.com/facebook/rebound) - Java library that models spring dynamics.
- [Android View Animations](https://github.com/daimajia/AndroidViewAnimations) - Cute view animation collection.
- [Android-Transition](https://github.com/kaichunlin/android-transition) - Allows the easy creation of view transitions that react to user inputs.
- [Android-View-Actions](https://github.com/dtx12/AndroidAnimationsActions) - Makes creating complex animations for views easy.
- [Swipper](https://github.com/mdg-iitr/Swipper) - Android library for swipeable gestures to control volume , brightness and seek .
- [Spotlight](https://github.com/TakuSemba/Spotlight) - Android Library that lights items for tutorials or walk-throughs etc...

#### Images

- [Crescento](https://github.com/developer-shivam/Crescento) - Explore new style in material design by adding curve below image view.
- [CircularImageView](https://github.com/Pkmmte/CircularImageView) - Custom view for circular images while maintaining the best draw performance.
- [Android-Image-Filter](https://github.com/ragnraok/android-image-filter) - Library project for applying image filters easily.
- [Compressor](https://github.com/zetbaitsu/Compressor) - Lightweight and powerful Android image compression library.
- [ShapeImageView](https://github.com/siyamed/android-shape-imageview) - Library to display images in different shapes.

#### Inputs

- [FloatingLabel](https://github.com/hardik-trivedi/FloatingLabel) - Allows you to create a blow kind of EditText. *Doesn't have Gradle or Maven Support.*
- [MaterialSearchBar](https://github.com/mancj/MaterialSearchBar) - Material Design Search Bar for Android.
- [InputMask](https://github.com/RedMadRobot/input-mask-android) - Pattern-based user input formatter, parser and validator.
- [SweetPassword](https://github.com/jesusmartinoza/Sweet-Password) - Password EditText that allows to custom toggle button.
- [VoiceOverlay](https://github.com/algolia/voice-overlay-android) - An overlay that gets your user’s voice permission and input as text in a customizable UI.

#### View Pagers
- [Material Dots Indicators](https://github.com/tommybuonomo/dotsindicator) - Three Material Dots Indicators styles for View Pagers.

#### Loading Images

- [Glide](https://github.com/bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling, Recommended by Google.
- [Fresco](https://github.com/facebook/fresco) - An Android library for managing images and the memory they use.
- [Glide Bitmap Pool](https://github.com/amitshekhariitbhu/GlideBitmapPool) - Memory management library for reusing the bitmap memory.
- [Coil](https://github.com/coil-kt/coil) - Image loading for Android backed by Kotlin Coroutines.

#### Video

- [ijkplayer](https://github.com/bilibili/ijkplayer) - Android/iOS video player based on FFmpeg n3.2, with MediaCodec, VideoToolbox support.
- [Media3 (ExoPlayer)](https://github.com/androidx/media) - Jetpack Media3 support libraries for media use cases, including ExoPlayer, an extensible media player for Android.
- [VideoPlayView](https://github.com/MarcinMoskala/VideoPlayView) - Custom Android view with video player, play/stop, loader and placeholder image.

#### Camera

- [MagicalCamera](https://github.com/fabian7593/MagicalCamera) - Simple way to take or select photos of your gallery, with other features for manage pictures.
- [Camera](https://github.com/duanhong169/Camera) - Use Android camera to take pictures and videos, based on camera2 api.

#### Field Validation
- [Convalida](https://github.com/wellingtoncosta/convalida) - A simple and annotation-based way to validate your input fields.

### JSON

- [Gson](https://github.com/google/gson) - Java library used for serializing and deserializing Java objects from and into JSON.
- [Jackson JSON Processor](https://github.com/FasterXML/jackson) - High-performance JSON processor.
- [Moshi](https://github.com/square/moshi) - A modern JSON library for Android and Java.
### Crash monitoring

- [Bugsnag](https://www.bugsnag.com/) - Cross platform error monitoring. Free tier. Support for SDK & NDK. Error reports include data on device, release, user, and allows arbitrary data.
- [Catcho](https://github.com/alhazmy13/Catcho) - No Force Close any more.
- [Luciq](https://www.luciq.ai/) - Bug reporting, Crash Reporting, In-app Feedback (formerly Instabug).
- [Firebase Crashlytics](https://firebase.google.com/products/crashlytics) - Easy crash reporting solution. *Commercial (has free tier)*
- [Measure](https://github.com/measure-sh/measure/) - Open source tool to monitor crashes, ANRs, and performance of mobile apps. Can be self-hosted.

### Networking

- [Ion](https://github.com/koush/ion) - Good networking library for Android.
- [OkHttp](https://github.com/square/okhttp) - An HTTP+SPDY client for Android and Java applications.
- [IceNet](https://github.com/anton46/IceNet) - Fast, Simple and Easy Networking for Android.
- [Android Volley](https://developer.android.com/training/volley/) - Official Android HTTP library that makes networking for easier and faster.
- [IceSoap](https://github.com/AlexGilleran/IceSoap) - Easy, asynchronous, annotation-based SOAP for Android.
- [node-android](https://github.com/InstantWebP2P/node-android) - Run Node.js on Android.
- [HappyDns](https://github.com/qiniu/happy-dns-android) - A Dns library, user can use custom dns server, dnspod httpdns. Only support A record.
- [RESTMock](https://github.com/andrzejchm/RESTMock) - HTTP Web server for mocking API responses in Android Instrumentation tests.
- [Fast-Android-Networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking) - A Complete Fast Android Networking Library that also support HTTP/2.

### Logger
- [logger](https://github.com/orhanobut/logger) - Simple, pretty and powerful logger for Android.
- [timber](https://github.com/JakeWharton/timber) - A logger with a small, extensible API which provides utility on top of Android's normal Log class.
- [LoggingInterceptor](https://github.com/ihsanbal/LoggingInterceptor) - An OkHttp interceptor which pretty logs request and response data.
- [Bugfender](https://github.com/bugfender/BugfenderSDK-android-sample) - Upload your logs and check them online, specially made for mobile.
- [EzyLogger](https://github.com/afiqiqmal/EzyLogger) - Simple Lightweight logger.
- [Logback Android](https://github.com/tony19/logback-android) - Logback port to Android which provides a highly configurable logging framework for Android apps.
- [LogDog](https://log.dog) - Remote debugging/logging sdk (iOS and Android) with a web ui. Captures all logs and requests in real-time and allows to intercept them. 

### Notifications
- [android-remote-notifications](https://github.com/kaiwinter/android-remote-notifications) - Pulls notifications from a remote JSON file and shows them in your app.
- [Android HeartBeat Fixer](https://github.com/joaopedronardari/AndroidHeartBeatFixer) - Way to set heartbeat interval and users receive PushNotifications from GCM.

### Database
- [DbInspector](https://github.com/infinum/android_dbinspector) - Provides a simple way to view the contents of the in-app database for debugging purposes.
- [SQLite Asset Helper](https://github.com/jgilfelt/android-sqlite-asset-helper) - Manage database creation and version management using an application's raw asset files.
- [Realm](https://github.com/realm/realm-java) - The alternative to SQLite and ORMs: Simple, modern and fast! Object oriented API and multi platform support.
- [RestorableSQLiteDatabase](https://github.com/yaa110/RestorableSQLiteDatabase) - A wrapper to replicate Android's SQLiteDatabase with restoring capability.
- [Nitrite Database](https://github.com/dizitart/nitrite-database) - A NoSQL embedded document store for Android with MongoDB like API.

#### ORM

- [ObjectBox](https://github.com/objectbox/objectbox-java) - Simple but powerful object database, optimized for performance & mobile.
- [requery](https://github.com/requery/requery) - Compile time ORM and SQL query library for Java & Android.
- [GreenDAO](https://greenrobot.org/greendao/) - Light & fast ORM solution.
- [ORMLite](https://ormlite.com/sqlite_java_android_orm.shtml) - Lightweight ORM Java package for JDBC and Android.
- [DBFlow](https://github.com/agrosner/DBFlow) - Fast and powerful ORM with compile-time annotation processing.
- [NexusData](https://github.com/dkharrat/NexusData) - Object graph and persistence framework for Android.
- [SimpleNoSQL](https://github.com/Jearil/SimpleNoSQL) - A simple NoSQL client for Android. Meant as a document store using key/value pairs and some rudimentary querying. Useful for avoiding the hassle of SQL code.

### REST

- [Retrofit](https://square.github.io/retrofit/) - Turns your REST API into a Java interface.
- [Spring for Android - Rest Template](https://github.com/spring-projects/spring-android) - A Rest Client for Android.

### Testing

- [Robotium](https://github.com/RobotiumTech/robotium) - Test automation framework for black-box UI tests.
- [Roboletric](https://robolectric.org/) - Unit test framework to run tests inside the JVM on your workstation, not in the emulator.
- [Ghost in the Droid](https://github.com/ghost-in-the-droid/android-agent) - Python MCP server for AI agent control of Android and iOS devices via ADB and WebDriverAgent.
- [Green Coffee](https://github.com/mauriciotogneri/green-coffee) - Run your Cucumber tests in your Android instrumentation tests.
- [Droidline](https://github.com/KnifeLemon/Droidline) - Automate real Android phones from Python, Node.js, C# or a CLI over Wi-Fi, without ADB or root.

### Tracking

- [MobileAppTracking](https://www.tune.com/) - Tracking your marketing campaigns across multiple ad networks.
- [Mixpanel](https://mixpanel.com/) - Analytics platform to analyze the users.
- [Countly](https://count.ly) - Open source mobile & web analytics, push notifications and crash reporting platform, based on Node.js, MongoDB and Linux.
- [CleverTap](https://clevertap.com) - Analytics platform and user-engagement platform with 1 million free events.

### Maps

- [Google-Directions-Android](https://github.com/jd-alexander/Google-Directions-Android) - Allows you to calculate the direction between two locations and display the route on a Google Map using the Google Directions API.
- [Android Maps Extensions](https://github.com/mg6maciej/android-maps-extensions) - Extending capabilities of Google Maps Android API v2, adding marker clustering among other things.
- [MapScaleView](https://github.com/pengrad/MapScaleView) - Scale bar for Google Maps Android API.
- [GLMap](https://globus.software) - Crossplatform offline vector map with MapCSS styling. Offline search and offline navigation are included.

### Utility
- [Conceal SharedPreferences](https://github.com/afiqiqmal/SharedChamber) - Secured Preferences using Facebook Secure Encryption called Conceal.
- [EventBus](https://greenrobot.github.io/EventBus/) - Library that simplifies communication between different parts of your application.
- [Weak handler](https://github.com/badoo/android-weak-handler) - Memory safer implementation of android.os.Handler.
- [Byte Buddy](https://bytebuddy.net) - Runtime code generation library with support for Android.
- [Secure Preference Manager](https://github.com/prashantsolanki3/Secure-Pref-Manager) - Uses various Encryption to protect your application's Shared Preferences.
- [LeakCanary](https://github.com/square/leakcanary) - Catch memory leaks as they occur.
- [Drekkar](https://github.com/coshx/drekkar) - An Android event bus for WebView and JS.
- [Androl4b](https://github.com/sh4hin/Androl4b) - A vm for assessing Android applications.
- [DroidMVP](https://github.com/andrzejchm/DroidMVP) - Android library to help you incorporate MVP along with Passive View and Presentation Model patterns into your app.
- [EasyDeviceInfo](https://github.com/nisrulz/easydeviceinfo) - Get device information in a super easy way.
- [Shutter-Android](https://github.com/levibostian/Shutter-Android) - Capture photos/videos from device camera or get photos/video from gallery app with no runtime permissions needed.
- [Validator](https://github.com/anderscheow/Validator) - An utilities class to validate text inside TextInputLayout.
- [Keyboard Visibility Event](https://github.com/viniciusmo/keyboard-visibility-event-android/) - A DSL to handle soft keyboard visibility change event.
- [Reactor](https://github.com/oky2abbas/reactor) - Fast and secure key-value library for Android.
 
### Debugging Tools

- [Linx](https://github.com/pedrovgs/Lynx) - Show logcat inside the device for debug builds.
- [Chucker](https://github.com/ChuckerTeam/chucker) - An HTTP inspector for Android & OkHTTP (like Charles but on device).
- [Android Debug Database](https://github.com/amitshekhariitbhu/Android-Debug-Database) - Powerful library for debugging databases and shared preferences in Android applications.
- [Android Debug Bridge - ADB](https://github.com/mzlogin/awesome-adb/blob/master/README.en.md) - A command-line tool to assist in debugging Android-powered devices.
- [ADB Enhanced](https://github.com/ashishb/adb-enhanced) - A command-line wrapper around ADB for developers, so that, developers don't have to remember esoteric version-dependent commands.
- [handsets](https://github.com/elliotgao2/handsets) - Android control CLI that drives devices over ADB with no APK required.
- [Pidcat](https://github.com/JakeWharton/pidcat) - A colored command-line ADB wrapper that only shows log entries for a specific application package.
- [AppSpector](https://appspector.com) - Remote Android and iOS debugging and data collection service. You can debug networking, logs, SQLite and mock device's geo location.


### Wireless

- [SmartGattLib](https://github.com/movisens/SmartGattLib) - Simplifies the work with Bluetooth SMART devices (a.k.a. Bluetooth Low Energy in Bluetooth 4.0).

### Chat & Messaging

- [Qiscus SDK](https://github.com/qiscus/qiscus-sdk-android) - Lightweight and powerful Android chat library. Allows you to easily integrating Qiscus engine with your apps to make cool chatting application.
- [Kommunicate Live Chat SDK](https://github.com/Kommunicate-io/Kommunicate-Android-Chat-SDK) - Kommunicate provides open source live chat sdk in Android. Kommunicate lets you add real time live chat and in-app messaging in your mobile (Android, iOS) applications and website for customer support.
- [CometChat Voice, Video and Text Chat SDK with UI](https://github.com/cometchat-go/android-chat-sdk-demo) - Add voice, video and text chat to your app (and website) in minutes using CometChat. CometChat's SDK includes a complete ready UI so that you don't have to spend any time building one! That's not all, CometChat has out-of-the-box support for real-time translation, whiteboards, screen sharing, friends sync, role based access control, credits deduction and more.
- [Build a one-on-one Android chat app using Kotlin](https://www.cometchat.com/tutorials/build-one-on-one-chat-in-your-android-app-using-kotlin/) - Build a one-one-one Android chat app in Kotlin within few minutes using CometChat Pro. This tutorial discusses the features such as login, getting list of contacts, user presence indicators, sending/receiving messages etc.
- [Stream Chat](https://getstream.io/tutorials/android-chat/) - Comprehensive SDK & Components for real-time chat, powered by [Stream](https://getstream.io/chat/).
- [Add Push Notifications to Your Android Chat App Using Kotlin](https://www.cometchat.com/tutorials/android-chat-push-notifications/) - Add push notifications in your Android chat apps in Kotlin with the help of CometChat Pro and Firebase Cloud Messaging (FCM).

#### Custom Dialog

- [MediaRecorderDialog](https://github.com/alhazmy13/MediaRecorderDialog) - Custom Dialog to record audio, store it and play it in your phone.
- [HijriDatePicker](https://github.com/alhazmy13/HijriDatePicker) - Offers a hijri (Islamic Calendar) Date Picker designed on Google's Material Design Principals For Pickers.
- [Noty](https://github.com/emre1512/Noty) - A simple library for creating animated alerts/dialogs/warnings.

### Version Checking

- [AppUpdater](https://github.com/javiersantos/AppUpdater) - Comprehensive and feature rich library, including support for checks at Amazon and FDroid.
- [Gandalf](https://github.com/btkelly/gandalf) - Comprehensive features and a "companion" iOS solution.
- [Siren](https://github.com/eggheadgames/Siren) - Focused feature set that mimicks the popular iOS library of the same name. Supports Play and Amazon.
- [Fit](https://github.com/KeithYokoma/Fit) - Version checking callback framework with no UI.

### Date & Time

- [kotlinx-datetime](https://github.com/Kotlin/kotlinx-datetime) - A multiplatform Kotlin library for working with date and time.
- [Joda-Time Android](https://github.com/dlew/joda-time-android) - Joda-Time library with Android specialization.
- [True Time](https://github.com/instacart/truetime-android) - Android NTP time library. Get the true current time impervious to device clock time changes.

### Runtime Permissions

- [Permission Dispatcher](https://github.com/permissions-dispatcher/PermissionsDispatcher) - Simple annotation-based API to handle runtime permissions.
- [Ask-Permission](https://github.com/Kishanjvaghela/Ask-Permission) - Simple RunTime permission manager.
- [Gota](https://github.com/alhazmy13/Gota) - Simplifying Android Permissions.

### Payments

- [Square In-App Payments for Android](https://developer.squareup.com/docs/in-app-payments-sdk/build-on-android) - Integrate Square payments into your mobile app with Digital wallet and stored card support for quick checkout.

### Other

- [Licensee](https://github.com/cashapp/licensee) - Gradle plugin which validates the licenses of your dependency graph match what you expect, or it fails your build!
- [AndroidX](https://developer.android.com/jetpack/androidx) - The modern Android development toolkit that replaces the Android Support Library, providing backward-compatible versions of Android framework APIs.
- [Google Play Services](https://developers.google.com/android/guides/overview) - Library to access Google services, such as account syncing, Google+ (sharing, single sign-on), Google Maps, Location APIs, Google Play Games, Cloud Messaging, Android Device Manager, and others.
- [Guava: Google Core Libraries for Java](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth.
- [Android Priority Job Queue](https://github.com/yigit/android-priority-jobqueue) - Implementation of a Job Queue to easily schedule jobs (tasks) that run in the background, improving UX and application stability.
- [Easy Rating Dialog](https://github.com/fernandodev/easy-rating-dialog) - Lib provides a simple way to display an alert dialog for rating app.
- [ZXing Android-Integration](https://github.com/zxing/zxing) - Integration with Barcode Scanner via Intent.
- [Gradle Retrolambda Plugin](https://github.com/evant/gradle-retrolambda) - Java 8 Lambdas on Android!
- [RxJava](https://github.com/ReactiveX/RxJava) - Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM.
- [RxAndroid](https://github.com/ReactiveX/RxAndroid) - Adds minimum RxJava bindings for easy writing of reactive Android java code.
- [Caffeine](https://github.com/percolate/caffeine) - A collection of utility classes that help make Android development faster.
- [AboutLibraries](https://github.com/mikepenz/AboutLibraries) - Automatically generates an About this app section, with a list of used libraries.
- [AudioPlayerView](https://github.com/HugoMatilla/AudioPlayerView) - A view that loads audio from an url and have basic playback tools.
- [andle](https://github.com/Jintin/andle) - Command line tool help you sync dependencies, sdk or build tool version.
- [Typography](https://github.com/workarounds/typography) - An Android library that makes it easy to use custom fonts in views.
- [transai](https://github.com/Jintin/transai) - Command line tool help you manage localization string files.
- [Sensey](https://github.com/nisrulz/sensey) - Detecting gestures in a snap.
- [UserAwareVideoView](https://github.com/kevalpatel2106/UserAwareVideoView) - A customized video view that will automatically pause video is user is not looking at device screen.
- [Agile Boiler Plate](https://github.com/xresco/Android-Agile-Boiler-Plate) - The boiler plate is based on MVP architecture and it is fully based on Dependency Injection design pattern using Dagger2.
- [Gradle buildSrcVersions](https://github.com/jmfayard/buildSrcVersions) - A Kotlin dsl to simplify dependencies management.
- [Teller](https://github.com/levibostian/Teller-Android/) - Facilitates the downloading, saving, and reading of the cached data of your app. Keep your user's data fresh and remove those annoying loading screens!

## Resources

- [Programming Community Curated Resources for Learning Android Development](https://hackr.io/tutorials/learn-android-development) - Android Tutorials & Courses submitted and voted by the programming community.
- [Vogella Tutorials](https://www.vogella.com/tutorials/android.html) - Very good tutorials by Lars Vogel.
- [Android API Levels](https://apilevels.com/) - A quick reference table of Android versions with SDK & API levels, version codes, codenames, cumulative usage, and more.
- [Android Design in Action Video series](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc8j2B95zGMb8muZvrIy-wcF) - The video series by Android Design Team of Google.
- [Android DevBytes Video Series](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc_XOgcRukSoKKjewFJZrKV0) - It is the technical counterpart of Android Design in Action series.
- [Developing for Android](https://medium.com/google-developers/developing-for-android-introduction-5345b451567c) - A series of articles from Googler Chet Hasae and others, answering most commonly asked question: "What are some of the important rules to keep in mind when developing Android applications?"
- [Android Hive Tutorials](https://www.androidhive.info) - Very good tutorials for beginners.
- [Android Weekly](https://androidweekly.net) - Newsletter with weekly information about Android.
- [Android Asset Studio](https://romannurik.github.io/AndroidAssetStudio/) - Generator for icons and other assets.
- [Android Action Bar Style Generator](https://jgilfelt.github.io/android-actionbarstylegenerator/) - Customize the look of the Android Action Bar.
- [Device Art Generator](https://developer.android.com/distribute/marketing-tools/device-art-generator) - Wraps app screenshots in real device artwork.
- [Pencil Project](https://pencil.evolus.vn/) - An open source prototyping software.
- [How to Make Android Apps](https://www.youtube.com/playlist?list=PLGLfVvz_LVvSPjWpLPFEfOCbezi6vATIh) - Video tutorials by Derek Banas.
- [android-blogs](https://github.com/vbauer/android-blogs) - List with blogs about Android.
- [Future Studio](https://futurestud.io/tutorials/tag/android) - Extensive Android tutorials on Retrofit, Glide & Gson.
- [Android Tips & Tricks](https://github.com/nisrulz/android-tips-tricks) - Cheatsheet about tips and tricks for Android Development.
- [Associate Android Developer Certification Materials](https://github.com/Amejia481/Associate-Android-Developer-Certification) - A collection of materials for getting ready for the test.
- [Google Developers Training](https://developer.android.com/courses/) -  Google Developers Official Training page has list of various useful learning resources for beginner as well seasoned developer.
- [Mindorks](https://mindorks.com/) - Become a complete and happy Android developer.
- [AndroidVille](https://ayusch.com/) - Become a better Android Engineer. A website dedicated to Android Development covering advanced topics such as RxJava, Android Zygote and much more.
- [Android Stack Weekly](https://blog.canopas.com/tagged/canopas-android-weekly) - A weekly newsletter on new development and updates of Android universe.
- [Roadmap.sh Android Roadmap](https://roadmap.sh/android) - Community-created Android developer roadmap.

### Code examples
- [Android Architecture Blueprints](https://github.com/android/architecture-samples) - The Android Architecture Blueprints project demonstrates strategies to help solve or avoid common Android problems.
- [Kotlin MVVM example](https://github.com/emedinaa/kotlin-mvvm) - Example about MVVM (Model View ViewModel) Pattern.
- [Kotlin VIPER example](https://github.com/OmiSoftNet/AndroidViperTemplate) - Example about VIPER (View Interactor Presenter Entity Router) Pattern.
- [Complete-Google-Map-API-Tutorial](https://github.com/mohammadima3oud/Complete-Google-Map-API-Tutorial) - Learn How to use Google Map API for Android from Basic to Advance with complete examples.
- [Android Modular Architecture](https://github.com/VMadalin/kotlin-sample-app) - Android Sample App using modular, clean, scalable, testable Architecture written in Kotlin following the best practices with Jetpack.

### Podcasts
- [Fragmented](https://fragmentedpodcast.com/) - Is the Android developer podcast where Donn Felker and Kaushik Gopal talk about building good software and becoming better Android developers.
- [Android Developers Backstage](https://androidbackstage.blogspot.com/) - Is a podcast by and for Android developers. Hosted by developers from the Android engineering team, this show covers topics of interest to Android programmers, with in-depth discussions and interviews with engineers on the Android team at Google.
- [Android Dialogs](https://www.youtube.com/channel/UCMEmNnHT69aZuaOrE-dF6ug/feed) - Is a video based podcast, where they have bite-sized conversations with people from the Android community.
- [The Context](https://github.com/artem-zinnatullin/TheContext-Podcast) - A podcast about Android Development with Hannes Dorfmann, Artem Zinnatullin and wonderful guests!
- [Talking Kotlin](https://talkingkotlin.com/) - A Podcast on Kotlin and more.
- [Android Authority](https://www.androidauthority.com/podcast/) - Is a weekly Android podcast hosted by Adam Doud, Joe Hindy, and Jonathan Feist from the Android Authority team.
- [Android Central](https://www.androidcentral.com/podcast) - Is a weekly Android podcast hosted by the Android Central team.

### More lists of libraries
- [Square libraries](https://square.github.io/) - Multiple high quality libraries by square.
- [Awesome Android @LibHunt](https://android.libhunt.com) - Your go-to Android Toolbox.
- [Android Store](https://mindorks.com/android/store) - Search Android Libraries, Projects, and Tools.

## Development Alternatives

My personal recommendation is (for now) to use the Android SDK to build a native app. Scala and Kotlin are both options; multidex requirements depend on an app's method-reference count and minimum SDK level, not its language. Cross-platform alternatives can also be useful when they fit a project's requirements.

### C&#35;

- [.NET MAUI](https://github.com/dotnet/maui) - .NET Multi-platform App UI, the evolution of Xamarin.Forms, for building native cross-platform apps with .NET and C#.

### HTML, CSS and JavaScript

- [NativeScript](https://www.nativescript.org/) - An open-source framework to build native iOS and Android apps with JavaScript from a single code base.
- [React Native](https://github.com/facebook/react-native) - A framework for building native apps with React by Facebook.
- [Ionic Framework](https://ionicframework.com) - A framework to build hybrid apps with mobile-optimized HTML, CSS and JS with AngularJS.
- [Apache Cordova](https://github.com/apache/cordova-android) - Cordova based applications are, at the core, applications written with web technology: HTML, CSS and JavaScript.
- [Capacitor](https://github.com/ionic-team/capacitor) - Build cross-platform Native Progressive Web Apps for iOS, Android, and the web. Very promising Cordova alternative. 

### Lua
- [Solar2D](https://github.com/coronalabs/corona) - Cross-platform framework for creating 2D games and apps (formerly Corona SDK).

### Python
- [BeeWare](https://github.com/beeware/toga) - Write native Android apps in Python using Toga and Briefcase.
- [Flet](https://github.com/flet-dev/flet) - Build Flutter apps using Python.
- [Kivy](https://github.com/kivy/kivy) - Open source Python framework for Android apps, packaged with Buildozer.

### Scala
- [Scaloid](https://github.com/pocorall/scaloid) - Library for less painful Android development with Scala.
- [Macroid](https://github.com/47deg/macroid) - A modular functional UI language for Android.

### Groovy
- [Groovy on Android](https://melix.github.io/blog/2014/06/grooid.html) - Introduction to Groovy on Android.
- [SwissKnife](https://github.com/Arasthel/SwissKnife) - A multi-purpose Groovy library containing view injection and threading for Android using annotations.

### Kotlin
- [Android Kotlin Samples](https://github.com/irontec/android-kotlin-samples) - Some basic Android code samples written in Kotlin.
- [Kotlin coding puzzles](https://github.com/igorwojda/kotlin-coding-puzzle) - Set of programming challenges thats helps to improve whiteboard coding and problem-solving skills.
- [KAndroid](https://github.com/pawegio/KAndroid) - Lightweight library providing useful extensions to eliminate boilerplate code in Android SDK.
- [KuiklyUI](https://github.com/Tencent-TDS/KuiklyUI) - Kotlin Multiplatform UI framework supporting Android, iOS, and other platforms.
- [RxKotlin/Pocket](https://github.com/RxKotlin/Pocket) - This app help user to save links easily, and can export to Evernote as weekly.
- [Android Clean Architecture - Kotlin](https://github.com/patrickyin/clean-architecture-android-kotlin) - A base project using the Uncle Bob's clean architecture with Kotlin language and the latest Android technologies.
- [Koin](https://insert-koin.io/) - Lightweight dependency injection framework for Kotlin.
- [AppDimens](https://github.com/bodenberg/appdimens) - Smart Responsive Dimensions for Any Screen (FX, DY, DP, SP, Logarithmic).

### Flutter
- [Flutter](https://flutter.dev/) - Google's mobile app SDK for high-quality native interfaces for Android and iOS in very quick time.

## Performance
- [awesome-android-performance](https://github.com/Juude/awesome-android-performance) - A list of awesome Android tutorials, videos and tools for performance optimization.
- [Booster](https://github.com/didi/booster) - An optimization toolkit for Android applications.

## Shrinking

- [ProGuard](https://www.guardsquare.com/proguard) - Open-source Java bytecode optimizer and shrinker for Android apps.
- [R8](https://developer.android.com/studio/build/shrink-code) - Default code shrinker and optimizer for Android apps.
- [ProGuard Playground](https://playground.proguard.com/) - Interactive online tool for visualizing and testing ProGuard and R8 keep rules.

## Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.
