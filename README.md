# text-editor
# 19 Progressive Web Applications (PWA): Text Editor
# JATE - Just Another Text Editor

## Overview

JATE (Just Another Text Editor) browser-based text editor designed for developers. This single-page application leverages Progressive Web Application (PWA) technology, ensuring it runs smoothly offline while offering a seamless online experience. With robust data persistence techniques and a sleek, user-friendly interface, JATE stands out as a reliable tool for creating and managing notes or code snippets, accessible anytime, anywhere.

## Features

- **PWA Technology:** Installable as a desktop app, providing a native-like experience.
- **Data Persistence:** Utilizes IndexedDB with `idb` for reliable data storage and retrieval.
- **Offline Functionality:** Fully functional without an internet connection, thanks to service workers and cached assets.
- **Modern JavaScript Support:** Built using next-gen JavaScript, ensuring compatibility and performance.
- **Automatic Saving:** Content is automatically saved to IndexedDB when the application window loses focus.
- **Ease of Use:** An intuitive and polished user interface that mirrors the provided mock-up functionality.

## Deployment

JATE is deployed on Render, showcasing the application's robust build scripts and adherence to PWA criteria. Experience the live application [here](https://text-editor-som9.onrender.com).

## Installation

To install JATE on your desktop:
1. Visit the [live application](https://text-editor-som9.onrender.com).
2. Click on the "Install" button in the address bar or within the application menu.
3. Follow the prompts to add JATE to your desktop.

## Usage

1. Open JATE from your desktop or web browser.
2. Begin typing your notes or code snippets. The application will automatically save your content as you type.
3. To view previously saved notes or code, simply reopen JATE; your data will be retrieved from IndexedDB.

## Technology Stack

- HTML
- CSS
- JavaScript
- Webpack
- IndexedDB
- Service Workers

## Resources
The following resources were instrumental in the development of JATE - Just Another Text Editor:

- [Progressive Web Apps (PWAs)](https://web.dev/progressive-web-apps/)
- [IndexedDB API](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
- [Webpack](https://webpack.js.org/)
- [Render Deployment Guide](https://render.com/docs/deploying)


## License

Distributed under the MIT License. See `LICENSE` for more information.
