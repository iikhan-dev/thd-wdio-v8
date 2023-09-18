# Home Depot Canada WebDriverIO Project

This WebDriverIO project is designed for automated testing of the Home Depot Canada website. It leverages the power of WebDriverIO, a JavaScript-based automation framework, and MochaBDD to test various functionalities of the website, ensuring that it performs as expected.

This project was developed by Ismail Khan. Github: https://github.com/iikhan-dev

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Writing Tests](#writing-tests)
- [Running Tests](#running-tests)
- [Reporting](#reporting)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you begin, make sure you have the following installed:

- Node.js: Install it from [nodejs.org](https://nodejs.org/).
- npm (Node Package Manager): This comes with Node.js installation.

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/iikhan-dev/thd-wdio-v8.git
   ```

2. Navigate to the project directory:

   ```bash
   cd thd-wdio-v8
   ```

3. Install project dependencies:

   ```bash
   npm install
   ```

## Configuration

1. Configure your test environment in the `wdio.conf.js` file. This project currently runs on Chrome only. https://www.homedepot.ca/ is the BASE_URL.

2. A collection of tests can be found in /test/specs.

## Running Tests

Execute your tests using the following command:

```bash
npm test
```

This command will run WebDriverIO and execute all the test scripts specified in your configuration.

## Reporting

WebDriverIO generates detailed test reports by default. You can find them in the `allure-results` directory. To view the report, you need to install Allure command-line tools. You can find more information on setting up Allure reporting [here](https://docs.qameta.io/allure/).

## Contributing

We welcome contributions to this project. If you find issues or have suggestions for improvements, please create a GitHub issue or submit a pull request.

## License

This project is licensed under the [ISC License](LICENSE.md).