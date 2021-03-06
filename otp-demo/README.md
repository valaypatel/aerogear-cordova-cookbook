# OTP demo
----------
Authors: Erik Jan de Wit (edewit)   
Level: Advanced   
Technologies: Cordova, iOS, Android   
Summary: And example of using the cordova otp plugin.   
Target Product: -   
Product Versions: -   
Source: https://github.com/aerogear/aerogear-cordova-cookbook/tree/master/otp-demo   

## What is it?

Want to setup security with OTP and create an mobile client for all platforms use the OTP cordova plugin.

## How do I run it?

### 0. System Requirements

* [Cordova 4.2](http://cordova.apache.org/)

For the complete instructions about how to setup OTP see the [OTP plugin documentation](https://github.com/aerogear/aerogear-cordova-otp)

### 1. Application Setup

To use this project as is, first clone the repo from GitHub, then run:

```bash
$ bower install
$ cordova restore plugins --experimental
```

**Notes:** 
[Cordova restore](http://cordova.apache.org/news/2014/07/10/tools-release.html) is an experimental feature that allows to persist the currently added plugins to config.xml.

If you don't want to use ```cordova restore```, you have to add all plugins manually (it might be required if you want to test the latest version of otp plugin for instance):

```bash
$ cordova plugin add org.jboss.aerogear.cordova.otp
```

#### iOS setup

* Add iOS platform

```bash
$ cordova platform add ios
```

* Deploy on device:

```bash
$ cordova run ios --device
```

#### Android setup

* Add Android platform

```bash
$ cordova platform add android
```

* Deploy on device:

```bash
$ cordova run android --device
```