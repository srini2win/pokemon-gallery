# pokemon-gallery

This project was created with Angular4. 

## Problem description 
Pokemon character figure image are to be displayed in a gallery.

The page should adapt to mobile, tablet and desktop
screen widths.
* `Mobile`: 1 Pokemon per row
* `Tablet`: 2 Pokemon per row
* `Desktop and larger`: 4 Pokemon per row
 
A maximum of 20 Pokemon should be displayed at once. The
page should have a Previous / Next control for
pagination.
Provide a search box to filter all Pokemon by name. The
search term should be case insensitive and match any part
of the name. For example, searching “Rat” will display
Rattata, Raticate, Poliwrath, Dratini.

Before running the project please make sure following dependencies are installed

1. Node.js with NPM (Node Package Manager)
2. Angular-CLI (Command Line Interface)

## Installation of dependencies
If dependencies are not installed, please follow steps given below, otherwise follow code setup instructions.

1. To Install Node: https://nodejs.org/en/download/
2. Once Node is installed, run following command on terminal to make sure node has been installed
> node -v
3. Now install angular cli using following command on terminal
> npm install -g @angular/cli

## Code setup
1. Once dependencies are installed, project can be clonned using following command
> git clone https://github.com/srini2win/pokemon-gallery.git
2. Go inside pokemonGallery and run following command
> npm install

Once these steps are performed Development server can be started as instructed below

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Unit test report
For desktop Screen @ ![Screenshot](https://github.com/srini2win/pokemon-gallery/blob/master/unit_test_report_desktop.png)

For iPad version @ ![Screenshot](https://github.com/srini2win/pokemon-gallery/blob/master/unit_test_report_iPadAir.png)

For iPhone version @ ![Screenshot](https://github.com/srini2win/pokemon-gallery/blob/master/unit_test_report_iPhone6.png)
