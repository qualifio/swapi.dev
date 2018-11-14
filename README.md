# A Star Wars NodeJS Exercice
DeathStar simple exercice using Star Wars API [https://swapi.co/](https://swapi.co/)


## Goal

The main objectif of the exercice is to provide the total diameter of the planets **without mountains and with a water surface** of a provided film.

For example If we follow the result of SWAPI:

```
In the Film #6 there are 3 planets that have mountains and a water surface.
- Alderaan, diameter: 12500
- Naboo, diameter: 12120
- Mustafar, diameter: 4200

Total diameter: 28820
```

We want to know if you can:

* Consume and manipulate API data
* Optimize the Algorythm
* Use simultaneous calls
* Manipulate the received data
* How you structure


## Instructions

* The application should a simple nodejs script that accepts an argument which would be the film id. (use process.argv)
* Catch errors if swapi is down.
* It prints the total diameter at the end.

## Final result
Your app should works as the following:
```bash
node index.js 6
28820
```

