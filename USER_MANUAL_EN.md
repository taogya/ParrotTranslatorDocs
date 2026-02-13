# ParrotTranslator User Manual

[日本語のドキュメント](USER_MANUAL.md)

## Table of Contents

1. [Overview](#overview)
2. [How to Use](#how-to-use)
3. [Practice Modes](#practice-modes)
4. [Mini Games](#mini-games)
5. [Missions](#missions)
6. [Settings Screen](#settings-screen)
7. [Learning History Screen](#learning-history-screen)
8. [Troubleshooting](#troubleshooting)

---

## Overview

A language learning app using voice. Translate what you say in your native language into your target language and practice pronunciation.

---

## How to Use

### Learning Flow

```
     ┌─────────────────┐
     │   1 Speak       ├──┐
     │  (Native lang)  │  │
     └────────┬────────┘  │
              │           │
              ↓           │
     ┌────────┴────────┐  │
     │  2 Translate    │  │
     │   (Auto)        │  │
     └────────┬────────┘  │
              │           │
              ↓           │
     ┌────────┴────────┐  │
  ┌──┤  3 Listen       │  │
  │  │ (Target lang)   │  │
  │  └────────┬────────┘  │
  │           │           │
  │           ↓           │
  │  ┌────────┴────────┐  │
  │  │ 4 Pronounce     │  │
  │  │ (Repeat)        │  │
  │  └────────┬────────┘  │
  │           │           │
  │           ↓           │
  │  ┌────────┴────────┐  │
  │  │   5 Judge       │  │
  │  │ (OK/Try again)  │  │
  │  └────────┬────────┘  │
  │           │           │
  │  [Again]  │  [Next]   │
  └───────────┤           │
              └───────────┘
```

**📝 Note:** Native and target language selection is done on the screen displayed when starting a learning session.

1. **Speak**: Tap the mic and speak in your native language
2. **Translate**: Automatically translated to learning language
3. **Listen**: Hear the translation pronunciation
4. **Pronounce**: Repeat what you heard
5. **Judge**: Pass if similarity ≥80% (adjustable in settings)

### Voice Commands

Simply speak naturally on the result screen:

| Command          | Action |
| ---------------- | ------ |
| Next / 次        | Next   |
| Again / もう一度 | Retry  |
| Finish / 終わり  | End    |

---

## Practice Modes

### Shuffle Mode

A mode to practice multiple language pairs in random order.

- **Setup**: Add 2 or more language pairs (e.g., JA→EN, JA→FR) and set the number of questions per pair
- **Practice**: Language pairs switch randomly for each question, with standard pronunciation practice
- **Results**: After completion, accuracy and per-pair results are displayed

**📝 Note:** Free/Coffee/Lunch plans are limited to 3 language pairs. Study and above: unlimited.

### Review Mode

A review mode that quizzes you on previously learned phrases.

- **Setup**: Select a language pair and number of questions (5/10/20/30/50, or unlimited depending on plan)
- **Practice**: Phrases from your learning history are presented; listen to the example audio, then pronounce
- **Controls**: After evaluation, use voice commands (Next/Again/Finish) to navigate

### Relearning

Practice individual phrases again from the history screen.

- **How to use**: Tap "Retry" from a history detail, then use the mic button to record and get evaluated
- **Use case**: Great for focused practice on phrases you previously got wrong

---

## Mini Games

Mini games are unlocked by completing [Missions](#missions).

### Reverse Talk

A chat-style game where your recognized speech is translated and played in reverse.

- **How it works**: Tap the mic to speak; your speech is recognized, translated, and shown as a chat bubble. Tap any message to hear it reversed
- **Record & reverse**: You can also record your own voice and play it backwards
- **Reverse modes**: Text reverse (reverses characters and reads aloud) and waveform reverse (reverses the actual audio data)
- **Playback speed**: Adjustable via slider

### Fukuwarai

A game combining the traditional Japanese "Fukuwarai" face game with pronunciation practice.

- **How it works**: A phrase is displayed and read aloud; pronounce it and face parts are placed based on your similarity score
- **Part sets**: 3 types (Bird / Okame / Hyottoko)
- **Completion**: After all parts are placed, your score (average similarity) is shown

**📝 Note:** Requires learning history entries equal to or more than the number of parts.

### Pronunciation Challenge

Phrases from your learning history fall from the top of the screen and you pronounce them to score.

- **How it works**: See a falling phrase card, pronounce it, and get evaluated (OK/NG) by speech recognition
- **Pause**: While paused, tap cards to hear the audio
- **Results**: After completion, OK/NG counts and average similarity are displayed

**📝 Note:** Requires at least 5 learning history entries.

### Game of Life

A Conway's Game of Life (cellular automaton) simulator.

- **How it works**: Tap cells to toggle alive/dead, press play to start the simulation
- **Controls**: Adjust speed, blur, grid size, and time-of-day color theme via sliders

---

## Missions

A system where mini games are unlocked by achieving conditions.

| Mission                 | Unlock Condition            |
| ----------------------- | --------------------------- |
| Game of Life            | Unlocked on first launch    |
| Reverse Talk            | 3 consecutive days of use   |
| Fukuwarai (Bird)        | 10 total learning sessions  |
| Pronunciation Challenge | 50 total learning sessions  |
| Fukuwarai (Okame)       | 100 total learning sessions |
| Fukuwarai (Hyottoko)    | 200 total learning sessions |

**📝 Note:** With the Unlimited plan, all missions are unlocked unconditionally.

---

## Settings Screen

### System Settings

| Item             | Description           |
| ---------------- | --------------------- |
| **Color Scheme** | System / Light / Dark |

**📝 Note:** App display language follows iOS "Preferred Languages" setting.

### Language Settings

| Item                          | Description                                                                                                                |
| ----------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **Language Model Management** | Download/delete language models for speech recognition. Required for offline use. Select native and target languages here. |

### Voice Settings

| Item                     | Description                                                                       |
| ------------------------ | --------------------------------------------------------------------------------- |
| **Speaker**              | Voice type                                                                        |
| **Speech Rate**          | 0.1–1.0 (slower for beginners)<br>※ Free plan: 0.5–1.0. Coffee and above: 0.1–1.0 |
| **Sound Effects Volume** | 0%–100%                                                                           |

### Pronunciation Evaluation

| Item                              | Description                                     |
| --------------------------------- | ----------------------------------------------- |
| **Enable Pronunciation Judgment** | Toggle pronunciation evaluation ON/OFF          |
| **Similarity Threshold**          | 50%–100% (beginners: 50–70%, advanced: 80–100%) |

### Voice Command Settings

| Item                             | Description                                      |
| -------------------------------- | ------------------------------------------------ |
| **Voice Command Language**       | Language for command recognition                 |
| **Next/Again/Finish Commands**   | Customize each command                           |
| **Command Similarity Threshold** | Min similarity for command recognition (0%–100%) |

### Information

- **Subscription Plan**: View and change current plan
- **Missions**: Check mini game unlock conditions
- **How to Use**: Usage guide
- **About the App**: Version, developer, and license info
- **Privacy Policy**: View privacy policy

---

## Learning History Screen

### History Display

Each history entry records:

- Date and time
- Original text (native language)
- Translation result (target language)
- Pronunciation result
- Similarity score

### Operations

| Operation       | Description                                            |
| --------------- | ------------------------------------------------------ |
| **Tap**         | View history details                                   |
| **Retry**       | Practice the same question again                       |
| **★ Button**    | Add/remove from favorites                              |
| **Swipe Left**  | Report issue (report translation/recognition problems) |
| **Swipe Right** | Delete individual history                              |
| **Filter**      | Filter by All / ★ Only / No ★                          |
| **Statistics**  | View success rate and practice count with graphs       |
| **Delete All**  | Delete all history from menu                           |
| **CSV Export**  | Export history as CSV file (Pro and above)             |

**📝 Favorites limit:** Free: 10 / Coffee: 50 / Lunch and above: unlimited

---

## Troubleshooting

| Issue                          | Solution                                                                      |
| ------------------------------ | ----------------------------------------------------------------------------- |
| Speech recognition not working | Check mic permission / Download language model if on-device recognition is ON |
| Translation not working        | Check language pair support / Check internet connection                       |
| No audio                       | Check device volume / Check sound effects volume setting                      |
| Judgment too strict/lenient    | Adjust similarity threshold (50–70% for beginners, 80–100% for advanced)      |

---

**Last Updated**: February 14, 2026
