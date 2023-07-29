# 7MinutesWorkout App

The 7MinutesWorkout app is an Android application designed to guide users through a short, effective workout routine. It includes features for managing exercises, tracking user progress, and now has an added BMI feature to help users monitor their body mass index.

## Table of Contents
- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The 7MinutesWorkout app aims to provide a quick and efficient workout routine for users with busy schedules. The app is built using modern Android development principles and utilizes various Android libraries and components to ensure smooth performance and user experience.

## Dependencies

The project uses the following dependencies:

- **Room and Lifecycle Dependencies**:
  - androidx.room:room-runtime:2.5.2
  - androidx.room:room-compiler:2.5.2 (kapt annotation processor)
  - androidx.room:room-ktx:2.5.2 (Kotlin extensions for coroutine support with Room)

- **Activity Extensions**:
  - androidx.activity:activity-ktx:1.7.2 (Kotlin extensions for coroutine support with activities)

- **Core Components**:
  - androidx.core:core-ktx:1.10.1
  - androidx.appcompat:appcompat:1.6.1
  - com.google.android.material:material:1.9.0
  - androidx.constraintlayout:constraintlayout:2.1.4

- **Testing Dependencies**:
  - junit:junit:4.13.2 (Unit testing)
  - androidx.test.ext:junit:1.1.5 (Android JUnit testing)
  - androidx.test.espresso:espresso-core:3.5.1 (UI testing)

Please ensure you have the specified versions of these dependencies in your development environment to ensure compatibility.

## Features

- **7 Minutes Workout Routine**: The app provides a carefully curated set of exercises that can be completed in just 7 minutes, making it ideal for busy users.

- **BMI Calculator**: The app now includes a BMI feature that allows users to calculate their Body Mass Index by providing their height and weight. This feature helps users monitor their fitness progress and make informed health decisions.

- **Exercise Tracking**: Users can track their workout progress and view their exercise history, enabling them to stay motivated and monitor their improvement over time.

- **User-friendly Interface**: The app is designed with a clean and intuitive user interface to ensure a smooth and enjoyable user experience.

## Getting Started

To get started with the 7MinutesWorkout app, follow these steps:

1. Clone the repository to your local machine.
2. Open the project using Android Studio.
3. Ensure you have the required dependencies specified in the `build.gradle` file.
4. Build and run the app on an Android emulator or physical device.

## Usage

Upon launching the app, users will be presented with the main screen containing the 7 minutes workout routine. Users can start the workout and follow the instructions for each exercise.

To use the BMI feature, navigate to the BMI calculator section of the app. Input your height and weight, and the app will calculate and display your BMI.

Users can also explore the exercise tracking feature by accessing the history section, where their workout progress and exercise history will be available.

## Contributing

Contributions to the 7MinutesWorkout app are welcome! If you find any issues or have suggestions for improvements, feel free to open a new issue or create a pull request. Please ensure that your contributions align with the project's coding standards and guidelines.

## License

The 7MinutesWorkout app is distributed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the app as per the terms of the license.
