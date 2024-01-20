# just-another-text-editor


## Description
Create a browser-based text editor as a single-page application adhering to Progressive Web App (PWA) standards. Implement various data persistence techniques to ensure redundancy in case a browser doesn't support one option. The editor should also operate seamlessly offline.

## Table of Contents
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Struggles](#struggles)
* [Links](#links)

## User Story
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use


## Acceptance Criteria
* GIVEN a text editor web application
* WHEN I open my application in my editor
* THEN I should see a client server folder structure
* WHEN I run `npm run start` from the root directory
* THEN I find that my application should start up the backend and serve the client
* WHEN I run the text editor application from my terminal
* THEN I find that my JavaScript files have been bundled using webpack
* WHEN I run my webpack plugins
* THEN I find that I have a generated HTML file, service worker, and a manifest file
* WHEN I use next-gen JavaScript in my application
* THEN I find that the text editor still functions in the browser without errors
* WHEN I open the text editor
* THEN I find that IndexedDB has immediately created a database storage
* WHEN I enter content and subsequently click off of the DOM window
* THEN I find that the content in the text editor has been saved with IndexedDB
* WHEN I reopen the text editor after closing it
* THEN I find that the content in the text editor has been retrieved from our IndexedDB
* WHEN I click on the Install button
* THEN I download my web application as an icon on my desktop
* WHEN I load my web application
* THEN I should have a registered service worker using workbox
* WHEN I register a service worker
* THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
* WHEN I deploy to Heroku
* THEN I should have proper build scripts for a webpack application

## Usage
***Quick Note-Taking:***

Use the simple text editor for quick note-taking. Open it in your browser, jot down ideas, to-dos, or any information you need on the fly.

***Creating Drafts:***

When working on drafts for articles, blog posts, or creative writing, the text editor provides a straightforward platform to compose and organize your thoughts.

***Distraction-Free Writing:***

Enjoy a distraction-free writing experience. The basic text editor removes unnecessary features, allowing you to focus solely on your content.

***Code Snippet Storage:***

Use the text editor to store and organize code snippets. It's a handy tool for developers who want a quick and accessible space for code notes.

***Offline Writing:***

Take advantage of the editor's offline functionality. Even without an internet connection, continue writing and editing your documents seamlessly.

***Export and Share:***

Export your documents in various formats such as plain text or Markdown. Easily share your work with others or integrate it into different platforms.

## License
No license for this project

## Struggles
I was unable to get the application to deploy properly to Render. I have still been working to resolve this issue, and I was able to deterine the issue may have to do with my file pathing. Although, I have not comepltely resolved the error.

## Links 

* [Link to deployed application](https://just-another-text-editor-cxj2.onrender.comLinks)
