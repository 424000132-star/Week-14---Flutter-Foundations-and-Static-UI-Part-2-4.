# Week 14: Flutter Foundations & Static UI (Part 2)

## Project Description
This project is a static mobile application interface called **FoodToGo**, developed using Flutter and Dart.

It contains two related mobile screens designed to demonstrate Flutter widget composition, layouts, image assets, sizing, spacing, and consistent visual styling.

## Screens

### 1. FoodToGo Home Screen
- Displays a welcome message and heading.
- Includes a search bar.
- Shows food categories.
- Displays a special offer banner.
- Shows popular food items.

### 2. Food Details Screen
- Displays a food image.
- Shows the food name, price, and rating.
- Includes preparation time and description.
- Displays ingredients.
- Includes a static Add to Cart button design.

## Flutter Concepts Used
- MaterialApp and ThemeData
- StatelessWidget
- Scaffold
- Row and Column
- Container and Padding
- Stack and Positioned
- Expanded and SizedBox
- Image.asset()
- Local image assets
- Text and Icon widgets

## Project Structure
```text
lib/
├── main.dart
└── screens/
    ├── home_screen.dart
    └── food_details_screen.dart

assets/
└── images/
    ├── burger.jpg
    └── pizza.jpg

pubspec.yaml
README.md
```

## How to Run the Project

1. Clone this repository.
2. Open the project folder in VS Code.
3. Open the terminal.
4. Install the dependencies:

```bash
flutter pub get
```

5. Run the application:

```bash
flutter run -d chrome
```

## Project Information
- **Project:** FoodToGo
- **Activity:** Week 14 – Flutter Foundations & Static UI (Part 2)
- **Student:** Raniel Piollo A. Camarador
- **Section:** BSIT 2.1
- **College:** The National Teachers College

## Note
This project focuses on static UI design. Buttons and other visual elements are for display purposes only. No functional navigation or interaction is implemented.