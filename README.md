# App Builders 2018

**April 16-17, 2018 Lugano, Switzerland**

* [Website](https://www.appbuilders.ch)
* [Youtube](https://www.youtube.com/channel/UC9hu86f3N9wJgLk7l8kxFeA)
* [Twitter](https://twitter.com/appbuilders_ch?lang=en)

<mark>**The notes below only cover the iOS Panel**<mark>

# Table Of Contents

- [Day One](#day-one)
  * [Lessons learned from the App Store](#lessons-learned-from-the-app-store)
  * [Work-life Balance & Burnout - Q&A Session](#work-life-balance--burnout---qa-session)
  * [iOS Application Architecture](#ios-application-architecture)
  * [A Better MVC](#a-better-mvc)
  * [Lightning Talks](#lightning-talks)
    + [Apple MDM and Kiosk applications](#apple-mdm-and-kiosk-applications)
    + [One nice trick to solve way too many Auto Layout issues](#one-nice-trick-to-solve-way-too-many-auto-layout-issues)
    + [Using the Swift Package Manager on iOS](#using-the-swift-package-manager-on-ios)
    + [Launching a mac app](#launching-a-mac-app)
  * [Rethinking Object-Oriented Design](#rethinking-object-oriented-design)
  * [Becoming An Effective Contributor to Swift](#becoming-an-effective-contributor-to-swift)
  * [System Scalability - Q&A Session](#system-scalability---qa-session)
  * [The Little App that Got Us into Big Trouble](#the-little-app-that-got-us-into-big-trouble)
  * [Advanced Debugging Techniques your senior hasn’t told you about](#advanced-debugging-techniques-your-senior-hasnt-told-you-about)
  * [Sharing](#sharing)
- [Day Two](#day-two)
  * [Why We Build Products - Firebase](#why-we-build-products---firebase)
  * [Entrepreneurship - Q&A Session](#entrepreneurship---qa-session)
  * [Swift Generics - The 5 Stages of PATs](#swift-generics---the-5-stages-of-pats)
  * [How to Build a Modern iOS App](#how-to-build-a-modern-ios-app)
  * [Swift & Objective-C](#swift--objective-c)
  * [Lightning Talks](#lightning-talks-1)
    + [Jumpstarting localization using AppleGlot4](#jumpstarting-localization-using-appleglot4)
    + [Tasty cakes have complicated recipes](#tasty-cakes-have-complicated-recipes)
    + [Review your own code with Android Lint](#review-your-own-code-with-android-lint)
    + [Building your app, or being built by it?](#building-your-app-or-being-built-by-it)
  * [Bootstrapping the Machine Learning Training Process](#bootstrapping-the-machine-learning-training-process)
  * [iOS - 10 years in review](#ios---10-years-in-review)
  * [Into the Deep](#into-the-deep)
  * [A Quest for a Better World](#a-quest-for-a-better-world)

# Day One

## Lessons learned from the App Store
### _Phillip Shoemaker_

Main lessons:

* Communicate your intends
* Talk to your costumes
* It can always get harder
* Use the stick and the carrot
* Developers are wily
* Perception is everything
* Never trust a magician

Major Store Challenges:

* Rating and review fraud
* Malware in Xcode

Contact Phillip at <phillip@realityshiftnetwork.com>

##### [Full presentation video](https://youtu.be/tJeEuxn9mug)

<br>

## Work-life Balance & Burnout - Q&A Session
### with Steve Scott & Beatrice Sigrist Charbonnier

Host: [Steve Scott](https://twitter.com/macdevnet)

Guest: [Beatrice Sigrist Charbonnier](http://de.sigristcoaching.ch/)

Platform promoted: [https://www.noburnout.ch](https://www.noburnout.ch)

##### [Full live-session video](https://youtu.be/K_OrZ0e35x8)

<br>

## iOS Application Architecture
### Krzysztof Zabłocki

Sings of bad architecture:

<img src="Media/KrzysztofZabłocki_00.jpg" height="250">
<img src="Media/KrzysztofZabłocki_01.jpg" height="250">
<img src="Media/KrzysztofZabłocki_02.jpg" height="250">

Flow Coordinators:

* [Flow Controllers](http://merowing.info/2016/01/improve-your-ios-architecture-with-flowcontrollers/)
* [Redux Coordinators](http://khanlou.com/2015/10/coordinators-redux/)


##### [Full presentation video](https://youtu.be/PdkWjdKOqfo)

<br>

## A Better MVC
### Dave DeLong

Refactoring MVC:

1. Patterns are data structures
2. Naming affects perception. Naming reflects intend.
3. Consider VC as view
4. Views are small
5. Views are compose-able
6. Views are reusable
7. Views show data or have children
8. Actual controllers are needed

<img src="Media/DaveDeLong_00.jpg" height="250">
<img src="Media/DaveDeLong_01.jpg" height="250">
<img src="Media/DaveDeLong_02.jpg" height="250">

##### [Full presentation video](https://youtu.be/YWVzCd5FYbs)

<br>

## Lightning Talks

⚡️⚡️⚡️

### Apple MDM and Kiosk applications
#### by Florent Pillet

<img src="Media/FlorentPillet_00.jpg" height="250">

<br>

### One nice trick to solve way too many Auto Layout issues
#### by Aleksandar Vacić

Slide from a side animation with constraints.
Using 999 as priority to avoid runtime autolayout exceptions.

<br>

### Using the Swift Package Manager on iOS
#### by Seán Labastille

How to build a MongoDB client with MongoKitten

<img src="Media/SeánLabastille_00.jpg" height="250">

<br>

### Launching a mac app
#### Marin Todorov

<img src="Media/MarinTodorov_00.jpg" height="250">

[Snippetty Tool](www.Snippetty.io)

<br>

## Rethinking Object-Oriented Design
### Graham Lee

[Wealthwizards Platform](wealthwizards.io)

##### [Full presentation video](https://youtu.be/6OQq2kE5wUY)

<br>

## Becoming An Effective Contributor to Swift
### Harlan Haskins & Robert Widmann

<img src="Media/HarlanHaskins_RobertWidmann_00.jpg" height="250">
<img src="Media/HarlanHaskins_RobertWidmann_01.jpg" height="250">

##### [Full presentation video](https://youtu.be/oGJKsp-pZPk)

<br>

## System Scalability - Q&A Session
### with Steve Scott & Antonio Carzaniga

Host: [Steve Scott](https://twitter.com/macdevnet)

Guest: [Antonio Carzaniga](http://www.inf.usi.ch/carzaniga/)

<br>

## The Little App that Got Us into Big Trouble
### Vikram Kriplaney

App area: **iOS Content Blockers**

<img src="Media/VikramKriplaney_00.jpg" height="250">

##### [Full presentation video](https://youtu.be/kFdc1ahcRX4)

<br>

## Advanced Debugging Techniques your senior hasn’t told you about
### Carola Nitz

Carola Nitz works at [Video Labs](https://videolabs.io/)

#### Raw notes:

* LLDB command: Register read.
* Layout feedback loop debugger.
* Work with launch options & diagnostics.
* See wwdc2016 236
* Concurrency debug
* Use debug Launch arguments. You can pass launch arguments at runtime.
* See Tn2239
* See Tn2124
* export @import UiKit ...in console or debug actions
* Use User breakpoint or shared breakpoint
* Nskvodeallocatebreak
* po $arg1

Check Psdpdfkit's user breakpoints in Xcode

#### Good practices for error handling

Usage of asserts. See swift optimization levels.
Precondition, preconditionFailure, fatalerror.

Slides will be uploaded...

##### [Full presentation video](https://youtu.be/LbAlIzxSO6M)

<br>

## Sharing
### John Sundell

_***nontechnical talk**_

* [Swift by Sundell](https://www.swiftbysundell.com/podcast/)
* [Stacktrace podcast](https://itunes.apple.com/ro/podcast/stacktrace/id1359435443?mt=2)

<img src="Media/JohnSundell_00.jpg" height="250">

##### [Full presentation video](https://youtu.be/_mQNwL8HkS0)

<br>
<br>

# Day Two

## Why We Build Products - Firebase
### Sebastian Schmidt

<img src="Media/SebastianSchmidt_00.jpg" height="250">

##### [Full presentation video](https://youtu.be/7-NUdnYkmdU)

<br>

## Entrepreneurship - Q&A Session
### with Steve Scott & Peter Steinberger

Host: [Steve Scott](https://twitter.com/macdevnet)

Guest: [Peter Steinberger](https://twitter.com/steipete)

PSPDFKit: [https://pspdfkit.com/](https://pspdfkit.com/)

##### [Full session video](https://youtu.be/eJ_BdSBxCZk)

<br>

## Swift Generics - The 5 Stages of PATs
### David Hart

*Uses Redux architecture (for better logging and instrumentation).

<img src="Media/DavidHart_01.jpg" height="250">

##### [Full session video](https://youtu.be/_CJXGCaA2_4)

<br>

## How to Build a Modern iOS App
### Paul Hudson

Wide color, 3D Touch, Spotlight, and more

<img src="Media/PaulHudson_00.jpg" height="250">

##### [Full session video](https://youtu.be/gmc5gwMNzBE)

<br>

## Swift & Objective-C
> Swift & Objective-C: The most adventurous mashup since „Avengers: Infinity War“

### Matthias Tretter

Tip: use https://git-scm.com/docs/git-bisect to find introduces issues.

<img src="Media/MatthiasTretter_00.jpg" height="250">


##### [Full session video](https://youtu.be/c-LAJKqyBCI)

<br>

## Lightning Talks

⚡️⚡️⚡️

### Jumpstarting localization using AppleGlot4
#### Dorin Danciu

<img src="Media/DorinDanciu_00.jpg" height="250">

<br>

### Tasty cakes have complicated recipes
#### Nataliya Patsovska

<img src="Media/NataliyaPatsovska_00.jpg" height="250">

<br>

### Review your own code with Android Lint
#### Michele Marchetti

<img src="Media/MicheleMarchetti_00.jpg" height="250">

<br>

### Building your app, or being built by it?
#### Josselin Pello

<img src="Media/JosselinPello_00.jpg" height="250">
<img src="Media/JosselinPello_01.jpg" height="250">

<br>

## Bootstrapping the Machine Learning Training Process
### Meghan Kane

<img src="Media/MeghanKane_02.jpg" height="250">

##### [Full session video](https://youtu.be/ugiPfm8ICZo)

<br>

## iOS - 10 years in review
### Alexsander Akers

<img src="Media/AlexsanderAkers_00.jpg" height="250">

##### [Full session video](https://youtu.be/doe06IAphJs)

<br>

## Into the Deep
> Into the Deep – or what would 80s have done with depth sensing technology?

### Tobias Due Munk

Presenting depth sensing technologies.

<img src="Media/TobiasDueMunk_00.gif" height="300">

##### [Full session video](https://youtu.be/SCOLRVVRDJk)

<br>

## A Quest for a Better World
### Adrian Kosmaczewski

##### [Full session video](https://youtu.be/bncZlutcAfo)

<br>

#### Share the knowledge, support the speakers, the organizers and consider attending future editions of the AppBuilders conference.

<br>

_**Note: All videos shared in this page are the property of Swiss Mobile Developers Association.**_

