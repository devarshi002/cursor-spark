# Cursor Animation

This is a simple cursor animation project created using HTML, CSS, and JavaScript. When you click anywhere on the page, it generates a spark-like effect at the cursor's position.

## How it works

- The JavaScript code listens for a click event on the body element.
- When a click event is detected, a `div` element with the class `spark` is created and appended to the body.
- The `spark` element is positioned at the click event's coordinates using `event.clientY` and `event.clientX`.
- Each `spark` element contains 8 `span` elements, each rotated at different angles to create the spark effect.
- The spark animation lasts for 1 second before the `spark` element is removed from the DOM.

## Usage

You can use this cursor animation in your projects by including the `style.css` file for styling and the JavaScript code in your HTML file.

## video


https://github.com/devarshi002/cursor-spark/assets/124704583/88fb6fa8-55d7-4383-9e5e-58b76d88bd87


