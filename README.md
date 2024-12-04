# Pocket-Tutor
App dev for the project Pocket-Tutor

Original project: https://github.com/Millenium-Falcons/Pocket-Tutor


A React Native application template.

## Overview
Pocket-Tutor is a React Native application template designed to help developers quickly set up and start building mobile applications. This template includes essential configurations and components to streamline the development process based off on an education app.

## Features
- Pre-configured React Native setup
- TypeScript support
- Essential components and utilities
- Easy-to-follow project structure

## Project Structure
The project is organized as follows:
- `components/`: Contains reusable UI components such as `VideoCard`, `FormField`, `CustomButton`, `InfoBox`, `Loader`, `Trending`, `SearchInput`, and `EmptyState`.
- `app/`: Contains the main application logic and screens, including authentication screens (`sign-in` and `sign-up`), and other pages like `profile`.
- `constants/`: Stores constants used throughout the project, such as images and theme colors.
- `context/`: Contains the global context provider to manage the application's state.

## Key Components and Features
1. **VideoCard**: Display video thumbnails and details.
2. **FormField**: Reusable form input fields with validation.
3. **CustomButton**: Customizable buttons used throughout the app.
4. **InfoBox**: Display informational messages or alerts.
5. **Loader**: Loading spinner animation.
6. **Trending**: Display trending items or content.
7. **SearchInput**: Search bar component.
8. **EmptyState**: Display a message when there is no content to show.

## Configuration and Setup
To get started with Pocket-Tutor, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/ImonChakraborty/Pocket-Tutor.git
   ```
2. Navigate to the project directory:
   ```
   cd Pocket-Tutor
   ```
3. Install the dependencies:
   ```
   npm install
   ```
4. Run the application:
   ```
   npm start
   ```

## Usage
After installing and running the application, you can start building your mobile app using the provided template. Modify the components and configurations as needed to suit your project requirements.

### Example Usage
- To create a new screen, add a new file in the `app` directory and define your screen component.
- Use the existing components from the `components` directory to build your UI.

```javascript
import { View, Text } from 'react-native';
import { CustomButton } from '../components';

const NewScreen = () => (
  <View>
    <Text>Welcome to the new screen!</Text>
    <CustomButton title="Click Me" handlePress={() => alert('Button clicked!')} />
  </View>
);

export default NewScreen;
```

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
