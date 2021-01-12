# A Star Wars NodeJS Exercice
This exercise is using the following Star Wars API: [https://swapi.dev/](https://swapi.dev/)

## Goal

The main target is to provide the total diameter of the planets **with mountains and with a water surface** for a specific film.

For example:
```
In Film #6 there are 2 planets that have mountains and a water surface (> 0).
- Alderaan, diameter: 12500
- Naboo, diameter: 12120
Total diameter: 24620
```

We want to know if you can:

* Consume and manipulate data
* Send concurrent calls
* Manipulate received data
* Structure your work flow

## Instructions

* The application should be a CLI.
* The application should accept the ${filmId} as only entry point parameter. 
* The application should catch any error. 
* The application should print the sum of all diameters of concerned planets.
* The application should use npm and not yarn.

## Note
There are a lot of possibilities to solve this exercise but feel free to show us what you can do and what you are worth.

## Final result
Your app should work as the following:
```bash
$ node index.js 6
> 24620
```

