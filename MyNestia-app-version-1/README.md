# MyNestia (Expo React Native)

A working MVP prototype implementing the page-by-page requirements:
- Splash, Onboarding, Auth (Sign up / Login), Profile Setup
- Home/Dashboard, House Search + Detail
- Find My Roommate (compatibility scoring), Roommate profile
- Chat (local-only), Post House, Post Roommate Requirement
- ID Verification (prototype), Saved, Profile, Settings

## Prerequisites
- Node.js 18+
- Expo CLI (optional) – `npm i -g expo`

## Run (fastest)
```bash
npm install
npm run start
```
Then scan the QR in **Expo Go** (Android/iOS) or run:
```bash
npm run android
```

## Build an installable APK (Android)
This repo is an Expo project. For a real installable APK you’ll typically use:
- **EAS Build (recommended)**: https://docs.expo.dev/build/introduction/

High level:
```bash
npm i -g eas-cli
eas build -p android --profile preview
```

> Note: EAS builds happen in Expo’s cloud, not locally by default.

## Where to edit
- `src/screens/*` for screens
- `src/mock/data.ts` for sample data
- `src/storage.ts` for local storage
