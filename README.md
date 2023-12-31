# ios-color-race-game
An iOS game based on the **Color Race** board game. Color Race is a 2 player game where users pick cards with random color patterns & then place colored tokens on a 3x3 board to match the pattern. The first one to complete the pattern wins the round!

<img width="100" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/80e9b785-d22c-434a-a1c9-766b4d3ba026">
<img width="100" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/e46f0849-2633-4507-807a-be7bda0ebe2e">
<img width="100" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/a7487039-9c1c-4674-bcd9-7d7158e30bd0">
<img width="100" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/d9aafac4-036c-479e-8f42-d336317aa68a">

---
iOS Gameplay
---
* In this version, when you launch the app it'll attempt to connect you to a local socket server.
* On connecting to the server the app will then wait for another user to connect to the server.
* When another user connects, both you and the other user are matched and a random color pattern is assigned to each.
* You sequentially tap each tile in a 3x3 grid in order to switch colors until you match the pattern you were assigned.
* The round ends when either player correctly matches the assigned pattern and the next round loads after 3 seconds.
* While in game, you can see the other users inputs in real time in the HUD.
* In case a user drops or backs out from the game and another user joins, you will be automatically matched with them.

---
Getting started
---
Steps:
* Install [Node.js](https://nodejs.org/en/download)
* cd to the **Server** directory in Terminal and run `npm install` to install the dependencies viz. express & socket.io
* [Optional] Run `npm install nodemon --global` to install nodemon. Use `sudo` if you face permission errors
* Run `nodemon index.js` to start the server
* Open **ColorRace.xcodeproj** in Xcode 14.3 or later.
* Wait for package dependencies to be resolved, build and run in the simulator or on a device.

---
Screenshots
---
<img width="100" alt="Screenshot 2023-10-10 at 10 42 00 AM" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/00a170f1-f8bb-41b4-a7ed-fb2d17f42223">
<img width="100" alt="Screenshot 2023-10-10 at 10 42 12 AM" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/27072a22-dee8-4712-9b3a-0aa4aa5e7240">
<img width="100" alt="Screenshot 2023-10-10 at 10 42 24 AM" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/aacaa893-feee-4723-9298-ecc4325adf0b">
<img width="100" alt="Screenshot 2023-10-10 at 10 59 03 AM" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/bf66185f-790c-4856-b0de-03c10a95bd55">
<img width="100" alt="Screenshot 2023-10-10 at 10 42 38 AM" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/19a341d6-e2d0-4bba-b6d4-ce1f07575085">
<img width="100" alt="Screenshot 2023-10-10 at 10 56 48 AM" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/86969e45-9b9f-452f-a85a-75981615dd84">
<img width="100" alt="Screenshot 2023-10-10 at 10 43 38 AM" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/7210a789-6ec9-4e05-83a2-0ca50fa5e204">
<img width="100" alt="Screenshot 2023-10-10 at 10 43 58 AM" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/5070c197-7aed-411f-a1a0-37d78d21c610">
<img width="100" alt="Screenshot 2023-10-10 at 10 44 20 AM" src="https://github.com/anupdsouza/ios-color-race-game/assets/103429618/5e2f0324-f335-4f59-bf1e-ce6d81bc2865">

---
Gameplay video
---
https://youtu.be/mnZZQEpkvQE

---
TODO
---
- [ ] Detect socket server disconnection/kill
- [ ] Tidy server side code


