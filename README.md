# NASA Mission Control Deno Project

## Installation

1. Ensure you have Deno installed: https://deno.land
2. Make sure to install v.1.0.0 
- Shell: ``curl -fsSL https://deno.land/x/install/install.sh | sh -s v1.0.0``
- Powershell: ``$v="1.0.0"; iwr https://deno.land/x/install/install.ps1 -useb | iex``
4. In the terminal, run: `deno run --allow-read --allow-net mod.ts`

## Backend API

Ensure the backend is running by making a request to http://localhost:8080/

## Front End

Browse to the Mission Control front end at http://localhost:8080/index.html and schedule an interstellar mission launch!

## Preview

<img src="https://github.com/adityanjr/nasa-deno/blob/master/images/1.PNG">
<img src="https://github.com/adityanjr/nasa-deno/blob/master/images/2.PNG">
<img src="https://github.com/adityanjr/nasa-deno/blob/master/images/3.PNG">

## Locking Dependencies

After adding a dependency, run `deno run -A mod.ts cache` to update the local module cache and create a corresponding lock file.

## API

Exoplanets API : https://exoplanetarchive.ipac.caltech.edu/docs/data.html
