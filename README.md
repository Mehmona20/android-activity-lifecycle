# android-activity-lifecycle
Android Activity Lifecycle Demonstration

# Android Activity Lifecycle

## Introduction
This project demonstrates the Activity Lifecycle in Android
using Java and XML layouts.

## Objectives
- Understand the Android Activity Lifecycle.
- Learn the purpose of lifecycle callback methods.
- Navigate between two activities.
- Understand how lifecycle events are logged.

## Lifecycle Methods

### 1. onCreate()
Called when an activity is first created.

### 2. onStart()
Called when the activity becomes visible.

### 3. onResume()
Called when the activity enters the foreground
and the user can interact with it.

### 4. onPause()
Called when the activity loses foreground focus.

### 5. onStop()
Called when the activity is no longer visible.

### 6. onRestart()
Called when a stopped activity is about to start again.

### 7. onDestroy()
Called before an activity is destroyed.

## Project Files
- MainActivity.java
- SecondActivity.java
- activity_main.xml
- activity_second.xml
- AndroidManifest.xml

## Tools Used
- Java
- XML
- Android SDK

## How It Works
The Main Activity displays a button to open the Second Activity.
Lifecycle callback messages are written to Logcat using Log.d().

## Conclusion
This project explains the Android Activity Lifecycle
and demonstrates how lifecycle callback methods work.

