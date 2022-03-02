# ComApp

Native Android simple chat application written in Kotlin using Jetpack Compose

* [Test - Video](https://www.youtube.com/watch?v=xcbukL4MDlQ) 🧪

* Screenshots 🖼️

|Splash|Login|Profile|
|------|-----|-------|
|<img src="https://user-images.githubusercontent.com/50905347/155622233-f76ff3d7-da3d-47e9-89a2-e401bd0887b7.png" width="270" height="570">|<img src="https://user-images.githubusercontent.com/50905347/155622238-9d075029-19e7-4fb3-a77d-71ba996d41f1.png" width="270" height="570">|<img src="https://user-images.githubusercontent.com/50905347/156369731-5d70332f-e851-4a22-b57c-fadae084ae35.png" width="270" height="570">|
|UserList|Chat|
|<img src="https://user-images.githubusercontent.com/50905347/155622809-ed653d79-3f46-4b37-985f-24cdf5107abb.png" width="270" height="570">|<img src="https://user-images.githubusercontent.com/50905347/155622823-aecda25e-2e06-45f1-8de4-7550f2597cfb.png" width="270" height="570">|

* Application - Features ☕
   * User Status (ONLINE - OFFLINE)
   * Message Status (RECEIVED - READ) - PENDING: After push notification.
   * Friend Status (PENDING, ACCEPTED, CANCELED, BLOCKED)
   * New Message Alert
   * Navigation Animation Between Sceens
   * LazyColumn Last Message Snap
   * UserList Swipe Reflesh
   * Push Notification

* Tech-stack ⚛️
    * [Kotlin](https://kotlinlang.org/) + [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) - perform background operation
    * [Google Firebase](https://firebase.google.com)
    * [One Signal](https://onesignal.com)
    * [Flows](https://developer.android.com/kotlin/flow)
    * [Hilt](https://github.com/google/dagger) - DI
    * [Accompanist](https://github.com/google/accompanist)
    * [Jetpack](https://developer.android.com/jetpack)
        * [Navigation](https://developer.android.com/topic/libraries/architecture/navigation/) - deal with whole in-app navigation      
        * [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - store and manage UI-related data in a lifecycle conscious way
        * [Compose](https://developer.android.com/jetpack/compose)
* Architecture 🏗️
    * Model-View-ViewModel
    * [Android Architecture components](https://developer.android.com/topic/libraries/architecture) ([ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel), [Navigation](https://developer.android.com/jetpack/androidx/releases/navigation))
 
 * Todo ✔️
   * Firebase request code optimization & cleaning ❌
   * Dark theme ❌
   * Push notification ✔️ Listening only offline & chat navigation when notf. pressed ❌
   * Login via Google ❌
   * Swipe - Gestures ❌


