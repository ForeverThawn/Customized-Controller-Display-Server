# 给OBS用的一个展示手柄操作的web程序

[English](https://github.com/ForeverThawn/Customized-Controller-Display-Server/blob/main/README.md)

此项目使用JavaScript Gamepad API制作，目的是弄一个自己用OBS录视频方便展示欧卡2/美卡手柄操作的overlay

*参考项目：* [ControllerInputVisualizer](https://github.com/AnonymerNiklasistanonym/ControllerInputVisualizer)

PS: 这个东西是完全自用，所以没有适配，当然大家可以用来学习

## 项目特性相关链接

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

## 使用

浏览器打开 [`index.html`](index.html)；

或者直接命令行运行 `node index.js`。
