# Text Editor Web Application txt ed



## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview!

![Jate1](https://github.com/Punk1776/txt-ed/assets/135387049/3d4839c2-a25b-48ce-9d1f-02aae6530ab8)

![Jate2](https://github.com/Punk1776/txt-ed/assets/135387049/ebf1165d-9bf8-4716-a4cf-bb95ad667c95)

![jate3](https://github.com/Punk1776/txt-ed/assets/135387049/1b71c879-0a3d-495c-b045-f37637b11c65)

![jate4](https://github.com/Punk1776/txt-ed/assets/135387049/44441285-9fa1-4be6-a65d-6981c15deb54)






The Text Editor Web Application, often referred to as "Just Another Text Editor" (J.A.T.E), is a powerful and versatile web-based text editor that allows you to create, edit, save, and manage text content with ease. It is designed to offer a seamless experience with features like IndexedDB integration, service workers, and Next-Gen JavaScript for efficient text editing and storage.



## Features

- **Folder Structure**: The application follows a client-server folder structure for organized development.

- **Quick Start**: With a simple `npm run start` command, the application starts both the backend and the client, making it easy to run.

- **JavaScript Bundling**: JavaScript files are efficiently bundled using Webpack for optimized performance.

- **Generated Files**: Webpack plugins generate HTML files, service workers, and manifest files.

- **Next-Gen JavaScript**: The application supports next-generation JavaScript for modern development practices.

- **IndexedDB Integration**: IndexedDB is immediately created for database storage, allowing for seamless data persistence.

- **Data Persistence**: Text content entered in the editor is automatically saved to IndexedDB. Even if you close and reopen the text editor, your content is retrieved from IndexedDB.

- **Desktop Installation**: Users can install the web application on their desktop by clicking the "Install" button, making it easily accessible.

- **Service Worker**: A registered service worker using Workbox ensures a smooth experience even in offline mode.

- **Service Worker Caching**: Static assets are pre-cached upon loading, including subsequent pages and static assets.

- **Heroku Deployment**: Proper build scripts are provided for deploying the application to Heroku.

## Installation

To install the Text Editor project, follow these steps:

1. Clone the repository to your local machine.


git clone https://github.com/Punk1776/txt-ed

Navigate to the project's root directory.
cd txt-ed

Install the required dependencies.
npm install

## Usage

To use the Text Editor application, follow these instructions:

Start the application by running the following command:
npm run start

Open the application in your web browser.

Enter the desired content in the text editor.

Click off the DOM window to save the content; it will be stored in the IndexedDB database.

If you close and reopen the text editor, the content will be retrieved from IndexedDB, ensuring data persistence.

## Demo
You can access the live demo of the Text Editor Web Application by following this link  https://txt-ed-56467fc71273.herokuapp.com/ 

## License
This project is covered under the MIT License. For more details, please see the LICENSE file.
