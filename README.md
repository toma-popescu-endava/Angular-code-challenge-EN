# Angular code challenge

Great that you are interested in working with us! Every day we work with a large group of developers on the websites of Centraal Beheer, Interpolis, FBTO and Avero. We really want to expand this group of developers. In addition, we don't find education, work experience or background really that valuable at all. It is more important that you have talent and the right motivation. 

## What is the Code challenge?
The Code challenge is an accessible front-end assignment where you build a number of new functionalities for an example application. We review your code and if we like your solution, we would like to invite you for a first introductory meeting.

## The challenge
We work a lot with forms. Forms to report your damage, to take out a new insurance policy, etc.

These forms are often built in Angular. 

In this code challenge you will work with an example form. The styling (we use Tailwind https://tailwindcss.com/ for this challenge) and html is already done but we are still missing some functionality.

![Screenshot](screenshot.png)

### Requirements:
Finish the example form (see src/app/app.component.html for the existing html). We expect your application to contain at least (part of) the following requirements:

Functionalities:
- The user must be able to choose the type of vehicle
    - Possible choices:
        - auto
        - motor
        - scooter
- The image to the right of the form should change based on the user's choice. The following combinations are possible:
    - auto: assets/auto.jpg
    - motor: assets/motor.jpg
    - scooter: assets/scooter.jpg     
- The user must be able to choose the subtype of the vehicle.
    - Possible subtypes for vehicle _auto_
        - Hatchback
        - Sedan
        - Station
        - Cabriolet
        - Coupé
        - Multi Purpose Vehicle (MVP)
        - Terreinauto
    - Possible subtypes for vehicle _motor_:
        - All-road
        - Naked
        - Enduro
        - Race
        - Toermotor
        - Chopper
        - Zijspan
    - Possible subtypes for vehicle _scooter_:
        -For _scooters_, the user cannot choose a subtype
- Implement license plate formatting as follows:
    - Insert a dash between the numbers and letters of the license plate. AA14BB then becomes AA-14-BB
    - For letter combinations of 4 characters: insert a dash after 2 characters. 12AABB then becomes 12-AA-BB
- Implement basic license plate validation:
    - Use the following library to implement license plate validation: https://www.npmjs.com/package/rdw-kenteken-check
    - Is the entered value invalid? Then show the following error message (on-blur of the field): "Helaas is het ingevoerde kenteken niet geldig. Probeer het opnieuw." 

### Technical requirements:
- Split the html into logical Angular components
- Use Angular Reactive forms to build your form
    
## Extra challenge?
- Do you want to show what else you can do? For example, can you already write unit tests, do you have experience with NGRX or do you love UX and do you think the current set-up is a bit thin? Get started with your own idea and show us what you can do! Of course you can also completely remove Tailwind and add your own CSS implementation.

## Conditions
- To keep the challenge equal for all candidates, we expect you to spend no more than 2 - max 4 hours on the challenge. Not finished with all requirements after 4 hours? No problem, just send in what you have. We find quality and an eye for details much more important than that you have realized all the requirements.
- Fork this Github to your own Github account and push your solution. Send us a link of your solution.

## Technical details

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
