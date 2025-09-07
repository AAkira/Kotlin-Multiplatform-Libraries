# Kotlin Multiplatform Libraries

* [Network](#network)
* [Repository](#repository)
* [Serializer](#serializer)
* [Storage](#storage)
* [DI](#di)
* [Image](#image)
* [Audio](#audio)
* [Bluetooth](#bluetooth)
* [Reactive](#reactive)
* [Utility](#utility-1)
* [Debug](#debug)
* [Test](#test)
* [Annotation Processor](#annotation-processor)
* [GUI](#gui)
* [Command Line Interface](#command-line-interface)
* [Architecture](#architecture)
* [Docs](#docs)
* [Build & Development Tools](#build--development-tools)
* [Artificial Intelligence](#artificial-intelligence)
* [Social](#social)
* [Health](#health)

## Libraries

### Network

#### Http

* [Ktor](https://github.com/ktorio/ktor) - Framework for quickly creating connected applications in Kotlin with minimal effort  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]

* [ktor-client-oauth-feature](https://github.com/kuuuurt/ktor-client-oauth-feature) - Ktor Client Feature for handling OAuth token refreshes  
![badge][badge-ios]
![badge][badge-jvm]

* [kmp-tor](https://github.com/05nelsonm/kmp-tor) - Embed Tor into your application.  
![badge][badge-android]
![badge][badge-jvm]


* [Ktorfit](https://github.com/Foso/Ktorfit) - HTTP client / Kotlin Symbol Processor for Kotlin Multiplatform (Js, Jvm, Android, Native, iOS) using KSP and Ktor clients inspired by Retrofit  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]

* [fuel](https://github.com/kittinunf/fuel) - The easiest HTTP networking library for Kotlin backed by Kotlinx Coroutines.  
![badge][badge-android]
![badge][badge-jvm]

* [rsocket-kotlin](https://github.com/rsocket/rsocket-kotlin) - [RSocket](https://rsocket.io) Kotlin multi-platform implementation based on [kotlinx.coroutines](https://github.com/Kotlin/kotlinx.coroutines) and [Ktor](https://github.com/ktorio/ktor).   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]
![badge][badge-watchos]
![badge][badge-tvos]

* [kotliny.network](https://github.com/corbella83/kotliny.network) - Simple, powerful and lightweight Kotlin Multiplatform Network Client.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]

* [ktor-simple-cache](https://github.com/Scogun/ktor-simple-cache) - Easy-to-use lightweight library which adds configurable output cache support to [Ktor](https://github.com/ktorio/ktor), including [Memory](https://github.com/Scogun/ktor-simple-cache/tree/main/ktor-simple-memory-cache) and [Redis](https://github.com/Scogun/ktor-simple-cache/tree/main/ktor-simple-redis-cache) providers.  
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]

#### GraphQL

* [apollo](https://www.apollographql.com/docs/android/essentials/get-started-multiplatform/) - Multiplatform official GraphQL client.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]

* [suparnatural-graphql](https://github.com/suparngp/kotlin-multiplatform-projects/tree/master/graphql) - Strict type safe GraphQL client with support for composable links.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]

* [kgql](https://github.com/yshrsmz/kgql) - GraphQL Document wrapper generator for Kotlin Multiplatform Project and Android  

#### Real-time communication
* [webrtc-kmp](https://github.com/shepeliev/webrtc-kmp) - WebRTC Kotlin Multiplatform SDK.  
![badge][badge-android]
![badge][badge-ios]

#### JSON-RPC

* [jsonrpc-kotlin-client](https://github.com/Reedyuk/jsonrpc-kotlin-client) -JSON-RPC Kotlin Multiplatform client.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-js]

#### Stomp

* [krossbow](https://github.com/joffrey-bion/krossbow) - A Kotlin multiplatform coroutine-based STOMP client over websockets  
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]

#### Utility

* [Connectivity status](https://github.com/ln-12/multiplatform-connectivity-status) - Monitor the internet connection status of your device on Android and iOS.  
![badge][badge-android]
![badge][badge-ios]

* [Highlights](https://github.com/SnipMeDev/Highlights) - Kotlin Multiplatform syntax highlighting engine.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-js-ir]

#### Authentication

* [cognito-idp](https://github.com/Liftric/cognito-idp) - Lightweight AWS Cognito Identity Provider client for Kotlin Multiplatform projects.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]

### Identity Wallet

* [VC-K](https://github.com/a-sit-plus/vck) - Kotlin Multiplatform library implementing W3C VC Data Model and ISO 18013-5 mDL.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]

### Repository

* [Store](https://github.com/MobileNativeFoundation/Store) - A Kotlin Multiplatform library for building network-resilient applications.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]

### Serializer

* [kotlinx.serialization (official)](https://github.com/Kotlin/kotlinx.serialization) - Kotlin multiplatform / multi-format serialization  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-wasm]
![badge][badge-watchos]
![badge][badge-windows]

* [YAKL](https://github.com/jurgc11/yakl) - A YAML 1.2 processor  
![badge][badge-mac]
![badge][badge-linux]

* [KoAP](https://github.com/JuulLabs/koap) - CoAP encoder/decoder with support for UDP ([RFC 7252](https://tools.ietf.org/html/rfc7252)), TCP ([RFC 8323](https://tools.ietf.org/html/rfc8323)) and Observe ([RFC 7641](https://tools.ietf.org/html/rfc7641)).  
![badge][badge-js]
![badge][badge-jvm]

* [Pbandk](https://github.com/streem/pbandk) - Kotlin code generator and runtime for Protocol Buffers  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]

* [Kase64](https://github.com/saschpe/Kase64) - Base64 encoder/decoder for Kotlin/Multiplatform. Supports standard and URL-safe encodings.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [Kex](https://github.com/saschpe/Kex) - Hex string encoder/decoder for Kotlin/Multiplatform.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [Ktoml](https://github.com/akuleshov7/ktoml) - MPP serialization library (decoder/encoder) for TOML format.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [encoding](https://github.com/05nelsonm/component-encoding) - Rfc 4648 Section 4-8 compliant encoding (Base 16, 32 Crockford, 32 Default, 32 Hex, 64 Default, 64 Url Safe).  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-wasm]
![badge][badge-android-native]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

* [multi<sup>2</sup>–<sub>base</sub>](https://github.com/a-sit-plus/multibase) - Mutlibase and UVarInt encoding library. Verified against offical test vectors.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]


* [parcelize](https://github.com/05nelsonm/component-parcelize) - Implement Android `Parcelable` from common code.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-wasm]
![badge][badge-android-native]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

### Storage

#### RDB

* [SQLDelight](https://github.com/square/sqldelight) - Generates typesafe Kotlin APIs from SQL.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [Room](https://developer.android.com/kotlin/multiplatform/room) - Official Android Room for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]

* [SQLiter](https://github.com/touchlab/SQLiter) - Minimal multiplatform sqlite library  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [Door](https://github.com/UstadMobile/door) - Room for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-js]
![badge][badge-jvm]

* [AWS - S3](https://github.com/estivensh4/aws-kmp) - AWS KMP is an extension to AWS Kotlin Multiplatform for JVM, Android and iOS.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]

#### NoSQL

* [Realm](https://github.com/realm/realm-kotlin) - Kotlin Multiplatform and Android SDK for the Realm Mobile Database: Build Better Apps Faster.  
![badge][badge-android]
![badge][badge-ios]

* [Kotbase](https://github.com/jeffdgr8/kotbase) - Kotlin Multiplatform library for Couchbase Lite—a lightweight, embedded, syncable, NoSQL database  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-linux]
![badge][badge-windows]

* [Kodein-DB](https://github.com/Kodein-Framework/Kodein-DB) - Embedded NoSQL database  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]

* [Couchbaselite](https://github.com/MyUNiDAYS/couchbaselite-kotlin-sdk) - Kotlin Multiplatform wrapper for the Couchbase Lite Mobile Database.  
![badge][badge-android]
![badge][badge-ios]

#### KVS

* [multiplatform-settings](https://github.com/russhwolf/multiplatform-settings) - A Kotlin Multiplatform library for saving simple key-value data.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [KVault](https://github.com/Liftric/KVault) - Secure key-value storage for Kotlin Multiplatform projects.  
![badge][badge-android]
![badge][badge-ios]

* [Kissme](https://github.com/netguru/Kissme) - Kissme: Kotlin Secure Storage Multiplatform  
![badge][badge-android]
![badge][badge-ios]

* [Multiplatform-Preferences](https://github.com/florent37/Multiplatform-Preferences) - Kotlin Multi Platform Preferences, for android an ios : SharedPreferences & NSUserDefault.  
![badge][badge-android]
![badge][badge-ios]

* [kds](https://github.com/kotlingang/kds) - Multiplatform coroutine-based kotlin library for saving Serializables with kotlinx.serialization and delegates.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]

* [Kottage](https://github.com/irgaly/kottage) - Kotlin Multiplatform Key-Value Store Local Cache Storage for Single Source of Truth.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [Universal-Cache](https://github.com/andrew0000/universal-cache) - Kotlin Flow caching and request sharing. Main idea: don't request data more times than it's needed.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-ios]

* [KCrypt](https://github.com/abhriyaroy/KCrypt) - Kotlin encryption key generator and encrypted key-value storage.  
![badge][badge-android]
![badge][badge-ios]

* [Kedis](https://github.com/domgew/kedis) - Redis client library for Kotlin Multiplatform (JVM + Native).  
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]

#### FILE

* [okio](https://github.com/square/okio) - A modern I/O library for Android, Java, and Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]

* [suparnatural-fs](https://github.com/suparngp/kotlin-multiplatform-projects/tree/master/fs) - Kotlin Multi Platform File System access library for `iOS` and `Android`.  
![badge][badge-android]
![badge][badge-ios]

* [suparnatural-cache](https://github.com/suparngp/kotlin-multiplatform-projects/tree/master/cache) - A superfast, thread safe in-memory cache with configurable hashing schemes backed by persistent stores with blocking/non-blocking I/O.  
![badge][badge-android]
![badge][badge-ios]

* [KStore](https://github.com/xxfast/KStore) - A tiny Kotlin multiplatform library that assists in saving and restoring objects to and from disk using kotlinx.coroutines, kotlinx.serialisation and okio.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-wasm]
![badge][badge-watchos]
![badge][badge-windows]

#### File System

* [Kfswatch](https://github.com/irgaly/kfswatch) - Kotlin Multiplatform File System Watcher  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

### DI

* [Kodein-DI](https://github.com/Kodein-Framework/Kodein-DI) - Painless Kotlin Dependency Injection  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-wasm]
![badge][badge-watchos]
![badge][badge-windows]

* [Koin](https://github.com/InsertKoinIO/koin) -  A pragmatic lightweight dependency injection framework for Kotlin  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

* [PopKorn](https://github.com/corbella83/PopKorn) - Forget about modules and components. DI can be simple.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]

* [kotlin-inject](https://github.com/evant/kotlin-inject) - Dependency injection lib for kotlin.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

* [Koject](https://github.com/mori-atsushi/koject) - DI Container library for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

* [Ivy DI](https://github.com/Ivy-Apps/di) - A simple and lightweight runtime Dependency Injection (DI) container for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-wasm]

### Image

* [korim](https://github.com/korlibs/korge/tree/main/korge-core#korim) - Kotlin cORoutines IMaging, Bitmap and Vector graphics for Multiplatform Kotlin   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [Kraphviz](https://github.com/Yeicor/kraphviz) - [Graphviz](https://graphviz.org/) for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-wasm]
![badge][badge-android-native]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

* [Kim - Kotlin Image Metadata](https://github.com/Ashampoo/kim) - Kotlin Multiplatform library for reading and writing image metadata.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-ios]
![badge][badge-mac]

### Audio

* [korau](https://github.com/korlibs/korau) - Pure Kotlin WAV, MP3 and OGG vorbis decoders  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

### Bluetooth

* [Blue-Falcon](https://github.com/Reedyuk/blue-falcon) - A Bluetooth kotlin multiplatform "Cross-Platform" library for iOS and Android  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-mac]

* [Kable](https://github.com/juullabs/kable) - Simple Coroutines-powered API for interacting with Bluetooth Low Energy devices.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-mac]

### Reactive

#### Rx

* [Reaktive](https://github.com/badoo/Reaktive) - Kotlin multi-platform implementation of Reactive Extensions  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [RxCommon](https://github.com/noheltcj/RxCommon) - Multiplatform implementation of ReactiveX providing a common way to build one set of business logic for native, iOS, Javascript, Android, JVM, and other platforms   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]

#### LiveData(Android)

* [Multiplatform-LiveData](https://github.com/florent37/Multiplatform-LiveData) - Multiplatorm implementation of LiveDatas / MVVM in kotlin android & native ios  
![badge][badge-android]
![badge][badge-ios]

### Utility

#### Asynchronous

* [coroutine (official)](https://github.com/Kotlin/kotlinx.coroutines) - Support for Kotlin coroutine.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [suparnatural-concurrency](https://github.com/suparngp/kotlin-multiplatform-projects/tree/master/concurrency) - Unified APIs such as Workers, Schedulers for cross-platform multithreading on `iOS` and `Android`.  
![badge][badge-android]
![badge][badge-ios]

* [Koru](https://github.com/FutureMind/koru) - Coroutine wrappers for Kotlin Native generated from annotations.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

* [KMP-NativeCoroutines](https://github.com/rickclephas/KMP-NativeCoroutines) - Library to use Kotlin Coroutines from Swift code in KMP apps.  
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

* [FlowExt](https://github.com/hoc081098/FlowExt) - Kotlinx Coroutines Flow Extensions. Extensions to the Kotlin Flow library.   
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-ios]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-mac]
![badge][badge-linux]
![badge][badge-js]
![badge][badge-windows]

#### Date, Time

* [kotlinx-datetime](https://github.com/Kotlin/kotlinx-datetime) - Official date and time library  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-windows]
![badge][badge-watchos]

* [island-time](https://github.com/erikc5000/island-time) - A Kotlin Multiplatform library for working with dates and times  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]

* [time](https://github.com/MrAsterisco/Time) - Type-safe time calculations in Kotlin, on any platform  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-mac]
![badge][badge-watchos]

* [time](https://github.com/sebj/time) - Type-safe time periods for the Kotlinx-datetime multiplatform date/time library  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]

* [fluid-time](https://github.com/fluidsonic/fluid-time) - Kotlin multiplatform date & time library  
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-mac]

* [KDateTime](https://github.com/sunny-chung/kdatetime-multiplatform) - Date time library focusing on custom formatting, parsing, platform independence and interoperability.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-wasm]

* [kcron](https://github.com/Scogun/kcron-common) - Kotlin multiplatform Cron library  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js] 
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]

* [Kronos Multiplatform](https://github.com/softartdev/Kronos-Multiplatform) - Network Time Protocol (NTP) library  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-mac]
![badge][badge-linux]
![badge][badge-windows]

#### Semantic Versioning

* [SemVer-KMP](https://github.com/QazCetelic/SemVer-KMP) - A Kotlin library for Semantic Versioning with ranges and other features.  
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]

* [kotlin-semver](https://github.com/z4kn4fein/kotlin-semver) - Semantic Versioning library for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-js-ir]
![badge][badge-nodejs]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-wasm]
![badge][badge-apple-silicon]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

#### EventBus

* [Multiplatform-Bus](https://github.com/florent37/Multiplatform-Bus) - Kotlin event-bus compatible with Android & native iOS.  
![badge][badge-android]
![badge][badge-ios]

* [Event4k](https://github.com/nort3x/Event4k) - MultiPlatform Kotlin EventBus library - simple, bidirectional, concurrent.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-js-ir]
![badge][badge-nodejs]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-wasm]
![badge][badge-apple-silicon]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

#### Number

* [kotlin-multiplatform-bignum](https://github.com/ionspin/kotlin-multiplatform-bignum) - A Kotlin multiplatform library for arbitrary precision arithmetics  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]
![badge][badge-watchos]
![badge][badge-tvos]

#### Hashing

* [kotlinx-murmurhash](https://github.com/goncalossilva/kotlinx-murmurhash) - Multiplatform library for MurmurHash, a non-cryptographic hash function for general hash-based lookup focused on simplicity and performance.  
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-android]
![badge][badge-ios]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-mac]
![badge][badge-windows]
![badge][badge-linux]

#### Cryptography

* [krypt](https://github.com/korlibs/krypto) - Cryptography library. Support for SecureRandom, Hash(MD5/SHA1/SHA256), AES.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]

* [kotlin-multiplatform-libsodium](https://github.com/ionspin/kotlin-multiplatform-libsodium) - A Kotlin Multiplatform wrapper for Libsodium cryptography library.   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]
![badge][badge-watchos]
![badge][badge-tvos]

* [cryptography-kotlin](https://github.com/whyoleg/cryptography-kotlin) - Type-safe Multiplatform cryptography library for Kotlin which doesn't implement any cryptography algorithm on its own, but wraps well-known future-proof solutions like [OpenSSL 3.x](https://www.openssl.org), [WebCrypto](https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API) or [JCA](https://docs.oracle.com/en/java/javase/17/security/java-cryptography-architecture-jca-reference-guide.html).   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]

* [KotlinCrypto/hash](https://github.com/KotlinCrypto/hash) - Hash functions (MD5/SHA1/SHA2/SHA3).   
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-wasm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-android-native]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

* [KotlinCrypto/MACs](https://github.com/KotlinCrypto/MACs) - Message Authentication Code functions (Hmac MD5/SHA1/SHA2/SHA3, KMAC).   
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-wasm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-android-native]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

* [KotlinCrypto/sponges](https://github.com/KotlinCrypto/sponges) - Sponge functions & state (Keccak-p).   
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-wasm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-android-native]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

* [KotlinCrypto/secure-random](https://github.com/KotlinCrypto/secure-random) - Cryptographically secure random number generator, `SecureRandom`.   
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-android-native]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

* [DatL4g/Sekret](https://github.com/Datl4g/Sekret) - 🔒 Deeply hide secrets with Kotlin Multiplatform (API Keys, Application credentials, etc).   
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-android-native]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

* [Signum](https://github.com/a-sit-plus/signum) - Kotlin Multiplatform Crypto/PKI Library and ASN1 Parser + Encoder.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]

#### String Utils

* [FuzzyWuzzy-Kotlin](https://github.com/willowtreeapps/fuzzywuzzy-kotlin) - Fuzzy string matching on collections.  Port of python & java library.

![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-wasm]
![badge][badge-windows]

* [kasechange](https://github.com/pearxteam/kasechange) - Multiplatform Kotlin library to convert strings between various case formats including Camel Case, Snake Case, Pascal Case and Kebab Case.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-wasm]

* [kotlin-multiplatform-diff](https://github.com/petertrr/kotlin-multiplatform-diff) - Multiplatform Kotlin library for calculating text differences.  
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]

* [doistx-normalize](https://github.com/Doist/doistx-normalize) -- Kotlin Multiplatform library for string unicode normalization ([UAX #15](https://unicode.org/reports/tr15/)).  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

* [KeepLink](https://github.com/motorro/KeepLink) -- Kotlin multiplatform deep-link definition, parsing and creation library.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]

#### Input/Output

* [keyboard-mouse-kt](https://github.com/Animeshz/keyboard-mouse-kt) - Multiplatform Kotlin library for interacting with global keyboard and mouse events and states.  
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]

#### Analytics

* [Kotlin-Multiplatform-Firebase](https://github.com/RubyLichtenstein/Kotlin-Multiplatform-Firebase) - Kotlin Multiplatform - Android/iOS/Web/Node.Js(Firebase)  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]

* [FirestoreKMP](https://github.com/touchlab/firestorekmp) - Firestore KMP Library  
![badge][badge-android]
![badge][badge-ios]

* [measurer](https://github.com/soushin/measurer) - Google Analytics(using measurement protocol).  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]

* [SegmenKT](https://github.com/MyUNiDAYS/Segmenkt) - A Segment wrapper for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]

* [sentry-kotlin-multiplatform](https://github.com/getsentry/sentry-kotlin-multiplatform) - [Sentry](https://sentry.io/) SDK for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]

#### Atomic

* [AtomicFu](https://github.com/Kotlin/kotlinx.atomicfu) - The idiomatic way to use atomic operations in Kotlin  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

#### UUID

* [uuid](https://github.com/benasher44/uuid) - Kotlin Multiplatform UUID  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]

* [kotlinx-uuid](https://github.com/hfhbd/kotlinx-uuid) - kotlinx-uuid is a multiplatform (MPP) Kotlin library introducing support for UUID.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]

#### Paging

* ~~[Multiplatform Paging (Archived)](https://github.com/kuuuurt/multiplatform-paging) - Kotlin Multiplatform library for Pagination on Android and iOS~~  
![badge][badge-android]
![badge][badge-ios] 

* [Multiplatform Paging](https://github.com/cashapp/multiplatform-paging) - A library that adds additional Kotlin/Multiplatform targets to AndroidX Paging, and provides UI components to use Paging on iOS.  
![badge][badge-android]
![badge][badge-ios]


#### Kotlin/Native

* [Stately](https://github.com/touchlab/Stately) - The library is set of multithreaded collection classes that will allow multithreaded mutation in Kotlin/Native.  
![badge][badge-ios]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [coroutineworker](https://github.com/Autodesk/coroutineworker) - Kotlin Coroutine-based workers for native  
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-windows]
![badge][badge-mac]

#### Units

* [Measured](https://github.com/nacular/measured) - Intuitive, type-safe units of measure.  
![badge][badge-jvm]
![badge][badge-js]

* [KotlinCrypto/endians](https://github.com/KotlinCrypto/endians) - Utils for converting `Short`, `Int`, `Long` to/from `BigEndian` and `LittleEndian` bytes.   
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-wasm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-android-native]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

#### Monads

* [ItsOk](https://github.com/PaoloConte/kotlin-itsok) - A new take on the `Result` monad for clean error handling.   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-wasm]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

* [Kotlin utilities](https://czerwinski.it/projects/kotlin-util/) - Scala utility types: `Option`, `Either`, `Try` for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-wasm]

* [kotlin-result](https://github.com/michaelbull/kotlin-result) - A multiplatform Result monad for modelling success or failure operations.  
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-ios]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

* [ApiResult](https://github.com/respawn-app/ApiResult) - A monad for declarative & functional error-handling with a rich DSL.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

* [Résultat](https://github.com/nicolashaan/resultat) - A fork of Kotlin Result with a loading state.  
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-ios]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-apple-silicon]

* [value-clazz](https://github.com/05nelsonm/component-value-clazz) - Functionally equivalent to a Kotlin `value class` that implements an interface, but inheritance based and compiles to platform code.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-wasm]
![badge][badge-android-native]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

* [KmmResult](https://github.com/a-sit-plus/KmmResult) - Wrapper of `kotlin.Result` with KMM goodness.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

#### WebAssembly

* [ktmpwasm](https://github.com/Yeicor/ktmpwasm) - A WebAssembly interpreter for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-wasm]
![badge][badge-android-native]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

#### Metadata

* [XMP Core for Kotlin Multiplatform](https://github.com/Ashampoo/xmpcore) - Kotlin Multiplatform port of Adobe's XMP SDK.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-ios]
![badge][badge-mac]

#### Parsing

* [Ksoup](https://github.com/fleeksoft/ksoup) - HTML & XML Parser (Jsoup Alternative)  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-apple-silicon]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-wasm]
![badge][badge-linux]
![badge][badge-windows]

* [KtXml](https://github.com/kobjects/ktxml) - XML Parser (Basically a KXml2 port to Kotlin)  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-nodejs]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

* [RSS-Parser](https://github.com/prof18/RSS-Parser) - A Kotlin Multiplatform library to parse a RSS Feed  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-ios]

* [JsonPath4K](https://github.com/a-sit-plus/jsonpath4k) - Kotlin Multiplatform Library for using Json Paths as defined in [RFC9535](https://datatracker.ietf.org/doc/rfc9535).  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]

### Debug

#### Logging

* [Napier](https://github.com/AAkira/Napier) - Logging library for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-jvm]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-js-ir]
![badge][badge-apple-silicon]

* [KmLogging](https://github.com/LighthouseGames/KmLogging) - High performance, composable multiplatform logging.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]

* [klogger](https://github.com/korlibs/klogger) - Logging library for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]

* [Multiplatform-Log](https://github.com/florent37/Multiplatform-Log) - Logging library for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]

* [Kermit](https://github.com/touchlab/Kermit) - Kotlin Multiplatform logging utility with composable log outputs and prebuilt loggers.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]

* [Log4k](https://github.com/hadilq/log4k) - Logging library for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]

* [Cabret-Log](https://github.com/Foso/Cabret-Log) - Method call logging for Kotlin Multiplatform   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]

* [KmmAnkoLogger](https://github.com/september669/KmmAnkoLogger) - fork of the AnkoLogger for use it with Kotlin Multiplatform Mobile  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]

### Test

* [assertk](https://github.com/willowtreeapps/assertk) - Assertions for kotlin inspired by assertj.  
![badge][badge-jvm]
![badge][badge-android]
![badge][badge-js]
![badge][badge-mac]
![badge][badge-ios]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-linux]
![badge][badge-windows]

* [Atrium](https://github.com/robstoll/atrium) - A multiplatform assertion library for Kotlin.  
![badge][badge-android]
![badge][badge-js]
![badge][badge-jvm]

* [konform](https://github.com/konform-kt/konform) - Portable validations.  
![badge][badge-js]
![badge][badge-jvm]

* [kotest-assertions](https://github.com/kotest/kotest) - Multiplatform assertions and test utilities.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [kotest-framework](https://github.com/kotest/kotest) - Multiplatform test framework for Kotlin.  
![badge][badge-js]
![badge][badge-jvm]

* [mockk](https://github.com/mockk/mockk) - Mocking library for test.  
![badge][badge-android]
![badge][badge-jvm]

* [Mockative](https://github.com/mockative/mockative) - Mocking for Kotlin/Native and Kotlin Multiplatform using the Kotlin Symbol Processing API (KSP)  
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-android]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-windows]
![badge][badge-linux]

* [MocKMP](https://github.com/Kodein-Framework/MocKMP) - A Kotlin/Multiplatform Kotlin Symbol Processor that generates Mocks & Fakes.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]

* [Mokkery](https://github.com/lupuuss/Mokkery) - Mocking library for Kotlin Multiplatform based on compiler plugin.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

* [kotlinx-resources](https://github.com/goncalossilva/kotlinx-resources) - Multiplatform library for reading resources in tests.  
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-android]
![badge][badge-ios]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-mac]
![badge][badge-windows]
![badge][badge-linux]

* [Truthish](https://github.com/varabyte/truthish) - Multiplatform library with a testing API inspired by Google Truth.  
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-android]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-windows]
![badge][badge-linux]



* [testmints](https://github.com/robertfmurdock/testmints) - Lightweight test semantic-sugar, to improve readability.  
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-android]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-windows]
![badge][badge-linux]

* [jsmints](https://github.com/robertfmurdock/jsmints) - A suite of libraries and gradle plugins for working with Kotlin JS, with a focus on testing and version updating.  
![badge][badge-js]

### Annotation Processor

* [MpApt](https://github.com/Foso/MpApt) - Kotlin Native/JS/JVM Annotation Processor library  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]

* [kotlin-native-suspend-function-callback](https://github.com/feilfeilundfeil/kotlin-native-suspend-function-callback) - Kotlin Multiplatform compiler plugin to generate a callback implementation for suspended functions so they are visible from Kotlin Native  
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]

* [trckr](https://github.com/dzmpr/trckr) - KSP processer that simplifies the collection of analytics  
![badge][badge-jvm]
![badge][badge-android]
![badge][badge-ios]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-mac]
![badge][badge-windows]
![badge][badge-linux]

* [KMP-ComposeUIViewController](https://github.com/GuilhE/KMP-ComposeUIViewController) - KSP library for generating ComposeUIViewController and UIViewControllerRepresentable files when using Compose Multiplatform for iOS  
![badge][badge-ios]
![badge][badge-jvm]

* [KOMM](https://github.com/Scogun/komm) - Kotlin Object Multiplatform Mapper which generates mapping function via KSP and supports multi-mapping, converters, resolvers, null-substitute etc.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]

### GUI

* [moko-widgets](https://github.com/icerockdev/moko-widgets) - Declarative UI and screens management in common code for mobile (android & ios) Kotlin Multiplatform development  
![badge][badge-android]
![badge][badge-ios]

* [kgl](https://github.com/Dominaezzz/kgl) - This library provides a thin OOP wrapper with DSLs to make programming with vulkan easier.  
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]

* [kotlin-libui](https://github.com/msink/kotlin-libui) - Kotlin/Native interop to libui: a portable GUI library  
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]

* [kotlin-material-ui](https://github.com/subroh0508/kotlin-material-ui) - Kotlin Wrapper Library of Material-UI  
![badge][badge-js]

* [muirwik](https://github.com/cfnz/muirwik) - Kotlin Wrapper Library of Material-UI  
![badge][badge-js]

* [compose-macos-theme](https://github.com/chozzle/compose-macos-theme) - Multiplatform MacOS theme written in Compose UI  
![badge][badge-android]
![badge][badge-jvm]

* [componentbox](https://github.com/dropbox/componentbox) - A Kotlin multiplatform library for building dynamic server-driven UI  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-js]

* [kontrol](https://github.com/chopyourbrain/kontrol) - A Kotlin Multiplatform library for creating a debugging menu  
![badge][badge-android]
![badge][badge-ios]

* [koala-plot](https://github.com/KoalaPlot) - A Compose Multiplatform based charting and plotting library written in Kotlin  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]

* [Material Theme Preferences](https://github.com/softartdev/MaterialThemePrefs) - Switching Dark/Light Material themes on Compose  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-mac]
![badge][badge-linux]
![badge][badge-windows]

* [DrawBox](https://github.com/MarkYav/DrawBox) - The first multiplatform library to draw anything on canvas.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]

* [typist-cmp](https://github.com/zeeshanali-k/typist-cmp) - A Highly Customisable Typing Animation Library for Compose Multiplatform (Android & iOS)  
![badge][badge-android]
![badge][badge-ios]

* [KodeView](https://github.com/SnipMeDev/KodeView) - Kotlin Multiplatform syntax highlighting views.  
 ![badge][badge-android]
 ![badge][badge-ios]
 ![badge][badge-js]
 ![badge][badge-jvm]
 ![badge][badge-linux]
 ![badge][badge-windows]
 ![badge][badge-mac]
 ![badge][badge-js-ir]

* [Wavy slider](https://github.com/mahozad/wavy-slider) - Animated squiggly slider (aka sperm) similar to the one in Android 13   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-js-ir]

* [Korender](https://github.com/zakgof/korender) - 3D graphics engine for Kotlin Multiplatform  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]

* [Kdomskia](https://github.com/kdomskia/kdomskia) - Create Web (DOM), Mobile and Desktop apps. Built on top of Compose Multiplatform.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-windows]

### Animation / UI

* [Kottie](https://github.com/ismai117/kottie) - Compose Multiplatform animation library that parses Adobe After Effects animations. Inspired by Lottie  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]

### Command Line Interface

* [Clikt](https://github.com/ajalt/clikt) - Multiplatform command line interface parsing for Kotlin  
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]

* [Command_Parser](https://github.com/Martmists-GH/command_parser) - Multiplatform command parser using kotlinx.coroutines  
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]

* [Kotter](https://github.com/varabyte/kotter) - Multiplatform library for Kotlin command-line applications with support for text styling, animations, timers, and input.  
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]

* [Mordant](https://github.com/ajalt/mordant) - Multiplatform text styling for Kotlin command-line applications  
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]

### Firebase

* [Firebase Kotlin SDK](https://github.com/gitliveapp/firebase-kotlin-sdk/) - Firebase SDK for Kotlin Multiplatform projects (Firebase Authentication, Realtime Database, Cloud Firestore, Cloud Functions, Cloud Messaging and Cloud Storage).  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]

### Architecture
* [KmpEssentials](https://github.com/TheArchitect123/KmpEssentials) - KmpEssentials is a library that contains apis (40+ Modules) to accelerate your development. Everything from managing the Battery, File System, getting Package information, Biometrics, or taking Screenshots & Photos/Videos.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-watchos]

* [kompass](https://github.com/sellmair/kompass) - Kotlin Multiplatform Router for Android and iOS  

* [Decompose](https://github.com/arkivanov/Decompose) - Kotlin Multiplatform lifecycle-aware business logic components (aka BLoCs) with routing functionality and pluggable UI (Jetpack Compose, SwiftUI, JS React, etc.), inspired by Badoos RIBs fork of the Uber RIBs framework.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]

* [Decompose-Router](https://github.com/xxfast/Decompose-Router) - Compose Multiplatform navigation library that leverage Decompose to create an API inspired by Conductor  
![badge][badge-android]
![badge][badge-wearos]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-mac]
![badge][badge-watchos]

* [oolong](https://github.com/oolong-kt/oolong) - MVU for Kotlin Multiplatform  

* [moko-mvvm](https://github.com/icerockdev/moko-mvvm) - MVVM architecture components for mobile multiplatform with LiveData (iOS and Android)   
![badge][badge-android]
![badge][badge-ios]

* [MVIKotlin](https://github.com/arkivanov/MVIKotlin) - MVI framework for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-watchos]

* [Orbit MVI](https://github.com/orbit-mvi/orbit-mvi) - MVI framework for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]

* [ReduxKotlin](https://github.com/reduxkotlin/redux-kotlin) - Redux implementation for Kotlin (supports multiplatform JVM, native, JS, WASM)   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-wasm]

* [FlowMVI](https://github.com/respawn-app/FlowMVI) - Plugin-based Kotlin Multiplatform MVI framework.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-nodejs]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

* [ReKamp](https://github.com/xorum-io/ReKamp) - Port of [ReKotlin](https://github.com/ReKotlin/ReKotlin) to Kotlin Multiplatform, which corresponds to [ReKotlin/1.0.4](https://github.com/ReKotlin/ReKotlin/releases/tag/1.0.4).   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]

* [Kaskade](https://github.com/gumil/kaskade) - Simplifying UI state management in Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]

* [Flywheel](https://github.com/abhimuktheeswarar/Flywheel) - A simple and predictable state management library inspired by Redux and a few more. Fully built on top of coroutines using the concept of [actors](https://www.brianstorti.com/the-actor-model/).   
![badge][badge-jvm]
![badge][badge-android]
![badge][badge-ios]
![badge][badge-watchos]
![badge][badge-tvos]
![badge][badge-mac]
![badge][badge-linux]
![badge][badge-js]
![badge][badge-windows]

* [KStateMachine](https://github.com/nsk90/kstatemachine) - KStateMachine is a Kotlin DSL library for creating state machines and hierarchical state machines (statecharts).  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]

* [CommonStateMachine](https://github.com/motorro/CommonStateMachine) - CommonStateMachine is a small non-opinionated library to implement MVI with the state-machine pattern.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-js]

* [VisualFSM](https://github.com/Kontur-Mobile/VisualFSM) - VisualFSM is a Kotlin Multiplatform library for implements an FSM-based (Finite-state machine) MVI pattern and a set of tools for visualization and analysis of FSM's diagram of states.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-mac]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-js]

* [Premo](https://github.com/dmdevgo/Premo) — Presentation Model (aka View Model) and Navigation. Focus on writing logic instead of solving common and boring UI related issues: lifecycle, persistence, navigation, etc.   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-js]

* [multiplatform-viewmodel](https://github.com/doublesymmetry/multiplatform-viewmodel) — Shared ViewModel in Kotlin Multiplatform   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-tvos]

* [Direkt](https://github.com/myunidays/direkt) - Kotlin Multiplatform Router for Android, iOS, Js   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]

* [compose_bloc](https://github.com/beyondeye/compose_bloc) - State Management and Navigation Library for Jetpack Compose and Compose Multiplatform.   
![badge][badge-android]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]

* [Ballast](https://github.com/copper-leaf/ballast) - Opinionated Application State Management framework for Kotlin Multiplatform  

* [Kotlin Bloc](https://github.com/1gravity/Kotlin-Bloc) - A simple, predictable and composable UI framework for Kotlin Multiplatform  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]

* [kmp-viewmodel](https://github.com/hoc081098/kmp-viewmodel) - Shared ViewModel in Kotlin Multiplatform - A Kotlin Multiplatform library that provides shared MVVM for UI applications. Components are lifecycle-aware on Android.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-wasm]
![badge][badge-nodejs]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]

* [Blackbox](https://github.com/trueangle/Blackbox) - A lightweight framework that includes a set of architecture tools and approaches for building scalable, fully multiplatform applications (100% shared logic). Streamlines project modularization through the separation into independent parts and provides features like lifecycle-aware components, declarative navigation, and constructor-based DI.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-mac]

* [Voyager](https://github.com/adrielcafe/voyager) - A multiplatform navigation library built for, and seamlessly integrated with, Jetpack Compose. Additionally, it features a Screenmodel, functioning similarly to a viewmodel.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-mac]
![badge][badge-windows]

* [solivagant](https://github.com/hoc081098/solivagant) - Compose Multiplatform Navigation - Pragmatic, type safety navigation for Compose Multiplatform. Based on Freeletics Khonshu Navigation. ViewModel, SavedStateHandle, Lifecycle, Multi-Backstacks, Transitions, Back-press handling, and more...  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]

* [hakate](https://github.com/kigawa-net/hakate) - A state management library. It can manage state with dependency.  
![badge][badge-android]
![badge][badge-jvm]
![badge][badge-js]

#### Project templates 

* [moko-template](https://github.com/icerockdev/moko-template) - Template project of a Mobile (Android & iOS) Kotlin MultiPlatform project with the MOKO libraries and modularized architecture   
![badge][badge-android]
![badge][badge-ios]

* [KMMT](https://github.com/jittya/KMMT) - KMMT is a Multi-Module KMM based project template designed to simplify the KMM development. It uses a simplified approach that can be shared both in android and iOS easily. This template include network module, persistence module, resource module, analytics module ( with ios native library integration), domain module, presenter module etc.  
![badge][badge-android]
![badge][badge-ios]

### Docs

* [dokka (official)](https://github.com/Kotlin/dokka) - Documentation Engine for Kotlin.  

### Build & Development Tools

* [BuildKonfig](https://github.com/yshrsmz/BuildKonfig) - It reads values from properties and adds those into Build config like Android.

* [kotlin-native-cocoapods](https://github.com/AlecStrong/kotlin-native-cocoapods) - Gradle plugin for configuring Kotlin/Native with Cocoapods.

* [kotlin-frontend-plugin (official)](https://github.com/Kotlin/kotlin-frontend-plugin) - ~~Gradle plugin for frontend development.~~  
![badge][badge-js]  
=> Deprecated move [here](https://github.com/JetBrains/kotlin/tree/master/js)

* [kotlin-dce](https://kotlinlang.org/docs/reference/javascript-dce.html) - This tool allows to strip out unused properties, functions and classes from the generated JS.   
![badge][badge-js]  

* [xcode-kotlin](https://github.com/touchlab/xcode-kotlin) - Kotlin Native Xcode Plugin

* [xcode-compat(official)](https://github.com/Kotlin/xcode-compat) - AppCode helper for Kotlin/Native and Xcode  

* [KotlinXcodeSync](https://github.com/touchlab/KotlinXcodeSync) - Sync Kotlin files with an Xcode project

* [kotlinx-benchmark(official)](https://github.com/Kotlin/kotlinx-benchmark) - https://github.com/Kotlin/kotlinx-benchmark  
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]

* [mobile-multiplatform-gradle-plugin](https://github.com/icerockdev/mobile-multiplatform-gradle-plugin) - Gradle plugin to make Multiplatform projects settings simplier   
![badge][badge-android]
![badge][badge-ios]

* [kotlinx-ast(official)](https://github.com/kotlinx/ast) - Generic AST parsing library for kotlin multiplatform  

* [KaMPKit](https://github.com/touchlab/KaMPKit) - KaMP Kit by Touchlab is a collection of code and tools designed to get your mobile team started quickly with Kotlin Multiplatform  

* [Zakadabar](https://github.com/spxbhuhb/zakadabar-stack) - A Kotlin Multiplatform library for full-stack software development  
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-android]

* [multiplatform-swiftpackage](https://github.com/ge-org/multiplatform-swiftpackage) - This is a Gradle plugin for Kotlin Multiplatform projects that generates an XCFramework for your native Apple targets and creates a matching Package.swift file to distribute it as a binary target.  

* [Swift Klib](https://github.com/ttypic/swift-klib-plugin) - This is a Gradle Plugin to build Swift code as part of your Kotlin Multiplatform project. With this plugin, you can access Swift-only iOS libraries, such as CryptoKit and experiment with Swift to Kotlin interoperability.  

### Artificial Intelligence

#### Symbolic AI

* [2P-Kt](https://github.com/tuProlog/2p-kt) - A Kotlin-based, multi-platform, open ecosystem for _symbolic_ artificial intelligence (AI) and logic programming (LP), currently supporting many facilities for LP and a full-fledged, extensible, ISO-standard Prolog solver.  
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-nodejs]

* [Y-Chat](https://github.com/yml-org/ychat) - Y—Chat is a Kotlin Multiplatform (KMP) project that provides a simple API for integrating the powerful ChatGPT language model developed by OpenAI into mobile applications running on multi platforms.  
![badge][badge-jvm]
![badge][badge-android]
![badge][badge-ios]
![badge][badge-mac]

### Social

#### tgbotapi

* [tgbotapi](https://github.com/InsanusMokrassar/TelegramBotAPI) - Strongly-typed API wrapper for [Telegram Bot API](https://core.telegram.org/bots/api) with
fully covered API and a lot of additional DSLs on top of base API.  
![badge][badge-jvm]
![badge][badge-js]
![badge][badge-js-ir]

* [kbsky](https://github.com/uakihir0/kbsky) - [Bluesky/ATProtocol](https://atproto.com/) library for kotlin multiplatform.  
![badge][badge-jvm]
![badge][badge-ios]
![badge][badge-mac]

### Health

* [KHealth](https://github.com/shubhamsinghshubham777/KHealth) - A Kotlin Multiplatform wrapper over Android's [Health Connect](https://developer.android.com/health-and-fitness/guides/health-connect) and Apple's [HealthKit](https://developer.apple.com/documentation/healthkit) APIs.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-watchos]

### Math

* [Multiplatform expressions evaluator](https://github.com/murzagalin/multiplatform-expressions-evaluator) - Runtime infix expressions evaluator.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

* [Multik](https://github.com/Kotlin/multik) - Multiplatform library for Kotlin, specializing in multidimensional array operations with features like static typing and dimensional consistency, offering high-speed mathematical and arithmetic operations, as well as linear algebra functionalities.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-windows]
![badge][badge-mac]
![badge][badge-wasm]

### Miscellaneous

* [mavlink-kotlin](https://github.com/divyanshupundir/mavlink-kotlin) - A modern MAVLink library for Kotlin Multiplatform.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-watchos]
![badge][badge-windows]

## Contribute

Welcome contribute!
Please read the [contribution guidelines](Contributing.md) first.

[badge-android]: http://img.shields.io/badge/-android-6EDB8D.svg?style=flat
[badge-android-native]: http://img.shields.io/badge/support-[AndroidNative]-6EDB8D.svg?style=flat
[badge-wearos]: http://img.shields.io/badge/-wearos-8ECDA0.svg?style=flat
[badge-jvm]: http://img.shields.io/badge/-jvm-DB413D.svg?style=flat
[badge-js]: http://img.shields.io/badge/-js-F8DB5D.svg?style=flat
[badge-js-ir]: https://img.shields.io/badge/support-[IR]-AAC4E0.svg?style=flat
[badge-nodejs]: https://img.shields.io/badge/-nodejs-68a063.svg?style=flat
[badge-linux]: http://img.shields.io/badge/-linux-2D3F6C.svg?style=flat 
[badge-windows]: http://img.shields.io/badge/-windows-4D76CD.svg?style=flat
[badge-wasm]: https://img.shields.io/badge/-wasm-624FE8.svg?style=flat
[badge-apple-silicon]: http://img.shields.io/badge/support-[AppleSilicon]-43BBFF.svg?style=flat
[badge-ios]: http://img.shields.io/badge/-ios-CDCDCD.svg?style=flat
[badge-mac]: http://img.shields.io/badge/-macos-111111.svg?style=flat
[badge-watchos]: http://img.shields.io/badge/-watchos-C0C0C0.svg?style=flat
[badge-tvos]: http://img.shields.io/badge/-tvos-808080.svg?style=flat
