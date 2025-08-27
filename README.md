📱 Shopping App – React Native

This project is a React Native mobile shopping app built with Expo. It uses the FakeStore API
 to fetch product data and allows users to browse products and view detailed information.

🚀 Tech Stack

React Native (Expo for easy development & testing)

React Navigation (Stack Navigator for screen transitions)

FakeStore API for product data

React Native StyleSheet for layout and styling

📦 Installation & Setup

Clone or unzip the project folder

cd question2


Install dependencies

npm install


Start Expo development server

npx expo start


Open the Expo Go app on your mobile device and scan the QR code,
or run on an emulator (npm run android / npm run ios if configured).

🗂️ Project Structure
App.js
screens/
 ├─ HomeScreen.js
 └─ DetailScreen.js


App.js → Entry point with navigation container and stack navigator.

HomeScreen.js → Fetches and displays product list using FlatList.

DetailScreen.js → Fetches and displays details of a selected product.

🔄 Navigation Flow

User starts on HomeScreen → sees product list (image + title).

When a product is tapped → app navigates to DetailScreen.

DetailScreen fetches product by id and displays full info (image, title, price, description).

🎨 Features

Product List → Scrollable list of items with thumbnails and titles.

Detail View → Enlarged image, product title, price, and description.

Navigation → Powered by React Navigation (stack).

Error & Loading Handling → Shows loading indicator or error message when fetching data.
