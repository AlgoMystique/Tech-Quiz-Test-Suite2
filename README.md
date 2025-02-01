# Tech Quiz Test Suite

This project is an enhancement of a fully functioning Tech Quiz application built using the MERN stack (MongoDB, Express.js, React, Node.js). Cypress is integrated for both component and end-to-end testing.

## Directory Structure:
```
.
├── client/                 // the client application
├── cypress/                // Folder for Cypress
    ├── component/          // Folder for component tests
        └── Quiz.cy.jsx     // Component tests for the Quiz component
    ├── e2e/                // Folder for end-to-end tests
        └── quiz.cy.js      // End-to-end tests for the Tech Quiz
    ├── fixtures/           // Folder for test fixtures
        └── questions.json  // Mock data for testing
    └── tsconfig.json
├── server/                 // the server application
├── .gitignore
├── cypress.config.ts       // Configuration for Cypress tests
├── package.json
├── tsconfig.json
└── README.md              // App description, link to video, setup and usage instructions
```

## Server Configuration:

Create .env and add the necessary environment variables.
```
MONGODB_URI='your mongodb uri'
```

## Getting Started:

-Clone this repository:
```
git clone https://github.com/AlgoMystique/Tech-Quiz-Test-Suite2.git
```

-Install the dependencies:
```
npm install
```
-Run the Cypress tests:
```
npm run test
```
```
npm run test:component
```
```
npm run test:e2e
```
```
npm run cy:open
```


## View The Walkthrough Video Here:

[![Cypress testing](https://img.youtube.com/vi/eYBnTnn7fvA/0.jpg)](https://www.youtube.com/watch?v=eYBnTnn7fvA)

## Contributing:

Contributions are welcome! 🚀  
If you'd like to improve this project, please follow these steps:

1. **Fork** the repository.  
2. **Create a branch** (`git checkout -b feature-branch`).  
3. **Commit your changes** (`git commit -m 'Add new feature'`).  
4. **Push to the branch** (`git push origin feature-branch`).  
5. **Open a Pull Request** and describe your changes.

Make sure your code follows the existing style guidelines and passes all tests. 

## License:

This project is licensed under the [MIT License](LICENSE).
