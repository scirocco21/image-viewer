# image-viewer
React Native app that lets users search for images, displays thumbnails in a grid list, and a detailed view of individual selected images

## Installation
1. Clone the repository to your local machine
2. Run `npm install` to install all dependencies in package.json
3. Create a new `env.js` file in the root folder of the app.
4. Configure `env.js` (see step above) with your own api key from pixabay.com and any api specific variables you want to include. Here is an example configuration:
   `export const env = {
    API_KEY: {YOUR_KEY},
    BASE_URL: 'https://pixabay.com/api/',
    apiKeyPrepend: '?key=',
    queryPrePend: '&q='
  }`
 5. Add `env.js` to your gitignore file
 6. Run `react-native run-ios` or `react-native run-android`
 
 ## Screenshots
 ### ios
 ![](/screenshots/ios/ios-1.png)
 ![](/screenshots/ios/ios-2.png)
 ![](/screenshots/ios/ios-3.png)
 ![](/screenshots/ios/ios-4.png)

 ### Android
 ![](/screenshots/Android/android-1.png)
 ![](/screenshots/Android/android-2.png)
 ![](/screenshots/Android/android-3.png)
 ![](/screenshots/Android/android-4.png)

