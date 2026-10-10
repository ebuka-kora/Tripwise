# Tripwise

A travel planning mobile app built with React Native and Expo. Tripwise helps you find a destination, plan a trip with friends and see what it will cost before you go.

## Features

- **Onboarding** that sets up the app around how you like to travel
- **Discover** destinations and browse results that match what you're looking for
- **Group trip planner** for organising a trip with other people
- **Trip cost breakdown** so everyone knows what the trip will cost
- **Trip history** of past and planned trips
- **Rewards** for travelling with Tripwise
- **Emergency support** when something goes wrong on the road

## Tech stack

- React Native 0.79 and Expo 53
- TypeScript
- React Navigation (bottom tabs and native stack)
- Runs on iOS, Android and the web (React Native Web)

## Project structure

```
src/
  components/   Shared UI: Button, Card, Input
  constants/    Colours, sizes and other app-wide values
  navigation/   Tab and stack navigators
  screens/      One file per screen
  services/     Data layer (currently mock data)
  types/        Shared TypeScript types
```

## Running it

```bash
npm install
npm start          # then press i for iOS, a for Android or w for web
```

You need Node.js and the Expo Go app on your phone, or an iOS/Android simulator.
