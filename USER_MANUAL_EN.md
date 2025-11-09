# ParrotTranslator User Manual

[日本語のドキュメント](USER_MANUAL.md)

## Table of Contents

1. [Overview](#overview)
2. [How to Use](#how-to-use)
3. [Settings](#settings)
4. [Learning History](#learning-history)
5. [About the App](#about-the-app)

---

## Overview

ParrotTranslator is an application that supports language learning through voice interaction. It translates what you say in your native language into your target language and helps you practice pronunciation.

### Key Features

- **Real-time Speech Recognition**: Recognizes voice input in your native language
- **Automatic Translation**: Translates recognized content into your target language
- **Pronunciation Practice**: Plays translation results aloud for pronunciation practice
- **Pronunciation Evaluation**: Evaluates your pronunciation and displays similarity score
- **Voice Commands**: Hands-free operation
- **Learning History Tracking**: Tracks your learning progress

---

## How to Use

### Basic Flow

#### Step 1: Speak in Your Native Language

Tap the microphone button and speak in your native language. Speech recognition will automatically start and convert your words into text.

#### Step 2: Listen to the Translation

The recognized text is automatically translated into your target language. The translation result will be played aloud so you can learn the correct pronunciation.

#### Step 3: Pronounce

Try pronouncing the translated content yourself. The app will recognize your pronunciation and compare it with the original translation result.

#### Step 4: Check Results and Use Voice Commands

The similarity score of your pronunciation will be displayed. You can use voice commands to select the next action:

- **Next**: Proceed to the next practice
- **Again**: Practice the same phrase again
- **Finish**: End the practice session

---

## Settings

The Settings screen allows you to customize the app's behavior.

### System Settings

#### Color Scheme
- **System**: Follow OS settings
- **Light**: Light theme
- **Dark**: Dark theme

#### App Language
- **English**: Display UI in English
- **日本語**: Display UI in Japanese

#### On-Device Recognition
Set whether to perform speech recognition on the device. When enabled, you can use the app without an internet connection, but recognition accuracy may be slightly reduced.

### Language Settings

#### Native Language
Select the language you speak.

#### Target Language
Select the language you want to learn.

#### Language Model Management
Download or delete language models used for speech recognition. If you want to use the app offline, download the necessary language models in advance.

### Voice Settings

#### Speaker
Select the voice to read the translation results aloud.

#### Speech Rate
Adjust the playback speed of the voice (0.3 to 1.0).
- **Slow (0.3)**: When you want to check pronunciation slowly
- **Fast (1.0)**: When you want to practice at native speed

### Sound Effects Settings

#### Sound Effects Volume
Adjust the volume of sound effects in the app (0% to 100%).

### Pronunciation Evaluation Settings

#### Similarity Threshold
Set the minimum similarity required for pronunciation to be considered correct (50% to 100%).

- **50%**: Lenient evaluation (for beginners)
- **100%**: Strict evaluation (for advanced learners)

### Advanced Settings

#### Speech Recognition Timeout
Set the time from when voice input stops until recognition ends (1.0 to 10.0 seconds).

#### Recognition Start Timeout
Set the maximum time to wait for voice input (10 to 60 seconds). If no voice is detected within this time, recognition will automatically end.

### Voice Command Settings

#### Voice Command Language
Select the language used for voice command recognition.

#### Command Settings
You can customize the following commands:
- **Next**: Default "Next"
- **Again**: Default "Again"
- **Finish**: Default "Finish"

#### Command Similarity Threshold
Set the minimum similarity required for recognition as a voice command (0% to 100%).

### Information

#### How to Use
Display the app's usage guide.

#### About the App
Display app version information, developer information, and license information.

#### Privacy Policy
Display the privacy policy.

#### Check for Updates
Check if a new version is available on the App Store.

### Reset Settings

Tap the "Reset to Default" button to restore all settings to their initial values.

---

## Learning History

The Learning History screen allows you to review past practice records.

### Viewing History

Each history entry displays the following information:
- **Date and Time**: When you practiced
- **Original Text**: What you said in your native language
- **Translation Result**: Content translated into your target language
- **Pronunciation Result**: Your pronunciation
- **Similarity**: Pronunciation accuracy

### History Operations

#### Retry
Select a specific entry from the history to practice again.

#### Statistics
View learning statistics:
- **Success Rate**: Success rate of pronunciation practice (displayed in a pie chart)
- **Total Practice Count**: Number of practices so far
- **Successful Count**: Number of successful practices
- **Failed Count**: Number of failed practices

#### Delete History
- **Individual Delete**: Swipe to delete individual history entries
- **Delete All**: Select "Delete All" from the menu

---

## About the App

### Version Information

The current app version and build number are displayed.

### App Description

ParrotTranslator is a language learning support application that leverages speech recognition and machine translation. It supports efficient language learning through translation from your native language to your target language and pronunciation practice.

### Developer Information

Information about the app developer and development team.

### License Information

License terms for ParrotTranslator.

### Third-Party Licenses

License information for the following third-party technologies used in the app:
- **Apple Speech Framework**: Speech recognition
- **Apple Translation Framework**: Machine translation
- **Apple AVFoundation**: Audio playback

---

## Troubleshooting

### Speech Recognition Not Working

1. Check microphone access permission
2. If on-device recognition is enabled, verify that the corresponding language model is downloaded
3. Check the recognition start timeout setting

### Translation Not Working

1. Verify that the selected language pair is a translatable combination
2. If using online translation, check your internet connection

### Audio Not Playing

1. Check device volume settings
2. Check sound effects volume settings
3. Verify that a speaker is available for the selected language

### Pronunciation Evaluation Too Strict/Lenient

Adjust the "Similarity Threshold" in the Settings screen. For beginners, we recommend setting it lower (50% to 70%), and for advanced learners, setting it higher (80% to 100%).

---

**Last Updated**: November 8, 2025
