# dinnerd

A frictionless, mobile-first Flutter web app for calculating who owes what on a shared dinner check.

## What it does

dinnerd guides users through splitting a restaurant bill with minimal typing, tapping, and cognitive overhead. It is designed for people who want to:

- avoid signing up or downloading a heavy app
- skip overly complex interfaces
- split a check quickly without wrestling with too many fields
- use a clean, easy-to-follow guided flow on mobile or desktop

## Why it exists

Splitting a check is still annoyingly high-friction. Many existing tools:

- demand downloads, signups, or extra onboarding
- overload users with too many options and inputs
- feel overbuilt for a simple “who owes what” task
- expose cluttered UI that is hard to navigate on small screens
  dinnerd focuses on a lightweight experience that keeps the task simple and fast.

## Technical notes

- UI-only frontend
- Web-first Flutter app
- Progressive Web App (PWA) friendly
- Mobile-first layout with desktop accessibility
- Simple design system, with future polish planned

## Setup

1. Install Flutter from https://flutter.dev
2. From the project root: `flutter pub get`
3. Run the app in a browser: `flutter run -d chrome`
4. Build for web: `flutter build web`
