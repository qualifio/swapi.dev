# A Star Wars NodeJS Exercice
DeathStar simple exercice using Star Wars API [https://swapi.co/](https://swapi.co/)


## Goal

The main objectif of the exercice is to provide the total diameter of the planets **With mountains and with a water surface** of a provided film.

For example, if we have the following data from SWAPI:

```
In the Film #6 there are 2 planets that have mountains and a water surface (> 0).
- Alderaan, diameter: 12500
- Naboo, diameter: 12120

Total diameter: 24620
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

