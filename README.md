# Hello, universe! 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

   ```bash
   npm install nativewind tailwindcss react-native-animated react-native-safe-area-context
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

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

3. Create an account on Appwrite and save your IDs in a `.env` file as per below:

   EXPO_PUBLIC_MOVIE_API_KEY='YOUR_API_KEY_GOES_HERE'
   EXPO_PUBLIC_APPWRITE_PROJECT_ID='YOUR_PROJECT_ID_GOES_HERE'
   EXPO_PUBLIC_APPWRITE_DATABASE_ID='YOUR_DATABASE_ID_GOES_HERE'
   EXPO_PUBLIC_APPWRITE_COLLECTION_ID='YOUR_COLLECTION_ID_GOES_HERE'

4. Create a collection and call it `metrics`

5. Add the columns below to your collection:

   -> searchTerm
   -> count
   -> poster_url
   -> movie_id
   -> title

6. Make contributions

You can contribute to the project by adding additional tabs and functionality. The `Profile` and `Saved` tabs both have basic styling only.
