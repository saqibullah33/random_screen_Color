# Random Color Generator

This is a simple web application that generates random colors and changes the background color of the webpage. It includes a heart-shaped animation as well.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Generate Random Screen Color](#generate-random-screen-color)
- [License](#license)

## Introduction

This web application generates random colors and sets them as the background color of the webpage. It also includes a heart-shaped animation.

## Features

- Generate random colors and change the background color of the webpage.
- Heart-shaped animation for added visual appeal.
- Start and stop buttons to control color generation.

## Usage

1. Open the HTML file (`index.html`) in a web browser.
2. Click the "Start" button to begin generating random colors at an interval of 1 second.
3. Click the "Stop" button to stop the color generation.

## How It Works

- The web application uses HTML, CSS, and JavaScript to create the user interface and functionality.
- The "Start" button triggers the `startChangingColor` function, which starts generating random colors and changing the background color of the webpage at a 1-second interval.
- The `randColor` function generates a random color code in hexadecimal format.
- The "Stop" button triggers the `stopChangingColor` function, which stops the color generation by clearing the interval.

## Generate Random Screen Color

You can also generate a random color for the entire screen using the "Change Color" button. Click the "Change Color" button to set a new random background color for the entire webpage.

```html
<button id="change-color-btn">Change Color</button>
