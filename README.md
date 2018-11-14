# A Star Wars NodeJS Exercice
DeathStar simple exercice using Star Wars API [https://swapi.co/](https://swapi.co/)


## Goal

The main objective of the exercise is to compute the total diameter of the planets **without mountains and with a water surface** of a given film ID.

For example, if we have the following data from SWAPI:

```
In the Film #6 there are 3 planets that have mountains and a water surface.
- Alderaan, diameter: 12500
- Naboo, diameter: 12120
- Mustafar, diameter: 4200
```
The output should be:
```
Total diameter: 28820
```

We want to know if you can:

* Consume and manipulate API data
* Optimize the algorithm
* Send simultaneous/concurrent calls
* Manipulate the received data
* How you structure the flow


## Instructions

* The application should be a simple NodeJS script that accepts an argument which would be the film id. (use process.argv)
* You should catch errors if swapi is down.
* It should print the total diameter at the end.

## Final result
Your app should works as the following:
```bash
node index.js 6
28820
```

