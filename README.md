# Welcome to AXL Companion App


**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Running on Android**

This project includes Capacitor for mobile development. To run the app on Android:

```sh
# Step 1: Build the web app
npm run build

# Step 2: Copy the built web assets to the Android project
npx cap copy android

# Step 3: Sync the Capacitor configuration and plugins
npx cap sync android

# Step 4: Open the Android project in Android Studio
npx cap open android

# Alternative: Run directly on a connected device or emulator
npx cap run android
```

**Prerequisites for Android development:**
- Android Studio installed with Android SDK
- Java Development Kit (JDK) 17 or higher
- Android device or emulator for testing

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
- Capacitor