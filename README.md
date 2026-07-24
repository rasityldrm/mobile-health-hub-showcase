# Mobile Health Hub

A comprehensive mobile health and wellness application developed with Expo, React Native and TypeScript.

The application brings nutrition tracking, activity monitoring, health management and social sports features together in a single mobile experience.

> The complete source code is maintained in a private repository to protect intellectual property and security-sensitive implementation details.

## Overview

Mobile Health Hub was designed to help users manage their daily wellness activities from one application.

The project includes authentication, nutrition tracking, activity management, social sports rooms, profile and privacy management, and AI-assisted nutrition estimation.

## Key Features

- User registration, login and onboarding
- Personalized home dashboard
- Daily nutrition diary
- Food and barcode search
- Activity and exercise tracking
- Social sports rooms
- Health-focused management modules
- Profile and privacy settings
- Care team management
- AI-assisted photo nutrition estimation
- Local data persistence
- Responsive mobile interface

## Technology Stack

### Mobile

- Expo SDK 54
- React Native
- React 19
- TypeScript
- Expo Router
- NativeWind

### Backend and Services

- Firebase Authentication
- Cloud Firestore
- Firebase Cloud Functions
- AsyncStorage
- OpenFoodFacts API
- OpenAI Responses API

### Development Tools

- npm
- EAS Build
- ESLint
- TypeScript
- Git
- GitHub

## Application Architecture

```mermaid
flowchart TD
    A[Expo Mobile Application] --> B[Firebase Authentication]
    A --> C[Cloud Firestore]
    A --> D[AsyncStorage]
    A --> E[OpenFoodFacts API]
    A --> F[Firebase Cloud Function]
    F --> G[OpenAI Responses API]
