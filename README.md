# iSchool Rankings App

For this project you will build an app that shows totally accurate, up to the date global rankings for iSchools all over the world. Well, maybe not exactly. In fact what it will do is always show the University of Michigan School of Information in first place and all of the rest of the iSchools in random order from 2nd place on downward. So it might be a bit biased.

See the demo video for how the app should look and behave when you are done.

To help you out, I have provided two JavaScript files containing functions that you will need to `import` (using the JavaScript `import` statement) for use in your App.js. I have also created a default "blank" expo app for you to modify. Here are the steps you need to take to get set up to start working on the project:

1. Accept the GitHub invitation to get your personal copy of the project repository (if you're reading this, you've already done step 1!)
2. Clone the repo to your development machine.
3. Change the `default export` in your App.js to export a class Component rather than a function Component.
4. Figure out how you will use the exported functions from `Shuffle.js` and `iSchoolData.js` in your app, and set up your imports accordingly.
5. Write your app!

Notes:
- Make sure that the top-ranked iSchool is displayed as part of the list that contains all of the other schools. It should scroll with the other schools, for example.
- The icon I used for the refresh button is the 'ios-refresh' icon from Ionicons. This is included with expo. To learn about using icons in Expo read the [Expo Icon Guide](https://docs.expo.io/guides/icons/). You can also use a different icon if you find one you like better.
- You can tweak the styles and colors if you like, but make sure that all style-related requirements are met for full credit.
- To get the "Updated" time and date to display correctly, you may need to refer to the [JavaScript Date docs](https://www.w3schools.com/jsref/jsref_obj_date.asp), particularly the [docs for Date.toLocaleString()](https://www.w3schools.com/jsref/jsref_tolocalestring.asp)

# Project 1: iSchool Rankings
### Resources
* Demo: https://www.loom.com/share/e14fccc04feb4574bb91d8ca769f0d4a (Links to an external site.)
* GitHub Classroom invitation:  https://classroom.github.com/a/yUz2XMlN (Links to an external site.)
* iSchoolData module
* Shuffle modulePreview the document

### Descriptionn
In this project you will create an app from scratch that displays totally accurate, up to the minute global rankings of Information Schools. Given that there is no established set of criteria or definitive ranking system for iSchools, we will create our own (admittedly biased) ranking system according to the following rules:

The University of Michigan iSchool is always first.
All other iSchools are randomly ranked 2-n (where n is the total number of iSchools).
You should try to make your app look as similar to the app shown in the demo video as possible. When the user clicks the "Refresh" button, a new set of rankings are generated and displayed according to the rules described above.

Here are some pointers to help you on your journey:
* I have provided a module (`iSchoolData.js`) that contains the names and institutions of the current set of iSchools. The module exports a function that you can use to get a properly structured list of the iSchools for attaching to a React Native FlatList.
* I have provided a module (`Shuffle.js`) that implements a function for shuffling an array.
* For the refresh icon used in the button I used [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) (Links to an external site.). You can use a different icon or image. For full credit you'll need to figure out how to use some kind of icon or image here.
* For full credit, you will need to define a custom component (your own class that extends React.Component) to display each iSchool's information in the list.
* To correctly render the "Updated: ..." label in the header, you will need to do some research on working with Date objects in JavaScript (the example shown here is not doing anything particularly tricky. toLocaleString() will be your friend here).
* You may need to look into the documentation for the React Native Text component to get long strings to render as shown in the demo video (i.e., using ... to truncate strings that don't fit in the display).

### Getting Started
* Create a new expo project.
Copy the provided iSchoolData and Shuffle modules into your project directory.
* Use the git repo that is created when you create an expo project and add/commit your project files (including the provided modules) to it.
* Accept the GitHub Classroom invitation, which will create a blank repository. DON'T ADD A README.
Follow the instructions for pushing an existing repo from the command line to push your project files to the new repo.

### What to Turn In
1. Keep pushing your code to GitHub as you work.
2. Push your final version to GitHub when you are done. Your most recent commit will be used to determine when you turned the project in for the purposes of calculating a late penalty (if any).
3. When you are done, make a screencast video of your app in action and submit your video's URL to Canvas (this assignment). You will need to post your video somewhere on the web (you can use Google Drive,  Box, etc. and restrict access to umich if you don't want to worry about sharing too widely). I've added some information about making screencasts and also about installing iOS simulators/Android emulators to the Resources section of the Course Schedule (Links to an external site.).

### Grading
| User Story | Points |
| --- | ------------- |
| User sees a ranked list of iSchools is displayed when the app runs | 20 |
| User sees a shuffled list of ranked iSchools when they  press the refresh button |	20 |
| User always sees the University of Michigan iSchool as the number one school and other schools are listed in random order	| 10 |
| User sees an app header that looks similar to the one in the demo video | 10 |
| User sees an updated date and time in the header every time the refresh button is pressed | 5 |
| User sees a list of ranked iSchools similar to the one in the demo video, with or without truncation for long names |	10 |
| User sees long names truncated using ellipses (...) in the list of iSchools |	5 |
| Code correctly imports and uses the provided iSchoolData and Shuffle modules | 10 |
| Code correctly implements and uses a custom Component for displaying list items |	10 |
| Total Points | 100 |
| Demo video is missing	| -10 |