![](./public/space-invaders-hero.svg)

# About

This project runs a realtime multiplayer version of the classic retro game, Space Invaders.

![Preview of the game](https://user-images.githubusercontent.com/5900152/84092843-7ea1ce80-a9f0-11ea-809d-41cd20fb8e59.gif)
<br>

DEMO (https://alieninvaders-ad45-fc21889250c8.herokuapp.com/)
<br>

## Services/libraries 

- [Phaser 3](https://phaser.io)
- [p2 NPM library](https://www.npmjs.com/package/p2)
- [Ably Realtime](https://www.ably.com) 

An Ably API Key to run the app, which can be made [here](https://ably.com/sign-up)
<br>
<br>

## To run

1. Clone this repo locally
1. Navigate to the project folder and run `npm install` to install the dependencies
1. Rename `.env-sample` to `.env`, then edit the file and add your Ably API key and prefered PORT (default 8080).
1. (Optional) You can update the `MIN_PLAYERS_TO_START_GAME` to enforce a minimum number of players. (see `server-worker.js`)
1. Run the server with `node server.js` and then open a brower to [localhost:8080](http://localhost:8080)
<br>

## To do

- [x] Set up basic site
- [x] Locating necessary resources(SVGs, fonts, ...)
- [x] Room create/join
- [x] Game logic + rendering
- [x] Server synchronization between multiple players
- [ ] Handling page navigation (in progress)
- [ ] Final styling
<br> 

## To contribute

Have no fear! This project is distributed under the MIT license, free to be shared/used by all!

1. How do I make a contribution? 

1. Fork the repository. 

1. Clone the repository to your local machine using git clone https://github.com/github-username/repository-name.git.

1. Create a new branch for your feature (`git checkout -b`)

1. Make the appropriate changes for the issue you are trying to address or the feature that you want to add.

1. Push the changes to the remote repository (`git push origin branch-name-here`)

1. Submit a pull request to the upstream repository.

1. Title the pull request with a short description of the changes made. For example, you can title an issue like so "Added volume control feature".

1. In the description of the pull request, explain the changes that you made, any issues you think exist with the pull request you made, and any questions you may have. It's OK if your pull request is not perfect (no pull request is), I would love to see your ideas anyways &nbsp; 
: \)
<br> 

Hope you have fun!
