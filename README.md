# React Native Server and Client App

This repository contains a React Native application that acts as a server using `react-native-http-server` and handles dynamic permissions using `react-native-permissions`. Additionally, it includes a client application that communicates with the server to fetch data.

## Server Application

### Setup

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Dependencies**:
   - `react-native-device-info`: Fetches device information.
   - `react-native-permissions`: Handles permissions dynamically.
   - `react-native-http-bridge-refurbished`: Sets up an HTTP server within the React Native app.

3. **Permissions**:
   Ensure that the necessary permissions are added in your `AndroidManifest.xml` for Android.

### Running the Server

1. **Start the React Native Server**:
   ```bash
   npx react-native run-android
   # or
   npx react-native run-ios
   ```

## Client Application

### Setup

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Dependencies**:
   - `axios`: Makes HTTP requests to the server.

### Running the Client

1. **Start the React Native Client**:
   ```bash
   npx react-native run-android
   # or
   npx react-native run-ios
   ```

### Communication

- Ensure both the server and client are running on the same network.
- Update the server URL in the client app to match the IP address of the server device.

## Conclusion

This setup demonstrates how to create a React Native server app that dynamically handles permissions and a client app that communicates with the server. You can extend this example to fit your specific requirements.
