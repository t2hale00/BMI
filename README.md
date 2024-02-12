# Calorie Consumption Calculator App

This Android app, built with Kotlin and Jetpack Compose, allows users to calculate their calorie consumption based on weight, gender, and physical activity level. The final app features a simple and intuitive user interface, making it easy for users to input their information and receive accurate calorie consumption results.

This project is made as part of the Mobile Programming with Natie Technologies course.

## Learning Objectives

The learning objectives of this project include:

- **Divide App and UI into Multiple Composables/Components**: Learn how to organize your app's UI into reusable and manageable components using Jetpack Compose.

- **OutLinedTextField**: Understand how to use the `OutlinedTextField` component to create input fields for users to enter their weight and other information.

- **RadioButton**: Implement radio buttons to allow users to select their gender.

- **DropDownList**: Use a drop-down list to enable users to choose their physical activity level.

- **Hoisting State Up**: Learn how to manage and hoist state up to higher-level composables to ensure data consistency and efficient state management.

- **Support Portrait Mode Only**: Implement the app to support portrait mode only, ensuring a consistent user experience across different devices.

## App Features

- Input fields for weight, gender selection, and physical activity level
- Radio buttons for selecting gender
- Drop-down list for choosing physical activity level
- Calculation of calorie consumption based on user input
- Support for portrait mode only

## Getting Started

To get started with this app, clone the repository and open it in Android Studio. Build and run the app on an emulator or physical device to see the calorie consumption calculator in action.

## Implementation Details

### UI Components

The UI is divided into multiple Jetpack Compose composables/components, including:

- `WeightInput`: Composable for entering weight
- `GenderSelection`: Composable for selecting gender using radio buttons
- `ActivityLevelSelection`: Composable for selecting physical activity level using a drop-down list
- `CalorieCalculator`: Composable for displaying the calculated calorie consumption based on user input

### Portrait Mode Only

The app is designed to support portrait mode only to provide a consistent user experience across different devices. This ensures that the UI layout remains optimized and easy to use on both smartphones and tablets.

