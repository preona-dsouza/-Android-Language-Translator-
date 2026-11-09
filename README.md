# Android Language Translator

A simple Android application developed in Java that allows users to translate text between supported languages. It also provides speech input using the device's speech recognition feature.

## Features

- Translate text between supported languages.
- Select source and target languages.
- Enter text manually.
- Use speech recognition to enter text.
- Display translated text.

## Technologies Used

- Java
- Android SDK
- Firebase ML Natural Language Translation
- Android Speech Recognizer
- XML

## Supported Languages

English, Afrikaans, Arabic, Belarusian, Bengali, Catalan, Czech, Welsh, Hindi and Urdu.

## Requirements

- Android Studio
- Android SDK
- Firebase project configuration

## Setup

1. Clone or download this repository.
2. Open the project in Android Studio.
3. Register the application in your Firebase project using package name `com.example.translatorapp`.
4. Download the `google-services.json` file.
5. Place it inside the `app/` directory.
6. Sync the project with Gradle and build the application.

Note: The Firebase configuration file is not included in this repository. You must provide your own.

## Permissions

- Internet access for translation services.
- Microphone access for speech input.

## Project Structure

- `app/src/main/java/` – Java application code.
- `app/src/main/res/` – Layouts, images and resources.
- `app/src/main/AndroidManifest.xml` – Application configuration and permissions.
- `gradle/` – Gradle wrapper and version configuration.
