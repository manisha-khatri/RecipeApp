# Android Recipes App

A simple Android application demonstrating modern Android development practices, including Jetpack Compose for UI, Hilt for dependency injection, Coroutines for asynchronous operations, and a clean MVVM architecture with Use Cases.

## ✨ Features

* **Recipe Listing:** Displays a list of recipes with their ingredients.
* **Recipe Deletion:** Allows users to delete recipes from the list.
* **MVVM Architecture:** Clean separation of concerns using Model-View-ViewModel.
* **Use Cases:** Business logic encapsulated in dedicated Use Case classes.
* **Dependency Injection:** Uses Hilt for managing dependencies.
* **Asynchronous Operations:** Leverages Kotlin Coroutines and `StateFlow` for background tasks and UI state management.
* **Jetpack Compose UI:** Modern declarative UI development.

## 🚀 Technologies Used

* **Kotlin:** Primary programming language.
* **Jetpack Compose:** For building the user interface.
    * `androidx.compose.material3`: Material Design 3 components.
    * `androidx.compose.runtime`: Core Compose runtime.
    * `androidx.activity:activity-compose`: Compose integration for `ComponentActivity`.
* **Kotlin Coroutines:** For asynchronous and non-blocking operations.
    * `kotlinx-coroutines-core`
    * `kotlinx-coroutines-android`
* **Android Architecture Components:**
    * **ViewModel:** Manages UI-related data in a lifecycle-aware manner.
    * **Lifecycle:** Manages component lifecycles, especially with coroutines (`viewModelScope`, `collectAsStateWithLifecycle`).
    * **StateFlow/MutableStateFlow:** Hot observable data holders for reactive UI updates.
* **Hilt (Dagger Hilt):** For dependency injection.
    * `com.google.dagger:hilt-android`
    * `com.google.dagger:hilt-compiler`
    * `androidx.hilt:hilt-navigation-compose`
* **WorkManager:** (Present in `libs.versions.toml`, but not explicitly used in the provided code snippet for this specific feature).
* **Retrofit & Gson:** (Present in `libs.versions.toml`, but not explicitly used for the fake data).
* **Room:** (Present in `libs.versions.toml`, but not explicitly used for the fake data).
* **Apollo GraphQL:** (Present in `libs.versions.toml`, but not explicitly used).

## 📁 Project Structure

The project follows a standard Clean Architecture / MVVM pattern: