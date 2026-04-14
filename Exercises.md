# Part One

## Exercise One

These variables describe a dog. Rewrite them as a single object called `dog`.

```js
let dogName = "Rex";
let dogBreed = "Labrador";
let dogAge = 4;
```

let dog = {
    name: "Rex",
    breed: "Labrador",
    age: 4
};

The seperate variables can make it messy, this allows things to be more compact.

## Exercise Two

How many variables are declared below? Rewrite them as a single object called `song`. How many variables now?

```js
let title = "Stayin' Alive";
let artist = "Bee Gees";
let year = 1977;
let bpm = 103;
```

let song = {
    title: "Stayin Alive",
    artist: "bee Gees",
    year: 1977,
    bpm: 103
};

Before there were 4 variables, now there is 1 object. Keeping related data together.

## Exercise Three

Create two objects — `player1` and `player2` — each with a `name`, `score`, and `isOnline` property. Make up the values.

let player1 = {
    name: "Richie McCaw",
    score: 10,
    isOnline: true
};

let player2 = {
    name: "Daniel Carter",
    score: 8,
    isOnline: false
};

## Part Two

## Exercise Four

Given this object, write two `console.log` statements — one that prints the city name, and one that prints the population.

```js
let city = {
  name: "Auckland",
  population: 1700000,
  isCoastal: true
};
```

console.log(city.name);
console.log(city.population);

dot.notation can be used to access, modify or create properties and methods of an object. Using a period (.) between object name and property name.

## Exercise Five

A player just levelled up. Update their `level` to `5` and their `title` to `"Knight"`. Then `console.log` the whole object to check.

```js
let player = {
  name: "Aroha",
  level: 4,
  title: "Squire"
};
```

player.level = 5;
player.title = "Knight";

console.log(player);

