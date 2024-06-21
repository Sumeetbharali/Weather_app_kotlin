Weather App using Jetpack Compose and Retrofit

This is a weather application built with Kotlin, Jetpack Compose, and Retrofit. It fetches weather data from a remote API and displays it in a user-friendly interface using Jetpack Compose.

Project Structure

The project structure is organized as follows:

app:

Contains the main code for the application.
manifests: Android manifest files.
java/ir.sumeet.asmrweather: Kotlin source files.
models: Contains data-related classes (entities, data sources, repositories).
network: Retrofit service interfaces and network-related utilities.
Screens: UI components and screens implemented using Jetpack Compose.
repositories: all the repository classes.
res: Resources including layouts, drawables, and values.
build.gradle: Project-level Gradle build file.

app/build.gradle: App-level Gradle build file where dependencies are declared.

How to Run the App

To run the app locally, follow these steps:

Clone the repository:git clone https://github.com/your/repository.git


Open Android Studio:

Open Android Studio and select Open an existing Android Studio project.
Navigate to the directory where you cloned the repository and select the root folder.
Run the app:

Connect your Android device or use an emulator.
Build and run the project using the Run button in Android Studio.
Challenges Faced During Development

During the development of this project, several challenges were encountered:

Integrating Jetpack Compose:

Jetpack Compose was relatively new at the time, which required learning its concepts and adapting traditional UI development practices to the declarative model.
Setting Up Retrofit:

Configuring Retrofit to work seamlessly with Kotlin Coroutines for asynchronous network calls posed initial challenges.
Handling API Responses:

Parsing and mapping complex JSON responses from the weather API to Kotlin data classes while ensuring error handling and data consistency.
UI Design and Responsiveness:

Designing responsive UI components that adapt well to different screen sizes and orientations using Jetpack Compose's layout system.
Testing and Debugging:

Ensuring the app performs reliably across different Android versions, handling edge cases, and debugging issues related to network calls and UI rendering.
