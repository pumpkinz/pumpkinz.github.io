---
layout: post
title:  "Pumpkin Reader for Hacker News"
date:   2015-07-21 22:07:33
categories: portfolio
author: timotiusnc
image: /images/pumpkin-reader-banner.png
---
The idea for creating this app came from my friend [Agustinus Kristiadi][wiseodd]. He reads [Hacker News][hn] regularly and he demands a great mobile application to do it comfortably. He also happened to be a material design enthusiast. After trying several Hacker News reader app from Google Play Store, he never found one that suits his need and also quench his thirst of a good material design. So, he invited me to join him creating this app.

Three weks later, we released [Pumpkin Reader for Hacker News v1.0][v1.0]. Developing this app sure was an exciting experience. For me, this is the first time I dove into Android development since I first did it a couple years ago (IIRC, it's still Android API level 10 (Gingerbread)). It's nice to know that Google has put a lot of effort to improve Android development experience since then. For example, I really like my experience developing in Android Studio (compared to the way I used to develop in Eclipse). I also like [Android Design Support Library][supp] that provides us with lots of Material-Design-approed-components, preventing us from building everything from scratch.

Moreover, there are now a lot of open source libraries we can use to help us in Android development. For Pumpkin Reader, we used [Retrofit][retrofit], combined with [RxJava][rxjava] and [RxAndroid][rxandroid]. Harnessing the power of those open source softwares really helped us to get the foundation done sooner, therefore we can focus on our main features faster.

Realizing that we have learned so much just by creating this simple app, we planned to use Pumpkin Reader as a study-case to learn other platforms as well. We planned to develop Pumpkin Reader in iOS and web. We haven't started developing it yet, but for the web version we're really interested to use [ReactJs][reactjs]. We've been using [AngularJS][angular] with its famous [two-way data binding][databind] for some time and we're curious as how it compares to ReactJs' famous [diff algorithm][diffalgo].

In the meantime, please give our [Pumpkin Reader][pumpkin] app a try! We'd love to hear it from you!

<a href="https://play.google.com/store/apps/details?id=io.pumpkinz.pumpkinreader" target="_blank">
  <img src="https://developer.android.com/images/brand/en_generic_rgb_wo_60.png" alt="Get it on Google Play">
</a>

[wiseodd]:      http://thirdworldnomad.com
[hn]:           https://news.ycombinator.com
[v1.0]:         https://github.com/pumpkinz/pumpkin-reader/releases/tag/v1.0
[supp]:         http://android-developers.blogspot.com/2015/05/android-design-support-library.html
[retrofit]:     https://github.com/square/retrofit
[rxjava]:       https://github.com/ReactiveX/RxJava
[rxandroid]:    https://github.com/ReactiveX/RxAndroid
[reactjs]:      https://github.com/facebook/react
[databind]:     http://stackoverflow.com/a/9693933/1461624
[diffalgo]:     https://facebook.github.io/react/docs/reconciliation.html
[pumpkin]:      https://play.google.com/store/apps/details?id=io.pumpkinz.pumpkinreader
[angular]:      https://angularjs.org/
