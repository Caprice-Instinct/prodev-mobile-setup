# First Mobile App - prodev-mobile-app-0x00

## Project Setup Steps

### 1. Project Initialization
```bash
cd prodev-mobile-setup
mkdir prodev-mobile-app-0x00
cd prodev-mobile-app-0x00
npx create-expo-app@latest .
```

### 2. Home Screen Modification
- Opened `app/(tabs)/index.tsx`
- Located the default text "Welcome!"
- Changed it to "** First App Created**"

### 3. Application Testing
```bash
npx expo start
```
- For iOS: Scan QR code with Camera app
- For Android: Scan QR code with Expo Go app

### 4. Project Reset
```bash
npm run reset-project
```

## Observations from reset-project Command

When running `npm run reset-project`, the following changes occurred:

1. **Original app directory moved**: The existing `app/` directory with all its complex structure (tabs, components, etc.) was moved to `app-example/`

2. **New simplified app directory created**: A fresh, minimal `app/` directory was created with:
   - `_layout.tsx` - Root layout file
   - `index.tsx` - Simple entry screen with basic React Native components

3. **File structure transformation**:
   - **Before reset**: Complex tab-based navigation with multiple screens, themed components, and advanced features
   - **After reset**: Clean slate with minimal boilerplate code

4. **Preserved files**: All original complex code is preserved in `app-example/` for reference

5. **Benefits of reset**:
   - Provides a clean starting point for development
   - Removes template complexity
   - Keeps original template as reference in `app-example/`
   - Maintains all project configuration and dependencies

The reset command essentially gives you a fresh start while preserving the original template structure for learning and reference purposes.