# Alt-AI

Alt-AI is an open-source project aimed at providing a range of AI services, including an AI Bot, Image Generation, and AI-powered Image Restoration.

## Some Screenshots of Alt-AI

![Sign-up Page](screenshots/1.png)
![Imgae-Generation](screenshots/2.png)
![Restore-Dashboard](screenshots/4.png)

## Table of Contents

* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisties)
  * [Installation](#installation)
    
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#licesnse)

## Getting Started

### Prerequisties

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/) installed
- [npm](https://www.npmjs.com/) installed
- [MongoDB](https://www.mongodb.com/) installed

### Installation

Follow these steps to set up and run Alt-AI

1. **Clone the repository**
```sh
git clone https://github.com/codygeek01/Alt-AI.git
```

2. **Navigate to the client folder**
```sh
cd Alt-AI/client
```

3. **Install client dependencies**
```sh
npm install
```
5. **Navigate to the server folder**
```sh
cd ../server
```
6. **Install server dependencies**
```sh
npm install
```

7. **Start the client and the server**
- In the client folder
```sh
npm run dev
```

- In the server folder
```sh
npm start
```
## Usage

**Open the browser and go to http://localhost:5173** to access the Alt-AI application

Note: Make sure that MongoDB is running on your local machine or update the database configuration in the server code to connect to your MongoDB instance.

## Contributing

We welcome contribution from the community to make Alt-AI even better! To contribute, please follow these steps:

1. Fork this repository to your GitHub account.
2. Clone your forked repository to your local machine:
```sh
git clone https://github.com/codygeek01/Alt-AI.git
```

3. Create a new branch for your feature or bug fix:
```sh
git checkout -b feature-name
```

4. Make your changes and ensure that your code follows the project's coding guidelines.
5. Commit your changes with a descriptive commit message:
```sh
git commit -am "Add new feature"
```

6. Push your changes to your forked repository:
```sh
git push origin feature-name
```

7. Create a pull request:
- Go to the [original repository](https://github.com/codygeek01/Alt-AI.git).
- Click on "Pull Requests" and then "New Pull Request".
- Choose the main branch of the original repository as the base branch and your feature-name branch as the compare branch.
- Provide a clear title and description for your pull request.
8. I will review your contribution. Be prepared to address any feedback or suggested changes.

**Thank you for contributing to Alt-AI!**

## LICENSE

This project is licensed under the [MIT LICENSE](LICENSE).
