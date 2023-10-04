# Reactive Pod

[![Dev Complete](https://img.shields.io/badge/Dev-Complete-brightgreen)](https://github.com/yourusername/yourreponame)

A Virtual iPod using React JS. Play(https://anups1ngh.github.io/iPod/)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [How to Use](#how-to-use)
- [Tools Used](#tools-used)
- [Installation](#installation)
- [Configuration](#configuration)
- [Known Bugs](#known-bugs)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Reactive Pod is a virtual iPod application built using React JS. It simulates the experience of using an iPod, complete with rotation-on animation and the ability to play songs streamed from Firebase Cloud Storage. With clear instructions and a user-friendly interface, Reactive Pod offers an enjoyable way to explore music.

## Features

- Realistic Rotation-On simulation for an immersive experience.
- Seamless streaming of songs from Firebase Cloud Storage.
- Clear on-screen instructions to minimize user confusion.
- Dynamic action button lighting when a song is playing.
- High-speed and responsive React JS-based app.
- Easy scalability to add more songs to the database.
- Intuitive swipe navigation for menu selection.
- Quick song switching using on-screen buttons.

## How to Use

1. **Navigation**: In the circular action button section, the top button is for the menu, while the left and right buttons navigate through songs. The bottom button is for Play/Pause.
2. **Menu Selection**: Swipe clockwise to select an item below the current selection and counterclockwise to select an item above.
3. **All Songs**: Visit the Music/All Songs section to see the available songs (internet connection required).
4. **Playing a Song**: Click the "Select" button to play a song. Press the "Select" button in the menu to choose a section.
5. **Song Switching**: Change songs while one is playing using the left or right arrow buttons and the Play/Pause button.
6. **Screen Rotation**: Rotate the screen by pressing the circular button with the `Rotation` symbol.

## Tools Used

Reactive Pod was built using the following tools:

- ![Firebase](https://miro.medium.com/max/1024/1*oT_l6QxMdTN65-0gwFqeNg.png) Firebase Cloud Storage: For storing and streaming songs.
- ![React JS](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1200px-React-icon.svg.png) React JS: For building the app's user interface.

## Installation

To run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/yourreponame.git`
2. Install dependencies: `npm install`
3. Start the development server: `npm start`
4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Configuration

To configure the app for your environment, you will need to set up an API Key for Firebase Cloud Storage. This key should be placed in `SRC/index.js` as `process.env.REACTIVE_POD_API_KEY`. Ensure it is kept secure.

## Known Bugs

1. Changing lights in the circular buttons section may stay ON even when the song has finished playing.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE). Enjoy using Reactive Pod!

---

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

For more information about React and Create React App, please refer to the [React Documentation](https://reactjs.org/) and the [Create React App Documentation](https://facebook.github.io/create-react-app/docs/getting-started).
