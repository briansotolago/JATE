# PWA Text Editor: J.A.T.E

## Description

This project is a Progressive Web Application (PWA) text editor that allows users to create notes or code snippets with or without an internet connection. The application is designed to function offline and features data persistence techniques using IndexedDB. It is a single-page application that meets PWA criteria and can be installed on the user's device.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Deployment](#deployment)
- [Repo](#repo)
- [License](#license)

## Installation

1. Clone the repository:
        ```bash
   git clone <repository-url>
        ```
2. Navigate to the project directory:
        ```bash
   cd JATE
        ```
3. Install the dependencies:
        ```bash
   npm install
        ```

## Usage

To start the application, run the following command from the root directory:
      ```bash
npm start
      ```

Open the browser and navigate to port 3000.

## Features

- Offline functionality using service workers
- Data persistence with IndexedDB
- Bundled with webpack
- Uses Babel for next-gen JavaScript features
- Installable as a PWA
- Automatically saves content when the DOM window is unfocused

## Deployment

The application is deployed on Render. You can access it at the following URL: [Deployed Application URL](https://jate-ulf3.onrender.com)

## Repo

[GitHub Repo](https://github.com/briansotolago/JATE)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
