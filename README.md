# Tech Quiz Testing Assignment

## Overview
This project implements comprehensive testing for a MERN stack Tech Quiz application. The testing suite includes both component testing and end-to-end testing using Cypress, ensuring the application meets all functional requirements and provides a smooth user experience.

## Table of Contents
- [Application Description](#application-description)

- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Running Tests](#running-tests)
- [Testing Strategy](#testing-strategy)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Demo Video](#demo-video)

## Application Description
The Tech Quiz application allows users to test their technical knowledge through a series of questions. Built with the MERN stack (MongoDB, Express.js, React, and Node.js), the application presents users with 10 random questions, tracks their progress, and displays their final score once the quiz is completed.


## Installation
1. Clone the repository to your local machine
   ```
   git clone [repository URL]
   cd [repository name]
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Set up environment variables
   ```
   # Rename .env.example to .env
   mv .env.example .env
   ```

## Running the Application
1. Start the development server
   ```
   npm run develop
   ```

2. Open your browser and navigate to http://localhost:3000

## Running Tests
This project includes Cypress tests for both component and end-to-end testing.

### Run all tests
```
npm run test
```

### Run component tests only
```
npm run test:component
```

### Run E2E tests only
```
npm run test:e2e
```

### Open Cypress Test Runner
```
npm run cypress:open
```

## Testing Strategy
The testing strategy for this application focuses on two main areas:

### 1. Component Testing
The component tests ensure that the Quiz component:
- Renders correctly
- Displays questions properly
- Allows user interaction (selecting answers)
- Transitions between questions appropriately
- Displays final results correctly
- Handles the restart functionality

### 2. End-to-End Testing
The E2E tests verify that:
- The application loads correctly
- Users can start a new quiz
- Questions are presented one at a time
- Users can select answers and move to the next question
- The quiz tracks progress accurately
- Final results are displayed at the end
- Users can restart the quiz

## Technologies Used
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Testing Framework**: Cypress
- **Additional Libraries**:
  - @testing-library/cypress
  - @cypress/react

## Demo Video

https://www.youtube.com/watch?v=c6bx_XfLv5o

##Contact me 

LinkedIn: https://www.linkedin.com/in/mart%C3%ADn-rojo/
GitHub: https://github.com/Martin-rojo)

