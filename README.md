# Text Editor Starter Code

## Description
    PWA that allows you to switch between online and offline modes and still works,
    also allows you to download app to desktop from web browser (install button).The purpose of the assignment was to add DB, local caching, and PWA installation capabilities to the JATE starter code.

## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [Mock up](#mock-up)
- [Questions](#questions)



## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```
## Installation

This program has has dependencies, and requires their installation via *npm*.  This project has both a server and a client component, with the client component requiring a build.  This can all be invoked via Node at the command prompt using *npm run start:dev*.

## Usage 
This program is a text editor that can be run in-browser, or be installed to the PC or mobile device with the "install" button at the top-left of the display.

## Contributors
To contribute to PWA-text editor, clone this repo locally and commit your code on a separate branch.

## Mock Up
<img width="944" alt="image" src="https://github.com/robbi19/Progressive-Web-Applications-PWA-Challenge-Text-Editor/assets/128949831/6797a208-1f70-4a78-8659-1e4d0b20e217">
https://drive.google.com/file/d/1aJZMk5jUZ3vLiEpHhoiOUola3nDZFCuD/view

## Questions
Below is the link to my demo video on my Github:
https://drive.google.com/file/d/1aJZMk5jUZ3vLiEpHhoiOUola3nDZFCuD/view

deploy-https://pwatexteditor1-9d4b0824978c.herokuapp.com/


