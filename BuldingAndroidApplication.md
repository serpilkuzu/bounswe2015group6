# Android Operating System #

Android is a mobile operating system (OS) based on a modified Linux 2.6 kernel. Currently, Google and other members of the Open Handset Alliance (OHA) develop it. Android operating system is primarily designed for smartphones and tablets. It can also provides specialized user interfaces for televisions (Android TV), cars (Android Auto), and wrist watches (Android Wear). In the below, you can see the Android System Architecture:

![http://www.anddev.org/images/android/system_architecture.png](http://www.anddev.org/images/android/system_architecture.png)


Since Android is an open source, it has become the fastest growing mobile
operating system. As of July 2013 the Google Play store has had over one million Android applications ("apps") published. Android users download more than 1.5 billion applications and games from Google Play each month.

Android has several version. You can see the usage of these version below:

|**Version** |       |**Codename**|       |**Distribution**|
|:-----------|:------|:-----------|:------|:---------------|
|2.2 |           |Froyo|             |0.4%|
|2.3.3-2.3.7|    |Gingerbread|       |7.4%|
|4.0.3-4.0.4|    |Ice Cream Sandwich|        |6.4%|
|4.1.x |         |Jelly Bean |     | 18.4%|
|4.2.x |         |Jelly Bean |                    |19.8%|
|4.3 |            |Jelly Bean |                    |6.3%|
|4.4 |           |KitKat |           |39.7%|
|5.0 |           |Lollipop|          |1.6%|

# Android Developer Guidelines #
![http://cdnimg.chip.gen.tr/images/content/2014102021261641472.jpg](http://cdnimg.chip.gen.tr/images/content/2014102021261641472.jpg)

Google maintains a vast, extensive collection of documentation and resources for how to program your apps that you can reference or search through.
Here are some sections that are worth brushing up on if you're getting started:

[Google Services](https://developer.android.com/google/index.html): here's where you get to see what's going on under the hood. Google offers a wide variety of features that you might otherwise have to build out yourself like map and location features, cloud backups, sign-in services and more. You can check them all out here.

[API Guides](https://developer.android.com/guide/index.html): Google services are set apart from the regular APIs, which you can also read about here. These range from code to create basic animations, to reading sensors and connecting to the internet. There's tons of info here to add functionality to your app.

[Sample Code](https://developer.android.com/samples/index.html): Sometimes it helps to see how someone else did it before you. This section shows you samples of code for various functions. This can help you see how something works, or just use it in your app so you don't have to reinvent the wheel.
# Android Design Guidelines #

![http://www.esato.com/gfx/news/img/android-4-ics-design-guidelines_1326715232.jpg](http://www.esato.com/gfx/news/img/android-4-ics-design-guidelines_1326715232.jpg)

The counterpart to the developer guidelines is the Design Guidelines. Google is focusing increasingly on teaching its developers how to make apps that not only work well but look good. As such, that means a lot of the work has been done for you to cover the basics like buttons, simple animations, and whatnot.

[Devices](https://developer.android.com/design/devices.html): Android targets more than just phones. This section will help you learn how phones, tablets, TVs, and watches all relate and how you can design an interface that adapts to all of them.

[Patterns](https://developer.android.com/design/patterns/index.html): Android is built on structured interfaces. This section teaches the building blocks of how apps work so you can design the framework that you'll be building your design on top of.

[Material Design Documentation](https://www.google.com/design/spec/material-design/introduction.html#introduction-principles): This is technically a separate section for now, but Google's newest version of Android will introduce a new type of design language called Material Design. Here you can peruse what that means and how to think about designing apps that fit these guidelines. It's also helpful if you're not experienced with thinking about how users interact with apps, even if you don't follow the specific recommendations.

# Developing an Android Application #
Android applications are developed for Android operating system and generally they are written in Java programming language using Android SDK. Developing an Android application needs a systematic roadmap. Generally, this workflow consist of several steps. As Android’s developer website suggests, development workflow should be look like below chart:

![http://developer.android.com/images/publishing/publishing_overview.png](http://developer.android.com/images/publishing/publishing_overview.png)

Definitely each step contains other smaller steps to be followed. And following these steps exactly or changing them slightly is totally developer’s choice.
# Development Environment #

Android Software Development Kid (SDK) includes some tools required to develop an Android Application. Currently, Android SDK is divided into five main groups which are Virtual Device, Development, Debugging, Build and Image Tools. These groups includes a debugger, emulator, documentation, sample codes, tutorials and many other tools. Current version is SDK 24.0.2 and it can be downloaded from [Android Web Page](http://developer.android.com/sdk/installing/index.html)


Today, Android’s official IDE is Android Studio. It has plenty of features to make it easier building an app. Although it is the official IDE, there are other options such as Eclipse and Net Beans. Actually, Eclipse was the official IDE until the end of 2014. Programmers can use a text editor to write the code and then can use command line to create their application too. There are several choices for development environment as one can notice.

An example screenshot of Android Studio:
![http://www.learn2crack.com/wp-content/uploads/2014/04/Screenshot-from-2014-04-24-210304.png](http://www.learn2crack.com/wp-content/uploads/2014/04/Screenshot-from-2014-04-24-210304.png)

Image is taken from [this website.](http://www.learn2crack.com/2014/04/android-login-registration-nodejs-client.html)



# Testing an Android Application #

The Android testing framework, an integral part of the development environment, provides an architecture and powerful tools that help you test every aspect of your application at every level from unit to framework.

## Testing Framework ##

The Android testing framework, an integral part of the development environment, provides an architecture and powerful tools that help you test every aspect of your application at every level from unit to framework.

The testing framework has these key features:

  * Android test suites are based on JUnit.
  * Test suites are contained in test packages that are similar to main application packages, so you don't need to learn a new set of tools or techniques for designing and building tests.
  * The SDK tools for building and tests are available in Eclipse with ADT, and also in command-line form for use with other IDEs.
  * The SDK also provides monkeyrunner, an API for testing devices with Python programs, and UI/Application Exerciser Monkey, a command-line tool for stress-testing UIs by sending pseudo-random events to a device.

The following diagram summarizes the testing framework:

![https://developer.android.com/images/testing/test_framework.png](https://developer.android.com/images/testing/test_framework.png)

## What to Test ##
As an Android developer, it is important to know what to test. Below you can find some most common Android-related situations that you should consider when you test.

### Change in Orientation ###
  * Is the screen re-drawn correctly?
  * Does the application maintain its state? (Does it lose anything the user has entered before?)

### Change in Configuration ###
  * Is a change in keyboard possible?
  * Is a change in system language possible?

### Battery Life ###
  * Does the app use the battery efficient?
  * Is the battery usage as minimized as possible?

### Dependence on external resources ###
  * How does the app react when an external resource is not available?

# Publishing an Android Application #
Publishing is the last step of building an Android App. After debugging and testing your application, when you feel ready to publish your application, there are still some work to do. There are some options to release an app. The most frequently used option is upload it to a marketplace. As an example, Google Play Store is the most popular and probably the most efficient place to distribute an app. Google Play Store will be explained briefly in this article later on.

## Preparing Application for Release ##
According to Android’s official website, after debugging and testing, next steps are “Preparing App for Release” and then “Release It to Users”. To prepare the app for release, you should remove the debugging and logging settings, configure manifest settings, and clean up your project. After you configure the app to release, you should “Build and sign a release version of app”. By this step you can test your application’s release version and check if a bug or something unexpected is generated after configuration step. Also you can be sure that all resources of your app work correctly. And lastly, if the application uses remote services or servers, it is a good idea to check whether they works correctly or not. These steps mainly covers how to prepare your application to be released but there are several other minor tasks you have to double check before you publish the application.

## Releasing Application to Users ##
After the application is prepared for release, you come to the very last step of building an Android Application which is actually release it to the users by determined way of distribution method. At this step developers usually use Google Play Store, because of its power of efficiency, reachability, stability and many other superiorities.But also developers can use other ways to publish their applications such as releasing through e-mail. Since you have .apk file of application, you can simply send it to anyone via e-mail. But this method have some security problems for obvious reasons - receiver of e-mail also can send it to anyone without your permission. Another way is publishing applications through a website. Developer prepare the application exactly same way as above, but this time just put it on a website and android device users can download it from this website. Actually this method is also widely used one too.

Also it is important to decide how  you can earn money from your application. At this point you have two major alternatives. First one is make your application a purchased app which means that deciding a price for your app then users can download it only after paying that much money. Second alternative is making it free and using in-app billing. This option requires more effort, because it covers some coding and testing processes. After you implement [in-app billing](http://developer.android.com/google/play/billing/billing_integrate.html) feature into your application, users pay some amount of determined money to use specific features of your application after downloading it.

### Google Play Store ###
Google Play Store is a digital marketplace where customers can download and browse applications, and many other features. It is developed by Google in October 22,2008. After 6 years, it currently contains about 1,300,000 applications and has reached over 50 billion downloads. Google Play Store App’s user interface helps user to browse different categories of applications, rate them, put reviews and it gives users suggestions about applications to download.


These features obviously gives developer highly efficient feedbacks. Google Play Store also keeps statistics about applications such as installs, uninstalls, ratings, crashes, users which is very helpful for a developer. It gives developers daily or cumulative reports about their applications. It also gives financial reports about applications in two types namely, “Earnings Reports” and “Estimated Sales Report”. Since this is a brief summary of many features of Google Play Store, if you interested in developing an Android Application, you can get complete information from [Google Play Store's official website](https://support.google.com/googleplay/android-developer/#).
# Application Examples #
## Top 5 Most Downloaded Applications ##

  * [Gmail](https://play.google.com/store/apps/details?id=com.google.android.gm), by Google
  * [Chrome Browser](https://play.google.com/store/apps/details?id=com.android.chrome), by Google
  * [Angry Birds](https://play.google.com/store/apps/details?id=com.rovio.angrybirds), by Rovio Mobile Ltd.
  * [Facebook](https://play.google.com/store/apps/details?id=com.facebook.katana), by Facebook
  * [Skype](https://play.google.com/store/apps/details?id=com.skype.raider), by Skype

## Top 5 Most Downloaded Paid Applications ##
  * [Minecraft - Pocket Edition](https://play.google.com/store/apps/details?id=com.mojang.minecraftpe), by Mojang
  * [Where's My Water](https://play.google.com/store/apps/details?id=com.disney.wheresmywater2_goo), by Disney Mobile
  * [Asphalt7: Heat](https://play.google.com/store/apps/details?id=com.gameloft.android.ANMP.GloftA7HM), by Gameloft
  * [Poweramp Full Version Unlocker](https://play.google.com/store/apps/details?id=com.maxmpz.audioplayer.unlock), by Max MP
  * [Beatiful Widgets Pro](https://play.google.com/store/apps/details?id=com.levelup.beautifulwidgets), by Max MP
Both above lists are taken from [Wikipedia](http://en.wikipedia.org/wiki/List_of_most_downloaded_Android_applications)

## Applications that Our Group Finds Worth To Look At ##

  * [Word Lens](https://www.youtube.com/watch?v=h2OfQdYrHRs), by QuestVisual (bought by Google)
  * [Pocket](https://play.google.com/store/apps/details?id=com.ideashower.readitlater.pro&hl=en),by Read It Later
# References #

  1. http://en.wikipedia.org/wiki/Android_(operating_system)
  1. https://developer.android.com/about/dashboards/index.html
  1. https://developer.android.com/tools/testing/index.html
  1. http://en.wikipedia.org/wiki/Google_Play#Play_Store_.28Android_app.29
  1. http://lifehacker.com/i-want-to-write-android-apps-where-do-i-start-1643818268