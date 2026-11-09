# Lunch Tray

A lunch ordering flow: pick an entree, a side dish and an accompaniment, then review the order with subtotal, tax and total at checkout.

Built while following Google's [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/course) course (the "Lunch Tray" navigation practice project).

## Features

- Start screen, then entree, side dish and accompaniment menus with radio-button selection and prices
- Checkout screen with the selected items, subtotal, tax (8%) and total
- Cancel returns to the start screen; Up navigation in the app bar

## Built with

- Kotlin, Jetpack Compose, Material 3
- Navigation Compose (`NavHost`, enum-based routes)
- `ViewModel` with `StateFlow<OrderUiState>`
- Sealed `MenuItem` class for the three item types
- Min SDK 24, target/compile SDK 35

## Run it

1. Open the project folder in Android Studio and let Gradle sync.
2. Run the `app` configuration on an emulator or device (Android 7.0 / API 24 or newer).

Or, with a device or emulator connected:

```sh
./gradlew installDebug
```
