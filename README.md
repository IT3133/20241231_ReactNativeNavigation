<h1>React Native Navigation Practice</h1>

This project is a simple demonstration of <strong>React Navigation</strong> in React Native. It covers the basic functionality of navigating between screens, using different navigators, and integrating various UI components with the help of <strong>React Navigation</strong> .

<h2>Project Overview</h2>

This project is built to practice and demonstrate the usage of <strong> React Navigation</strong>  in a React Native application. The app consists of different screens that users can navigate through using various navigation techniques, such as stack, tab, and drawer navigation. It also integrates UI components from <strong> React Native Paper</strong>  for styling.

<h2>Features</h2>
<strong>Basic Navigation</strong>: Set up basic stack navigation for moving between screens.</br>
<strong>About Us Page</strong>: A page containing information about the University of Vavuniya.</br>
<strong>Button Navigation</strong>: Buttons to navigate to different screens and perform actions like "Go to Home", "Go to Top Screen", etc.</br>
<strong>React Native Paper</strong>: Usage of the React Native Paper UI component library for styling and components such as buttons, texts, and dividers.</br>

<h2>Technologies Used</h2>

<strong>React Native</strong>: A framework for building native mobile apps using JavaScript and React.</br>
<strong>React Navigation</strong>: A popular library for navigating between screens in React Native applications.</br>
<strong>React Native Paper</strong>: A Material Design component library for React Native.</br>
<strong>Expo</strong>: A toolchain that simplifies building and deploying React Native apps.</br>

<h2>Installation</h2>

To get started with this project, you need to clone the repository and install the required dependencies.

<h2>Clone the repository</h2>

```bash
git clone https://github.com/your-username/react-native-navigation-practice.git
```

<h2>Navigate to the project directory</h2>

```bash
cd react-native-navigation-practice
```

<h2>Install dependencies</h2>

Make sure you have Node.js and npm installed, then run:

```bash
npm install
```

<h2>Run the project</h2>

For <strong>Android</strong>:

```bash
npx expo start --android
```

For <strong>iOS</strong>:

```bash
npx expo start --ios
```

For <strong>Web</strong>:

```bash
npx expo start --web
```

<h2>Screens</h2>

1. <strong>Home Screen</strong>: The initial screen of the app, where users can navigate to different sections.</br>

2. <strong>About Us</strong>: Information about the University of Vavuniya with historical details and the university's goals.</br>
3. <strong>Navigation Buttons</strong>: Buttons that allow users to navigate between the different screens.</br>

<h2>About Us Page</h2>

The <strong>About Us</strong> page provides detailed information about the University of Vavuniya. The page is styled with components from <strong>React Native Paper</strong>.

- Displays the university’s history, faculty details, and goals.
- The page is scrollable, and an image of the university logo is displayed.
- Navigation buttons are provided for users to go back to the home screen or navigate to the top of the app.



<h2> Home Screen </h2>

The Home Screen is the first screen that appears when the app is launched. It contains basic navigation buttons to access the About Us page or other sections.

<h2>Navigation Implementation</h2>

<h2>Stack Navigator</h2>

The core of the navigation is handled by <strong>React Navigation's Stack Navigator</strong>. The stack navigator allows users to push new screens onto the stack and navigate back through the stack.

<h2>Example</h2>

The main app component sets up the Stack Navigator and defines routes to the Home and About Us screens.
<h2>Outputs</h2>
![HomePage2](https://github.com/user-attachments/assets/63487199-8da3-4eac-a238-c015d17b31cc)

<h2>License</h2>

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

