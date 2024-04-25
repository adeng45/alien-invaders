![](./public/space-invaders-hero.svg)

# About

This project runs a realtime multiplayer version of the classic retro game, Space Invaders.

![Preview of the game](https://user-images.githubusercontent.com/5900152/84092843-7ea1ce80-a9f0-11ea-809d-41cd20fb8e59.gif)
<br>

## Services/libraries 

- [Phaser 3](https://phaser.io)
- [p2 NPM library](https://www.npmjs.com/package/p2)
- [Ably Realtime](https://www.ably.com) 

You will require an Ably API Key to run the app, which can be made [here](https://ably.com/sign-up)
<br>
<br>
<br>

## To run

1. Clone this repo locally
1. Navigate to the project folder and run `npm install` to install the dependencies
1. Rename `.env-sample` to `.env`, then edit the file and add your Ably API key and prefered PORT (default 8080).
1. (Optional) You can update the `MIN_PLAYERS_TO_START_GAME` to enforce a minimum number of players. (see `server-worker.js`)
1. Run the server with `node server.js` and then open a brower to [localhost:8080](http://localhost:8080)
<br>

Have fun!
