# DCS Home Page

A way to design a dynamic, lively homepage for DCS

## Develop

Edit the `templates/home.tmpl` file to modify the homepage for DCS, using and leaving in the the `{{...}}` variables as needed.

## Local test

Install Docker Desktop if you haven't already: https://www.docker.com/products/docker-desktop/

Clone this repo on your machine: `git clone https://github.com/unfoldingWord/dcs-homepage.git`

Go into the dirctory this made: `cd dcs-homepage`

Run: `docker compose up`

Then view the homepage at http://localhost:3000

## Deploy

Copy to your DCS instance's templates/ directory in the `GITEA_CUSTOM` directory (either defined by environment variable or in your app.ini file). See https://docs.gitea.io/en-us/customizing-gitea/#customizing-startpage--homepage for more info.
