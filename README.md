FILE STRUCTURE:

/stylesheets/app - our application's CSS

/stylesheets/vendor- anything from a bower component, that we didnt write.

/assets/ - CSS Assets that are selectively rendered, at runtime, by browser, are for now put in as static assets in the /app/assets folder. This is because Brunch auto concatenates everything based on the brunch-config.js and I have no time to figure out the necessary regular expressions to exclude selectively. 

-------------

TODO:
- set up Brunch with Heroku
- split out CSS in /assets into ltie8/app and ltie8/vendor, etc?
- set  Handlebars + partials, to reuse panels, and cut down on responsive images markup
- make square crops for main image
- add Picturefill
- add font awesome - down blinking tab
- https://github.com/steffenmllr/imageoptmizer-brunch

- fix errors: Uncaught Error: Cannot find module "app" from "/"require @ app.js:80(anonymous function) @ (index):193
(index):196 Uncaught ReferenceError: app is not defined

- add animations
- youtube.video
- fix zooming. not working because of width:100%, added for Safari