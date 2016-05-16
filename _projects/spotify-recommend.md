---
project: spotify-recommend
tag: spotify
priority: 1
---
Yet another project that came out of my time in the Thinkful node.js course. This project was started early in the curriculum sequence to give me the opportunity to explore event-based and callback-based approaches to async programming in node.

Since it started as a throwaway exercise for working with the Spotify API, it was in a pretty poor state when I got started. Now, however, the app has an intuitive, easily extensible architecture:

- Build tasks configured via Grunt use browserify and babelify to transpile ES2015-style React components into a distribution file that will work on all browsers.
- The server-side Express application exposes a simple RESTful API that will be easy to add to going forward.
- Interactions with the Spotify API are being extracted to separate service modules.

Right now, I've converted the old handlebars template for searching related artists into React components - not very exciting by itself, but the modular, composable nature of React components will allow me to easily plug this view into different parts of the application as it grows.
