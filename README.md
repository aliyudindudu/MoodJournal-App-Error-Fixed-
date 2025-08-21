# Mood Journal App

A mobile application for tracking your mood, journaling your thoughts, and gaining insights into your emotional patterns.

## Features

- **Daily Journal Entries**: Record your thoughts and feelings through text entries
- **Emotion Detection**: Automatically detects emotions from your journal entries
- **Mood Tracking**: Visualize your mood on a 1-5 scale
- **Weekly Insights**: Get summaries of your most frequent moods and potential triggers
- **Suggested Actions**: Receive personalized suggestions based on your current mood
- **Journaling Prompts**: Get inspiration when you don't know what to write

## Tech Stack

- React Native with Expo
- TypeScript
- React Navigation for routing
- AsyncStorage for local data persistence
- React Native Paper for UI components

## Getting Started

### Prerequisites

- Node.js (v14 or newer)
- npm or yarn
- Expo CLI

### Installation

1. Clone the repository
   ```
   git clone https://github.com/yourusername/mood-journal.git
   cd mood-journal
   ```

2. Install dependencies
   ```
   npm install
   ```
   or
   ```
   yarn install
   ```

3. Start the development server
   ```
   npm start
   ```
   or
   ```
   yarn start
   ```

4. Open the app on your device using the Expo Go app or run it in an emulator

## Project Structure

```
src/
├── assets/         # Images, icons, and other static assets
├── components/     # Reusable UI components
├── context/        # React Context for state management
├── hooks/          # Custom React hooks
├── navigation/     # Navigation configuration
├── screens/        # App screens
├── types/          # TypeScript type definitions
└── utils/          # Utility functions
```

## Core Functionality

### Emotion Detection

The app uses a simple keyword-based approach to detect emotions from journal entries. In a production environment, this could be enhanced with a more sophisticated NLP approach or integration with an emotion analysis API.

### Mood Scoring

Mood is scored on a scale of 1-5:
- 1: Very Negative
- 2: Negative
- 3: Neutral
- 4: Positive
- 5: Very Positive

### Data Storage

All journal entries are stored locally on the device using AsyncStorage. No data is sent to external servers, ensuring privacy.

## Limitations and Disclaimers

- This app is not a replacement for professional mental health care
- The emotion detection is simplified and may not always accurately capture complex emotions
- All insights are generated based on simple pattern recognition and should be viewed as reflective tools, not clinical analysis

## Future Enhancements

- Voice-to-text functionality for journal entries
- Cloud synchronization for backup and multi-device access
- More sophisticated emotion analysis using NLP
- Customizable themes and appearance
- Export functionality for journal entries

## License

This project is licensed under the MIT License - see the LICENSE file for details.