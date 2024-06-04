# Macquarie University School of Computing Pathway Finder

Welcome to the Macquarie University School of Computing Pathway Finder website project! This web application is designed to assist students in finding their preferred major by answering a series of questions. The results guide users towards a major that best fits their interests and skills.

## Project Overview

This project is built using Flutter and is designed to be responsive across various devices. It features a multi-page layout that includes question screens, results screens, and additional informational content about the majors offered at Macquarie University.

## Getting Started

### Prerequisites

- Flutter SDK
- Dart
- Any IDE with Flutter support (e.g., Android Studio, VS Code)

### Installation
```bash
git clone https://github.com/FSEpace/MSCPF.git
flutter pub get
flutter run
```   


## Project Structure

- **Main Entry point (main.dart):** Describes the initial setup and entry point of the application, including main configurations, theme settings, and root widgets.
- **Screen Components:**
- `app_home_screen.dart`: Overview of the home screen, including main features, navigation elements, and key widgets.
- `app_credit_screen.dart`: Details the purpose and elements of the credit screen, such as author information or app version.
- `app_questions_screen.dart`: Explanation of the layout and logic for presenting questions to the user.
- `information_screen.dart`: Description of the information screen, which might include help or tutorial content.
- `results_screen.dart`: Explains how results are calculated, displayed, and what user interactions are possible.
- `final_screen_decider.dart`: Logic used to determine what final screen to show based on user actions or results.
- **Responsive Layout:**
- `mobile_layout.dart`, `tablet_layout.dart`, `laptop_layout.dart`: Descriptions of how the app's UI adapts to different device types.
- `responsive_layout.dart`: General logic and techniques used to make the app responsive across varied screen sizes.

## Components and Functionality

- **UI Components:**
- `app_answer_button.dart`: Details on the implementation of answer buttons within quizzes, including any special interaction effects or logic.
- **Utilities:**
- `constants.dart`: List and explain the constants used across the app for things like color schemes, font sizes, and padding.

## Additional Features

- **Tie Breaker:**
- `tie_breaker_layout.dart`: Discusses the conditions under which a tie breaker is needed and the layout/logic of how ties are resolved.

## Building and Running the App

- **Dependencies:** All dependencies are available in the pubspec.yaml file.
- **Running Locally:** Make sure to run `flutter pub get` before running the code. The website is runnable on Android, iOS, and Web.

## Testing

- **Unit/Widget/Integration:** All tests are available under the `test` folder. Tests include widget, unit, and integration tests. To run these tests, open the terminal in VS Code or Android Studio, and execute the following command:

```bash
flutter test
```

Wait for the results of the testing.

## Future Considerations

- **Potential Improvements:** The state file `lib/models/state.dart` might be able to take some improvement in the future especially when selecting/sorting/accessing keys/majors.
- **Known Issues:** At the moment of writing this manual, no bugs have been identified in the code.

## Website

**Website URL:** [Please click on this link to visit the website](https://mscpf-16ea7.web.app).

## Appendices

For any enquiries or questions regarding the codebase overall, please do not hesitate to contact:
- Majd Issa
- Email: issamajd00@gmail.com
- Phone Number: +61 411 911 174.
