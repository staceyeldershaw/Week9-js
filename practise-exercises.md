# JavaScript 104 — Objects & DOM Part 1
## Practice Exercises

---

## Part 1 — Creating objects

### Exercise 1 — Your first object *(starter)*

These variables describe a dog. Rewrite them as a single object called `dog`.

```js
let dogName = "Rex";
let dogBreed = "Labrador";
let dogAge = 4;
```

<details>
<summary>Hint</summary>

Use curly braces `{ }` and put each piece of info as a key-value pair separated by commas.

</details>

---

### Exercise 2 — Spot the difference *(starter)*

How many variables are declared below? Rewrite them as a single object called `song`. How many variables now?

```js
let title = "Stayin' Alive";
let artist = "Bee Gees";
let year = 1977;
let bpm = 103;
```

<details>
<summary>Hint</summary>

Before: 4 variables. After: 1 variable (`song`) that holds all four pieces of info as properties.

</details>

---

### Exercise 3 — Two objects *(starter)*

Create two objects — `player1` and `player2` — each with a `name`, `score`, and `isOnline` property. Make up the values.

<details>
<summary>Hint</summary>

`isOnline` is a boolean — its value should be `true` or `false`, not a string.

</details>

---

## Part 2 — Accessing & updating properties

### Exercise 4 — Read the properties *(practise)*

Given this object, write two `console.log` statements — one that prints the city name, and one that prints the population.

```js
let city = {
  name: "Auckland",
  population: 1700000,
  isCoastal: true
};
```

<details>
<summary>Hint</summary>

Use dot notation: `city.name`, `city.population`

</details>

---

### Exercise 5 — Update a property *(practise)*

A player just levelled up. Update their `level` to `5` and their `title` to `"Knight"`. Then `console.log` the whole object to check.

```js
let player = {
  name: "Aroha",
  level: 4,
  title: "Squire"
};
```

<details>
<summary>Hint</summary>

Use dot notation to assign: `player.level = 5;` — same way you'd update a regular variable.

</details>

---

### Exercise 6 — Bracket vs dot notation *(practise)*

Using the `car` object below, access `model` using dot notation and `year` using bracket notation. Print both with `console.log`.

```js
let car = {
  model: "Kia Rio",
  year: 1995,
  isNice: false
};
```

<details>
<summary>Hint</summary>

Dot: `car.model` — Bracket: `car["year"]`

</details>

---

## Part 3 — Putting it together

### Exercise 7 — Build a contact card *(challenge)*

Create an object called `contact` that could represent a person in your phone. It should have at least 4 properties. Then write code that prints a message like:

```
Call Tupac on 021-555-1234
```

<details>
<summary>Hint</summary>

Use a template literal to build the message:

```js
`Call ${contact.name} on ${contact.phone}`
```

</details>

---

### Exercise 8 — Transport compare *(challenge)*

Create two transport objects (e.g. `bus` and `uber`), each with a `name` and `cost` property. Then write an `if` statement that logs which option is cheaper.

<details>
<summary>Hint</summary>

Compare `bus.cost` and `uber.cost` using `<`. Print `bus.name` or `uber.name` in the message.

</details>

---

### Exercise 9 — Spot the bug *(debug)*

This code has **3 bugs**. Find and fix them all.

```js
let book = [
  title: "The Hobbit"
  author = "Tolkien",
  pages: 310
];

console.log(book.Title);
```

<details>
<summary>Hint</summary>

1. Objects use `{ }` not `[ ]`
2. Properties use `:` not `=`
3. Property names are case-sensitive — `title` not `Title`

</details>