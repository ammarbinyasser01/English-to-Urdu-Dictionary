# English-Urdu Dictionary

A Flutter-based bilingual dictionary application that helps users quickly find English words, view their Urdu meanings, and listen to accurate pronunciations. The application is designed with a simple and user-friendly interface to make vocabulary learning and language reference more convenient.

## Features

* Search English words instantly
* Auto-complete suggestions while typing
* Browse a scrollable list of words
* View detailed Urdu meanings
* English pronunciation using Text-to-Speech
* Urdu pronunciation using Text-to-Speech
* Clean and intuitive user interface
* Offline dictionary access

## Technologies Used

* Flutter
* Dart
* flutter_tts
* JSON Data Storage

## Project Structure

```text
lib/
├── main.dart
├── detail_screen.dart
└── db_helper.dart

assets/
└── dictionary.json
```

## Installation

### Prerequisites

* Flutter SDK
* Visual Studio Code or Android Studio

### Setup

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Open the project folder.

3. Install dependencies:

```bash
flutter pub get
```

4. Run the application:

```bash
flutter run
```

## How It Works

1. The application loads dictionary data from a local JSON file.
2. Users can search for English words using the search bar.
3. Matching suggestions appear automatically while typing.
4. Selecting a word displays its Urdu meaning.
5. Users can listen to both English and Urdu pronunciations using built-in text-to-speech functionality.

## Future Improvements

* Urdu to English translation
* Favorite words feature
* SQLite database integration
* Voice search
* Custom pronunciation settings
* Improved animations and UI enhancements
