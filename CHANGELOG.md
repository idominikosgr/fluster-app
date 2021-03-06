<a name="5.7.0"></a>
# [5.7.0](https://github.com/fluster/fluster-app/compare/v5.6.1...v5.7.0) (2019-02-09)

### Features

* improve toolbar spacing ([35cf838](https://github.com/fluster/fluster-app/commit/35cf8383cfb94981e9f049a4136e155844b86d77))

### Fix

* iOS glitch when changing categories on the details view ([9ba28ff](https://github.com/fluster/fluster-app/commit/9ba28ffc0a221093fab0501c11eff5eb7edd244e))

### Libs

* revert Ionic navigation to use promises again ([f81c54a](https://github.com/fluster/fluster-app/commit/f81c54ab0f5b57ef5edf93bf2a9e0f74027a2c9e))
* update various libs

<a name="5.6.1"></a>
# [5.6.1](https://github.com/fluster/fluster-app/compare/v5.6.0...v5.6.1) (2019-01-24)

### Bump up version

* apple store my love

<a name="5.6.0"></a>
# [5.6.0](https://github.com/fluster/fluster-app/compare/v5.5.0...v5.6.0) (2019-01-24)

### Fix

* add `<noscript/>` to index.html ([#62](https://github.com/fluster/fluster-app/pull/62))

### Libs

* update to Ionic v4
* update all actual libs dependencies

<a name="5.5.0"></a>
# [5.5.0](https://github.com/fluster/fluster-app/compare/v5.4.0...v5.5.0) (2018-12-07)

### Features

* Google login: remove scope birthday ([#61](https://github.com/fluster/fluster-app/issues/61))

### Fix

* improve calendar scrolling performance on mobile devices ([#55](https://github.com/fluster/fluster-app/issues/55))
* overscroll on appointment picker ([#56](https://github.com/fluster/fluster-app/issues/56))

### Libs

* update all actual libs dependencies

<a name="5.4.0"></a>
# [5.4.0](https://github.com/fluster/fluster-app/compare/v5.3.0...v5.4.0) (2018-11-21)

### UX

* move feature to extend the availability of an ad to a separate page ([#54](https://github.com/fluster/fluster-app/issues/54))

### Fix

* improve scrolling performances on date picker ([#55](https://github.com/fluster/fluster-app/issues/55))
* overscroll was not correct on the timeframe picker for advertiser ([#56](https://github.com/fluster/fluster-app/issues/56)) 

### Lib

* update last version of Ionic and other Cordova's libs

<a name="5.3.0"></a>
# [5.3.0](https://github.com/fluster/fluster-app/compare/v5.3.0...v5.3.0) (2018-11-09)

### UX

* if you offer a room or flat, per default the main view will be the one where you could look for candidates ([#53](https://github.com/fluster/fluster-app/issues/53))

### Lib

* update last version of Ionic and cordova-android

<a name="5.2.1"></a>
# [5.2.1](https://github.com/fluster/fluster-app/compare/v5.2.0...v5.2.1) (2018-10-27)

### Google Play

* Google Play as of 1st November is requesting at least API level 26 as target ([#52](https://github.com/fluster/fluster-app/issues/52))
* Try go solve weird Google Play issues regarding policy ([#51](https://github.com/fluster/fluster-app/issues/51))

<a name="5.2.0"></a>
# [5.2.0](https://github.com/fluster/fluster-app/compare/v5.1.3...v5.2.0) (2018-10-25)

### UX

* improve chat's textarea expand behavior ([#46](https://github.com/fluster/fluster-app/issues/46))
* move more options from the navbar to the bottom toolbar in the chat ([#45](https://github.com/fluster/fluster-app/issues/45))
* add ability to send a complaint from the chat ([#50](https://github.com/fluster/fluster-app/issues/50))
* display district in card stack and address details in summary of the details ([#47](https://github.com/fluster/fluster-app/issues/47))

### Fixes

* the "who" pane in the details was not displayed per default anymore in case of flatshare ([#48](https://github.com/fluster/fluster-app/issues/48))
* images in the cards stack were not correctly displayed as the second cards ([#49](https://github.com/fluster/fluster-app/issues/49))

<a name="5.1.3"></a>
# [5.1.3](https://github.com/fluster/fluster-app/compare/v5.1.2...v5.1.3) (2018-10-18)

### UX

* improve menu wording ([#44](https://github.com/fluster/fluster-app/issues/44))
* improve first choice page ([#43](https://github.com/fluster/fluster-app/issues/43))

### Fixes

* read correctly the value of picked birthday ([#42](https://github.com/fluster/fluster-app/issues/42))

<a name="5.1.2"></a>
# [5.1.2](https://github.com/fluster/fluster-app/compare/v5.1.1...v5.1.2) (2018-10-12)

### UX

* add a parallax effect on the navigation bar on Android too ([#40](https://github.com/fluster/fluster-app/issues/40))
* favorite artists' name were shrinked, display them properly ([#37](https://github.com/fluster/fluster-app/issues/37))

### Fixes

* some styles were not properly applied in Firefox ([#41](https://github.com/fluster/fluster-app/issues/41))

<a name="5.1.1"></a>
# [5.1.1](https://github.com/fluster/fluster-app/compare/v5.1.0...v5.1.1) (2018-10-10)

### UX

* don't display action sheet to select who could view a flatshare or flat if there isn't an ad yet ([#38](https://github.com/fluster/fluster-app/issues/38))

<a name="5.1.0"></a>
# [5.1.0](https://github.com/fluster/fluster-app/compare/v5.0.1...v5.1.0) (2018-10-09)

### Features

* on the page where users could select who could see theirs ads, add the information about how many users could be reached ([#33](https://github.com/fluster/fluster-app/issues/33))
* when users would refresh their profile, refresh the details of their ads ([#23](https://github.com/fluster/fluster-app/issues/23))

### UX

* block double tap on sliders' images ([#35](https://github.com/fluster/fluster-app/issues/35))

### Fixes

* display of the photos were not updated after an ad would have been updated with the wizard ([#32](https://github.com/fluster/fluster-app/issues/32))
* square meters weren't displaying when editing an ad with the wizard ([#36](https://github.com/fluster/fluster-app/issues/36))

<a name="5.0.1"></a>
# [5.0.1](https://github.com/fluster/fluster-app/compare/v5.0.0...v5.0.1) (2018-10-02)

### Fixes for Android and PWA

* loading not dismissed if user go back and forth to first-choice page ([#29](https://github.com/fluster/fluster-app/issues/29))
* hardware back button support improved for the wizard and modals ([#28](https://github.com/fluster/fluster-app/issues/28) and [#30](https://github.com/fluster/fluster-app/issues/30)) 

<a name="5.0.0"></a>
# [5.0.0](https://github.com/fluster/fluster-app/releases/tag/v5.0.0) (2018-09-28)

Hooray, here is Fluster v5 🎉 

### Features

* You could now send requests without any viewing dates or timeframes
* If you do select timeframes, Fluster will assist you better by prefilling your availabilities, letting you spare even more time in the communication process
* The wizard to publish your flatshares is now shorter and therefore faster
* The integration of the photo filters is more user friendly
* Some interactions have been improved to make the overall experience friendlier

### Tech

* Fluster is now powered by Ionic v4 and Angular v6 which has for effect that the app is smoooooooooother

Hope you will enjoy this version, let me know if you face any issues or have improvements ideas 😃🤘

David

<a name="5.0.0-rc.0"></a>
# [5.0.0-rc.0](https://github.com/fluster/fluster-app/compare/v5.0.0-beta.7...v5.0.0-rc.0) (2018-09-27)

### UX

* add ripple effect to date picker ([#14](https://github.com/fluster/fluster-app/issues/14))
* on Android, don't apply the parallax effect on item details ([#1](https://github.com/fluster/fluster-app/issues/1))

### Fixes

* better handle some uncatched promises return ([#19](https://github.com/fluster/fluster-app/issues/19))

<a name="5.0.0-beta.7"></a>
# [5.0.0-beta.7](https://github.com/fluster/fluster-app/compare/v5.0.0-beta.6...v5.0.0-beta.7) (2018-09-26)

### UX

* miscellaneous improvements regarding design after a run of tests on (real) iOS and Android
* revert/remove the buttons on date picker and go back to tappable items ([#2](https://github.com/fluster/fluster-app/issues/2))

### Fixes

* search location of interests weren't displayed on iOS (only) ([#17](https://github.com/fluster/fluster-app/issues/17))
* the very first time a bookmark was set, it used to took a bit more time ([#15](https://github.com/fluster/fluster-app/issues/15))
* after the first week, the calendar directive didn't displayed the time of the appointments ([#13](https://github.com/fluster/fluster-app/issues/13))

<a name="5.0.0-beta.6"></a>
# [5.0.0-beta.6](https://github.com/fluster/fluster-app/releases/tag/v5.0.0-beta.6) (2018-09-23)

### Features

* help users by prefilling automatically their schedule when requesting viewings ([#12](https://github.com/fluster/fluster-app/issues/12))
* make viewings requests more flexible, allow requests without schedule ([#2](https://github.com/fluster/fluster-app/issues/2))
* remove step appointments from wizard ([#6](https://github.com/fluster/fluster-app/issues/6))

### UX

* reduce the size of the biggest font size ([#11](https://github.com/fluster/fluster-app/issues/11))
* when navigating side browse -> publish, don't navigate automaticall to wizard ([#10](https://github.com/fluster/fluster-app/issues/10))
* improve screenshots quality on login page ([#8](https://github.com/fluster/fluster-app/issues/8))
* status bar color on iOS ([#4](https://github.com/fluster/fluster-app/issues/4))
* highlight terms and conditions on login page ([#7](https://github.com/fluster/fluster-app/issues/7))
