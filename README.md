# ContestFlow

A full-stack competition platform built as part of a Full Stack Development Internship technical assignment.

## Technology

- React Native / Expo
- Node.js
- Express.js
- TypeScript
- MongoDB *(to be introduced in a later phase)*

## Project Structure

```
contestflow/
+-- mobile/     # React Native (Expo) application
+-- server/     # Node.js + Express.js backend
+-- .env.example
+-- .gitignore
```

## Local Setup

### Prerequisites

- Node.js >= 18
- npm or yarn
- Expo CLI: `npm install -g expo-cli`

---

### Backend

```bash
cd server
npm install
npm run dev
```

The server starts on http://localhost:5000 by default.

Health check: GET http://localhost:5000/api/health

---

### Mobile

```bash
cd mobile
npm install
npx expo start
```

Scan the QR code with the Expo Go app, or press i for iOS simulator /  for Android emulator.
