# Basic Push Notifications Sample App for Windows Phone


<a id="top"></a>
* [Overview](#overview)
* [Requirements](#requirements)
* [Configuration](#configuration)
* [Running the Sample](#running-the-sample)

# Overview

This repository contains a basic sample app that can receive push notifications sent from its Telerik Platform backend. It is a native app built using .NET and Visual Studio.

The sample app utilizes the [Telerik Platform backend .NET SDK](http://docs.telerik.com/platform/backend-services/dotnet/getting-started-dotnet-sdk) to connect the app to Telerik Platform.

# Requirements

Before you begin, you need to ensure that you have the following:

- **An active [Telerik Platform](https://platform.telerik.com) account**
Ensure that you can log in to a Telerik Platform account. This can be a free trial account.
- **A Telerik Platform application** You can use an existing application or create a new one. 
- **Microsoft Visual Studio** You need it to load the Visual Studio project file.

# Configuration

The sample app comes fully functional, but to see it in action you must link it to your own Telerik Platform account.

1. Open your Telerik Platform application and go to **Settings**.
2. Take note of your **App ID**.
3. Open the `Windows Phone Push Subscriber/ConnectionSettings.cs` file in Visual Studio.
4. Find the `TelerikPlatformAppId` literal and replace its value with the actual App ID that you acquired earlier.
5. Finally, set up push notifications in your application as explained in [Enabling Push Notifications](http://docs.telerik.com/platform/backend-services/dotnet/push-notifications/push-enabling).

# Running the Sample

Once the app is configured, you can run it on a real device from within Visual Studio.

> Push notifications are not supported when running the app on device simulators.

> Ensure that the device that you are using has Internet connectivity when running the sample.


