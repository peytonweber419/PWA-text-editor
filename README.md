# PWA Text Editor: JATE

## Description

JATE is just another text editor. This is a progressive web application (PWA) that runs in the browser, locally, and offline. JATE can be useful for writing out code, storing code snippets, or just taking some notes. Keep reading for more info.

## Usage

### User Story


AS A developer
I WANT to create notes or code snippets with or without an internet connection

SO THAT I can reliably retrieve them for later use


### Acceptance Criteria


GIVEN a text editor web application

WHEN I open my application in my editor

THEN I should see a client server folder structure

WHEN I run npm run start from the root directory

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

WHEN I deploy to Render

THEN I should have proper build scripts for a webpack application

## Technologies Used

- HTML
- CSS
- JavaScript
- IndexedDB
- Express
- Concurrently
- Webpack + Workbox
- NodeJS
- Babel

## Installation

This project is deployed through Render: https://jate-pwa-editor-h4ep.onrender.com/

To run JATE locally:
- Clone this repo onto your machine,
- run `npm i` in the terminal,
- then run `npm start`, navigate to localhost:3000 to use JATE in the browser, or install from the browser.

## License

N/A

## Screenshot of Deployed Application
![image](https://github.com/peytonweber419/PWA-text-editor/assets/144742645/9c5c276e-a402-441d-ad97-b05e121e01a4)

