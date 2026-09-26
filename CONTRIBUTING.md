# Contributing to CalPal

Thank you for your interest in contributing to CalPal. CalPal is an open-source nutrition, fitness, and food budgeting project designed primarily for college students. Contributions of all sizes are welcome, including bug fixes, new features, documentation improvements, testing, and user interface improvements.

## How to Contribute

Before starting work, check the project's GitHub Issues page to see if the problem or feature has already been discussed.

For an existing issue, leave a comment indicating that you would like to work on it. For larger changes or new features, open an issue first so the idea can be discussed before significant development work begins.

To contribute code:

1. Fork the CalPal repository.
2. Clone your fork to your computer.
3. Create a new branch for your change.
4. Make and test your changes.
5. Commit your work with a clear commit message.
6. Push the branch to your fork.
7. Open a pull request against CalPal's `main` branch.

Keep pull requests focused on one feature, bug, or improvement whenever possible. The pull request should briefly explain what was changed and why.

## Development Setup

Clone the repository and enter the project directory:

```bash
git clone https://github.com/NAU-OSS/CalPal.git
cd CalPal
```

Install the required dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

The server runs locally on port `4000` by default.

## Code Style and Formatting

Contributors should follow the style already used throughout the CalPal project.

When contributing code:

- Use clear and descriptive variable and function names.
- Keep formatting consistent with surrounding code.
- Use comments when code behavior may not be immediately clear.
- Avoid unrelated changes in the same pull request.
- Keep functions and changes focused on a specific purpose.
- Do not commit passwords, API keys, credentials, or other private information.

Readable and maintainable code is preferred over unnecessarily complicated solutions.

## Testing

All changes should be tested before a pull request is submitted.

At minimum, contributors should verify that:

- The application starts successfully.
- Existing functionality affected by the change still works.
- The new feature or bug fix works as intended.
- The change does not introduce obvious errors in related functionality.

If automated tests exist for the area being changed, those tests should also pass. Contributors adding significant new functionality are encouraged to add appropriate tests when possible.

In the pull request, briefly explain how the change was tested.

## Documentation Standards

Changes that affect how CalPal is installed, configured, or used should include corresponding documentation updates.

Documentation should:

- Use clear and understandable language.
- Accurately describe the current behavior of the project.
- Include examples when they make a feature easier to understand.
- Keep the README and other project documentation consistent with the code.

Documentation-only contributions, such as fixing unclear instructions or correcting errors, are also welcome.

## Reporting Bugs

Bugs should be reported through GitHub Issues:

https://github.com/NAU-OSS/CalPal/issues

Before creating a new issue, check existing issues to make sure the problem has not already been reported.

A useful bug report should include:

- A clear description of the problem.
- Steps needed to reproduce it.
- What you expected to happen.
- What actually happened.
- Relevant browser or environment information.
- Screenshots or error messages when useful.

Providing enough information to reproduce a bug makes it easier for contributors to investigate and fix it.

## Proposing New Features

Feature ideas should also be submitted through GitHub Issues.

A feature request should explain the problem the feature would solve, who would benefit from it, and how the proposed feature might work.

For substantial changes, contributors should wait for feedback before beginning major development. This helps prevent multiple people from doing the same work and makes sure proposed features fit the goals of CalPal.

## Pull Request Review

Project maintainers will review pull requests before they are merged. Review may include checking functionality, readability, documentation, and whether the change fits the goals of CalPal.

Maintainers may request changes before accepting a pull request. Feedback should be treated as part of the collaborative development process.

## Community Guidelines

CalPal should be a welcoming project for contributors with different backgrounds and experience levels.

Contributors are expected to:

- Communicate respectfully.
- Provide constructive feedback.
- Be patient with new contributors.
- Respect different ideas and viewpoints.
- Keep technical disagreements focused on the project rather than individuals.
- Help maintain a productive and welcoming environment.

Questions are welcome, and contributors should not be discouraged because they are unfamiliar with part of the project.

Project discussions should normally take place publicly through GitHub Issues and pull requests so that other contributors can participate and learn from previous discussions.

## Getting Started as a New Contributor

New contributors should look through the project's GitHub Issues for a small task that matches their experience. Issues labeled `good first issue` are intended to provide an easier starting point.

Documentation improvements and small bug fixes are also good ways to become familiar with CalPal before working on larger features.

Thank you for helping improve CalPal.
