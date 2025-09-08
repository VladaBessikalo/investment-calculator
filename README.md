# Investment Calculator

A modern Angular application that helps users calculate their investment growth over time. This project demonstrates the implementation of various Angular features and concepts.

## Features

- Calculate investment returns based on:
  - Initial investment amount
  - Annual contribution
  - Expected return rate
  - Investment duration
- Dynamic result visualization
- Responsive user interface
- Real-time calculations

## Technical Concepts & Implementation

### Angular Core Features

- Standalone Components
- Signals for state management
- TypeScript strict type checking
- Component Communication (Input/Output decorators)
- Custom Models/Interfaces

### Components Structure

- `HeaderComponent`: Application header with branding
- `UserInputComponent`: Form handling for investment parameters
- `InvestmentResultsComponent`: Displays calculation results
- `AppComponent`: Main application component orchestrating data flow

### Services

- `InvestmentService`: Handles investment calculations logic

### Modern Angular Patterns

- Modular architecture
- Reactive state management with Signals
- Type-safe development
- Component-based architecture
- Standalone component configuration

## Development

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
