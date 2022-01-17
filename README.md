# Kotlin Multiplatform Libraries

* [Network](#network)
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

#### Stomp

* [krossbow](https://github.com/joffrey-bion/krossbow) - A Kotlin multiplatform coroutine-based STOMP client over websockets  
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]

#### Utility

* [Connectivity status](https://github.com/ln-12/multiplatform-connectivity-status) - Monitor the internet connection status of your device on Android and iOS.  
![badge][badge-android]
![badge][badge-ios]

#### Authentication

* [cognito-idp](https://github.com/Liftric/cognito-idp) - Lightweight AWS Cognito Identity Provider client for Kotlin Multiplatform projects.  
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

* [SQLiter](https://github.com/touchlab/SQLiter) - Minimal multiplatform sqlite library  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

#### NoSQL

* [Realm](https://github.com/realm/realm-kotlin) - Kotlin Multiplatform and Android SDK for the Realm Mobile Database: Build Better Apps Faster.  
![badge][badge-android]
![badge][badge-ios]

* [Kodein-DB](https://github.com/Kodein-Framework/Kodein-DB) - Embedded NoSQL database  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]

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

#### FILE

* [okio](https://github.com/square/okio) - A modern I/O library for Android, Kotlin, and Java.[WIP]  
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
![badge][badge-jvm]

* [PopKorn](https://github.com/corbella83/PopKorn) - Forget about modules and components. DI can be simple.  
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
  
### Image

* [korim](https://github.com/korlibs/korim) - Kotlin cORoutines IMaging, Bitmap and Vector graphics for Multiplatform Kotlin   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
![badge][badge-tvos]
![badge][badge-watchos]
![badge][badge-windows]

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

* [klock](https://github.com/korlibs/klock) - Multiplatform Date and time library for Kotlin  
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

* [fluid-time](https://github.com/fluidsonic/fluid-time) - Kotlin multiplatform date & time library  
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-mac]

* [kcron](https://github.com/Scogun/kcron-common) - Kotlin multiplatform Cron library  
![badge][badge-jvm]
![badge][badge-linux]
![badge][badge-mac]
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
![badge-jvm][badge-jvm]
![badge-js][badge-js]
![badge-nodejs][badge-nodejs]
![badge-android][badge-android]
![badge-ios][badge-ios]
![badge-watchos][badge-watchos]
![badge-tvos][badge-tvos]
![badge-macos][badge-macos]
![badge-windows][badge-windows]
![badge-linux][badge-linux]

#### Cipher

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

* [encoding](https://github.com/05nelsonm/component-encoding) - Base 16/32/64 encoding.  
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

#### Paging

* [Multiplatform Paging](https://github.com/kuuuurt/multiplatform-paging) - Kotlin Multiplatform library for Pagination on Android and iOS  
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

#### Monads

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

* [kotlin-result](https://github.com/michaelbull/kotlin-result) - A Result monad for modelling success or failure operations.  
![badge][badge-jvm]
![badge][badge-ios]
![badge][badge-js]

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

* [kotlinx-resources](https://github.com/goncalossilva/kotlinx-resources) - Multiplatform library for reading resources in tests.  
![badge-jvm][badge-jvm]
![badge-js][badge-js]
![badge-nodejs][badge-nodejs]
![badge-android][badge-android]
![badge-ios][badge-ios]
![badge-watchos][badge-watchos]
![badge-tvos][badge-tvos]
![badge-macos][badge-macos]
![badge-windows][badge-windows]
![badge-linux][badge-linux]

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

### Command Line Interface

* [Clikt](https://github.com/ajalt/clikt) - Multiplatform command line interface parsing for Kotlin  
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

* [kompass](https://github.com/sellmair/kompass) - Kotlin Multiplatform Router for Android and iOS  

* [Decompose](https://github.com/arkivanov/Decompose) - Kotlin Multiplatform lifecycle-aware business logic components (aka BLoCs) with routing functionality and pluggable UI (Jetpack Compose, SwiftUI, JS React, etc.), inspired by Badoos RIBs fork of the Uber RIBs framework.
![badge][badge-android]
![badge][badge-ios]
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-mac]
![badge][badge-tvos]
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

* [Premo](https://github.com/dmdevgo/Premo) — Presentation Model (aka View Model) and Navigation. Focus on writing logic instead of solving common and boring UI related issues: lifecycle, persistence, navigation, etc.   
![badge][badge-android]
![badge][badge-ios]
![badge][badge-jvm]
![badge][badge-js]


#### Project templates 

* [moko-template](https://github.com/icerockdev/moko-template) - Template project of a Mobile (Android & iOS) Kotlin MultiPlatform project with the MOKO libraries and modularized architecture   
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

* [KMMT](https://github.com/jittya/KMMT) - KMMT is a KMM based project template designed to simplify the KMM development. It uses a simplified MVVM approach that can be shared both in Android and iOS easily. 

* [Zakadabar](https://github.com/spxbhuhb/zakadabar-stack) - A Kotlin Multiplatform library for full-stack software development  
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-android]

* [multiplatform-swiftpackage](https://github.com/ge-org/multiplatform-swiftpackage) - This is a Gradle plugin for Kotlin Multiplatform projects that generates an XCFramework for your native Apple targets and creates a matching Package.swift file to distribute it as a binary target.  

### Artificial Intelligence

#### Symbolic AI

* [2P-Kt](https://github.com/tuProlog/2p-kt) - A Kotlin-based, multi-platform, open ecosystem for _symbolic_ artificial intelligence (AI) and logic programming (LP), currently supporting many facilities for LP and a full-fledged, extensible, ISO-standard Prolog solver.  
![badge][badge-js]
![badge][badge-jvm]
![badge][badge-nodejs]

### Social

#### tgbotapi

* [tgbotapi](https://github.com/InsanusMokrassar/TelegramBotAPI) - Strongly-typed API wrapper for [Telegram Bot API](https://core.telegram.org/bots/api) with
fully covered API and a lot of additional DSLs on top of base API.

![badge][badge-jvm]
![badge][badge-js]![badge][badge-js-ir]


## Contribute

Welcome contribute!
Please read the [contribution guidelines](Contributing.md) first.

[badge-android]: http://img.shields.io/badge/platform-android-6EDB8D.svg?style=flat
[badge-jvm]: http://img.shields.io/badge/platform-jvm-DB413D.svg?style=flat
[badge-js]: http://img.shields.io/badge/platform-js-F8DB5D.svg?style=flat
[badge-js-ir]: https://img.shields.io/badge/support-[IR]-AAC4E0.svg?style=flat
[badge-nodejs]: https://img.shields.io/badge/platform-nodejs-68a063.svg?style=flat
[badge-linux]: http://img.shields.io/badge/platform-linux-2D3F6C.svg?style=flat 
[badge-windows]: http://img.shields.io/badge/platform-windows-4D76CD.svg?style=flat
[badge-wasm]: https://img.shields.io/badge/platform-wasm-624FE8.svg?style=flat
[badge-apple-silicon]: http://img.shields.io/badge/support-[AppleSilicon]-43BBFF.svg?style=flat
[badge-ios]: http://img.shields.io/badge/platform-ios-CDCDCD.svg?style=flat
[badge-mac]: http://img.shields.io/badge/platform-macos-111111.svg?style=flat
[badge-watchos]: http://img.shields.io/badge/platform-watchos-C0C0C0.svg?style=flat
[badge-tvos]: http://img.shields.io/badge/platform-tvos-808080.svg?style=flat
