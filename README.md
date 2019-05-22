# Blackjack (1-week group project)

Becky Nielsen, Jenn Archibald, Jon Zarecki and Charlie Walker

Group project created following 3 weeks of JavaScript lessons. Created a full stack JavaScript application Blackjack game, with an Express server and MongoDB database.

## Brief
Create a browser game based on an existing card or dice game. Model and test the game logic and then display it in the browser for a user to interact with.

## Rules

The project must be built using **only**:

* HTML / CSS
* Javascript
* Express
* MongoDB

It must **NOT** use:

* Any Object Relational Mapper (e.g. ActiveRecord)
* Jquery
* Any pre-built CSS libraries, such as Bootstrap.
* Authentication. Assume that the user already has secure access to the app.

## MVP
```diff
+ Two cards can be dealt to both the dealer and the player
+ Hands can be totalled
+ The highest hand wins and a winner is declared 
+ Game displays in browser
```

## Extensions
```diff
+ A player can draw cards.
+ The model declares “Bust” if the hand is over 21.
+ A player draws multiple cards until bust or “Hit” is clicked.
+ Dealer takes a turn. Will draw until at least 17 or is bust.
+ Have a purse available to the player.
+ Allow the player to place bets.
+ Have the rules listed.
+ Bets and hands are totalled.
+ Buttons disabled until the appropriate point.
```
## Next Steps - what we would do with more time
```diff
- Remember a player and recall their purse.
- Allow for multiple players.
- Allow players to split their hand.
- Allow player to 'cash-out'.
```

## Getting Started

These instructions will get the project up and running on your local machine.

### Installing

Install dependencies:

```
npm install
```

Run a mongoDB server (leave running in a terminal window):

```
mongod
```

Seed the database:

```
mongo < server/db/seeds.js
```

Run webpack (leave running in a terminal window):

```
npm run build
```

Run express (leave running in a terminal window):

```
npm run server:dev
```

### Using

The application is running on port 3000 so visit http://localhost:3000/.

## Screenshot Examples

### Player Decides Bet Amount
![image](https://user-images.githubusercontent.com/30385421/56810675-c9817680-682e-11e9-84da-5b28c8994c0a.png)

### Player Turn
![image](https://user-images.githubusercontent.com/30385421/56812251-68f43880-6832-11e9-8286-41f7666aa7d4.png)


### Player Wins
![Screen Shot 2019-04-26 at 14 10 39](https://user-images.githubusercontent.com/30385421/56810386-1add3600-682e-11e9-8d27-6cb0eae365f7.png)
