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
