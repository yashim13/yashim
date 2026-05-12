# CMP Git Assignment — Yashim

Calculator app submission using the Expo framework.

---

### Setup

```sh
npm install && npx expo start
```

---

### About

Built for the Git assignment in our Computer Science module. The app implements a standard calculator with operators (+, -, *, /) and handles edge cases like repeated operators and decimal points.

The UI uses an emerald green theme in both light and dark modes. Buttons are styled with platform-specific shadows (elevation on Android, boxShadow on web).

### File Structure

```
app/          → screens and routing
components/   → Calculator, ThemedText, ThemedView etc.
constants/    → colour theme definitions
hooks/        → colour scheme detection
```
