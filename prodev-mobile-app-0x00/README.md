# First Mobile App - Expo Router Project

This is my first mobile application created using the Expo Router template as part of the mobile development learning journey.

## Project Setup Steps

### 1. Project Scaffolding
Followed these steps to create the mobile app:

1. **Navigate to Project Directory**
   ```bash
   cd prodev-mobile-setup
   ```

2. **Initialize Expo Project**
   ```bash
   npx create-expo-app@latest .
   ```
   This command created a new Expo project using the latest Expo Router template.

3. **Modify Home Screen**
   - Opened `app/(tabs)/index.tsx`
   - Changed the default "Welcome!" text to "First App Created"

4. **Run the Application**
   ```bash
   npx expo start
   ```
   - For iOS: Scan QR code with Camera app
   - For Android: Scan QR code with Expo Go app

### 2. Reset Project Observations

When running `npm run reset-project`, the following happens:
- The current `app` directory (containing all the starter code and components) gets moved to `app-example`
- A new blank `app` directory is created for fresh development
- This allows developers to start with a clean slate while preserving the original template as reference
- All the existing components, screens, and styling examples are preserved in `app-example` for learning purposes

## Project Structure

The Expo Router template includes:
- **app/(tabs)/** - Tab-based navigation screens
- **components/** - Reusable UI components
- **assets/** - Images, fonts, and other static resources
- **constants/** - App-wide constants and configurations

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction/).

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.