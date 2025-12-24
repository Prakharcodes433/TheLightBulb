# JavaScript Light Bulb Toggle

A simple interactive web demonstration showing how JavaScript can dynamically change HTML attribute values (specifically the `src` attribute of an image).

## Description
This project features a light bulb that can be "turned on" and "turned off" using two buttons. It serves as a fundamental exercise in DOM (Document Object Model) manipulation.

## How It Works
When a user clicks one of the buttons, a JavaScript function triggers a change to the `<img>` tag's `src` attribute:
* **Turn On:** Changes the image source to a "light bulb on" graphic.
* **Turn Off:** Changes the image source to a "light bulb off" graphic.

## Code Logic
The core functionality is achieved using the following logic:

```javascript
// Turning the light ON
document.getElementById('myImage').src = 'pic_bulbon.gif';

// Turning the light OFF
document.getElementById('myImage').src = 'pic_bulboff.gif';
