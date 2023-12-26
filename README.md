# AUTHENTICATION - PASSPORT JS

Passport.js is a popular authentication middleware for Node.js applications. It is designed to be flexible and modular, allowing you to implement various authentication strategies, including local (username/password), Google, Facebook, and many others. 

## Technologies Used
  - [Node.js](https://nodejs.org/)
  - [Express](https://expressjs.com/)

- **Database:**
  - [MongoDB](https://www.mongodb.com/)

- **Other Tools:**
  - [Git](https://git-scm.com/)
  - [GitHub](https://github.com/)
  - [VSCode](https://code.visualstudio.com/)

## Getting Started
### Prerequisites

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js; npm v6.14.6 or higher recommended)
- [MongoDB](https://www.mongodb.com/) (v4.0 or higher)
- [Your preferred web browser](https://www.google.com/chrome/)

> Note: Make sure to install the specified versions or higher to avoid compatibility issues.

To check if you have Node.js and npm installed, run the following commands in your terminal:

```bash
node --version
npm --version
```
## How To Run
Create the file `passport-js-authentication/config.env` with your Atlas URI and the server port:
```
MONGO_URL = your mongoDb url either from atlas or from localhost shell
```
If you are going Authenticate with Facebook and Google Through PassportJs Stratgy...
```
GOOGLE_CLIENT_ID = your google app clint id
GOOGLE_CLIENT_SECRET = your google app client secret
FACEBOOK_CLIENT_ID = your facebook app clint id
FACEBOOK_CLIENT_SECRET = your facebook app client secret
FRONTEND_DOMAIN = you react app url with port
SESSION_SECRET = anything you want
```
Start server i.e., BackEnd:
```
cd passport-js-authentication
npm install
npm start
```
## Disclaimer
Use at your own risk; not a supported MongoDB product

## Contributing
We appreciate your interest in contributing to our project! Whether you're a developer, designer, or enthusiast, we welcome your contributions. This guide outlines the process and guidelines for making your contributions.
## Getting Started

1. Fork the repository.
2. Clone your forked repository:
 ```bash
   git clone https://github.com/john12356/passport-js-authentication.git
```
## Issues and Bug Reports

- For bug reports, include details such as the operating system, browser version, and steps to reproduce the issue.
- Check for existing issues before opening a new one.
- Clearly describe the problem and provide any relevant error messages.
- Include screenshots or code snippets if they help explain the issue.

## License
### License

This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
## Acknowledgments

We greatly appreciate all contributions to this project. Contributors will be acknowledged in our [CONTRIBUTORS.md](CONTRIBUTORS.md) file. Thank you for your support!

## Feedback

For any queries and improvements please reach out to johnmoorthi85131@gmail.com

## Thank You

We appreciate your interest in our project and hope that you find it useful. Your contributions and adherence to the project's license are valuable to us.


