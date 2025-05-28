# Capacitor Android Setup Guide

This guide outlines the steps to set up and run your Capacitor project for Android.

## Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Android Studio](https://developer.android.com/studio)
- [Capacitor CLI](https://capacitorjs.com/docs/getting-started)

## Installation

Install Capacitor CLI globally:

```bash
npm install -g @capacitor/cli
```

Install required Capacitor packages locally:

```bash
npm install @capacitor/core
npm install @capacitor/android
```

## Build Android Project

Create the `android/` folder:

```bash
npx cap add android
```

Sync the `www` directory with the native Android project:

```bash
npx cap sync android
```

## Open in Android Studio

Open the Android project in Android Studio to build and run:

```bash
npx cap open android
```

> ⚠️ Make sure Android Studio is installed before running the above command.
