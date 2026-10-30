Mute Button
===================
Continuing in our exploration handling interactions and events in React, we'll now create a simple UI - but without `<input>` elements.  In addition to learning how to handle click events, you'll also learn how to utilize SVGs in React apps.

Release 0
-------------
* Scaffold the app (Node 22 or 24) and start it:

```sh
npm create vite@latest mute-button -- --template react
cd mute-button
npm install
npm run dev
```

* Copy the **icons** folder into `mute-button/src/assets/`, then import the images: `import onIcon from './assets/icons/on.svg'`.

Release 1
-------------
* Render the **on.svg** image from the icons directory and attach an onClick event listener to it.

Release 2
-------------
* When the image is clicked, toggle it to the **off.svg** image - and vice versa.  on -> off -> on -> off.
