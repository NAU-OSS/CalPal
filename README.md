# CalPal

CalPal is a web-based nutrition, fitness, and food budgeting application designed primarily for college students. The project helps users keep track of what they eat, understand their nutritional intake, manage food-related expenses, and work toward personal health goals.

College students often have to balance nutrition, convenience, cost, and fitness while also managing a busy academic schedule. These areas are usually handled separately, which can make it difficult to understand the relationship between eating habits, nutrition goals, and spending. CalPal was created to bring these tools together in one application.

## Features

CalPal is designed around several major features:

- Track daily calorie intake
- Track macronutrients and nutrition goals
- Record meals and commonly eaten foods
- Monitor food costs and personal food budgets
- Account for dietary restrictions and allergies
- Track personal health and fitness goals
- Provide access to useful food and campus dining information

The project also uses a Node.js and Express server to support requests for external food and dining information.

## Installation

### Prerequisites

Before installing CalPal, make sure you have:

- Git
- Node.js
- npm

### Clone the Repository

Clone the project from GitHub:

```bash
git clone https://github.com/NAU-OSS/CalPal.git
cd CalPal
```

Install the required Node.js packages:

```bash
npm install
```

Start the server:

```bash
npm start
```

The server runs locally on port `4000` by default.

## Usage

After installing the required dependencies and starting the server, open the CalPal web application locally.

Users can use CalPal to record and review information related to their food choices. For example, a student can track the foods they eat during the day, compare their intake with calorie or macronutrient goals, and keep track of how much they are spending on food.

A typical development session can be started with:

```bash
npm start
```

The application can then communicate with the local CalPal server at:

```text
http://localhost:4000
```

## Project Status

CalPal began as an undergraduate software engineering group project and is now being developed as an open-source project.

The project has a working foundation, but it is still open to improvement. Existing features can be refined and additional functionality can be added by future contributors.

## Roadmap

Current and future areas of development include:

- Improving calorie and macronutrient tracking
- Improving food cost and budget tracking
- Expanding support for dietary restrictions and allergies
- Improving frequently eaten food tracking
- Improving the user interface and overall usability
- Adding additional testing and documentation

Development priorities may change as contributors identify bugs, suggest improvements, and add new features. Current development tasks can be found on the project's GitHub Issues page.

## Contributing

CalPal is an open-source project and contributions are welcome.

Contributors can help by fixing bugs, improving documentation, testing existing functionality, improving the interface, or developing new features.

Before making a contribution, review the repository's contribution guidelines and existing GitHub Issues. New contributors are encouraged to begin with smaller issues when available.

## Community and Support

Questions, bug reports, and feature suggestions can be submitted through the CalPal GitHub Issues page:

https://github.com/NAU-OSS/CalPal/issues

The main project repository is available at:

https://github.com/NAU-OSS/CalPal

Using GitHub Issues keeps project discussions public so that users and contributors can find previous questions, follow development, and participate in improving the project.

## License

CalPal is released under the Unlicense. This allows the project to be freely used, modified, distributed, and built upon.

See [license.md](license.md) for the complete license text.

## Authors

CalPal was originally developed as a student software engineering project by:

- Logan Bankert
- Rita Bolanos
- Annaliese Dedmore
- Isidro Marquez
- Nile Ham
- Luke Flaker

The project is now open to contributions from the open-source community.