# Customized Controller Display Server for OBS

A simple webapp that visualizes the input triggers and axis of connected controllers using the JavaScript Gamepad API.

*This repository is forked from* [ControllerInputVisualizer](https://github.com/AnonymerNiklasistanonym/ControllerInputVisualizer)

PS: This is a version using my own settings, mainly working for ETS2 and ATS.

## Links of features that are used by this project

- `canvas`
  - [game loop (sitepoint)](https://www.sitepoint.com/quick-tip-game-loop-in-javascript/)
  - [game loop (mdn)](https://developer.mozilla.org/en-US/docs/Games/Anatomy)
  - [`window.requestAnimationFrame` (mdn)](https://developer.mozilla.org/en-US/docs/Web/API/Window/requestAnimationFrame)
  - [`window.cancelAnimationFrame` (mdn)](https://developer.mozilla.org/en-US/docs/Web/API/Window/cancelAnimationFrame)

- Gamepad API
  - [Using the Gamepad API (mdn)](https://developer.mozilla.org/en-US/docs/Web/API/Gamepad_API/Using_the_Gamepad_API)

- Web app manifest:
  - [Web app manifests (mdn)](https://developer.mozilla.org/en-US/docs/Web/Manifest)

- Web Storage API
  - [Using the Web Storage API (mdn)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API/Using_the_Web_Storage_API)

- FileReader API
  - [FileReader API (mdn)](https://developer.mozilla.org/en-US/docs/Web/API/FileReader)

## How to run

Open the [`index.html`](index.html) file with your browser.

Or simply run the command `node index.js` as a web server.
