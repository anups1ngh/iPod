# Reactive Pod
![Dev Complete](https://img.shields.io/badge/Dev-Complete-brightgreen)

![iPod Image](./music.png =200x200)

A Virtual iPod using React JS.

## Tools Used
![Firebase](https://miro.medium.com/max/1024/1*oT_l6QxMdTN65-0gwFqeNg.png)
![React JS](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1200px-React-icon.svg.png)

- Firebase cloud storage (to store songs).
- React JS

## Features
1. Rotation-On simulation. (Device rotates and so does screen and buttons).
2. Firebase Storage is used. Songs are streamed from Google's high-speed Firebase Storage.
3. Instructions are mentioned on the screen. No room for any type of confusion.
4. Action buttons light up when a song is being played.
5. Lightning-fast React JS-based app.
6. More songs can be added to the database with small changes here and there in the code. (Currently 6 songs for illustration)
7. Swipe Enabled, i.e. One can swipe through the 4 buttons given in the circular portion to navigate through the menu.
8. Songs can be switched without going to the All Songs screen again and again. (using the left and right arrow buttons provided in the Circular Actions Button Section).

## How to use?
1. In the group of circular action buttons section (See the screenshots), the upper-most button is the menu button. left and right buttons are navigation buttons(to navigate in All songs only). The bottom-most button is the Play/Pause button to stop or play the current song.
2. To navigate in the menu, just swipe clockwise if you want to select an item which is available below the currently selected item. And similarly, swipe anti-clockwise if you want to select an item which is available above the currently selected item.
3. Go to All Songs in the Music Section to view a list of all songs available currently on the Cloud Storage. (Make sure you are connected to the internet).
4. To play a song click the "Select" button. Also to select a section from the list of Sections in the menu, press "Select Button".
5. To change a song while another one is being played, click on the left or right arrow buttons and click on the Play/Pause button on the bottom.
6. To rotate the screen, press the small circular button with `Rotation` symbol on the right mid on the app.
7. Songs can be found in the Music/All Songs Section. All other pages are dummy pages for illustration purposes.

## Video Demo
<video width="320" height="240" controls>
  <source src="./myiPod.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

## IMPORTANT:
> An API Key is used to access the Firebase storage, which is in the `SRC/index.js` as `process.env.REACTIVE_POD_API_KEY`. It is intentionally hidden for security purposes. You may have to use your own Firebase Storage to edit and test the code on your system.

## Known Bugs:
1. Changing lights in the circular buttons section stays ON even when the song has finished playing.

**ENJOY :)**

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified, and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
