# React Native E-commerce UI App

The Shopping App is a simple e-commerce application that allows users to browse products, add them to a cart, and proceed to checkout. The app includes essential features such as product display, navigation, cart summary, and persistent storage.

## Features

**Display products**: Products are displayed in a grid layout on the Home screen.
**Navigation**: Users can navigate to the Checkout screen from the Home screen.
**Cart Summary**: The Checkout screen shows the list of selected products and their total cost.
**Bottom Tab Navigation**: For easy access to the Checkout screen.
**Persistent Storage**: Utilizes AsyncStorage to store selected items locally on the device.
  - Products added to the cart are stored persistently using AsyncStorage.
  - Upon app restart, previously selected items are retrieved from AsyncStorage and displayed in the CartScreen.



## Installation

1. **Clone the repository**:   ```   git clone https://github.com/doreen09/rn-assignment6-11210385.git   ```
2. **Install dependencies**:   ```   cd rn-assignment6-11210385/MarkApp   npm install   ```
3. **Start the development server**:   ```   expo start   ```
4. **Run the app on your device or emulator**:   - For iOS, press `i` to launch the iOS simulator.   - For Android, press `a` to launch the Android emulator or scan the QR code with the Expo Go app on your Android device.

## Usage

1. **Run the app on an Android or iOS device**:
   - Use the Expo Go app to scan the QR code displayed in your terminal.

2. **Explore the app**:
   - Browse products on the Home screen.
   - Navigate to the Checkout screen to view the selected products and their total cost.


## Screenshots

- **Home Screen**
  - Home screen
![Home Screen](MarkApp/assets/home.png)

- **Checkout Screen**
  - Checkout screen
![Checkout Screen](MarkApp/assets/Checkout.png)

## Technologies Used
React Native
Expo
Redux (for state management)
React Navigation (for routing and navigation)

## Author
**Name:** Doreen Owireduaa Amankwah
**ID:** 11210385