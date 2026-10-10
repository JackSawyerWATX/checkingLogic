# Checking Logic

Checking Logic is a small JavaScript example that demonstrates evaluating boolean values and numeric comparisons with `if...else` statements. Running the script reports whether Jack is a pilot, enjoys the outdoors, and is old enough to drive.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Security](#security)
- [How to Contribute?](#how-to-contribute)
- [What's Next?](#whats-next)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Author](#author)

## About

This project provides a concise example of control flow in JavaScript. It stores facts about a person in variables, checks those values with conditional statements, and writes applicable messages to the console.

## Features

- Checks a boolean value to identify whether Jack is a pilot.
- Conditionally reports whether Jack enjoys the outdoors.
- Uses a numeric age comparison to determine driving eligibility.
- Demonstrates both `if` and `if...else` control flow.

## Tech Stack

- JavaScript
- Node.js runtime for executing the script

## Architecture

The project uses a single-file architecture:

1. Variables define the sample facts.
2. Conditional statements evaluate each fact.
3. Matching outcomes are logged to the console.

## Project Structure

```text
checkingLogic/
├── README.md
└── script.js
```

## Getting Started

### Prerequisites

Install [Node.js](https://nodejs.org/).

### Run the project

From the project root, run:

```bash
node script.js
```

The script prints messages for each condition whose criteria are met.

## Configuration

No external configuration, environment variables, or dependencies are required. Update the values in `script.js` to experiment with different conditional outcomes.

## Security

This example does not process user input, store data, make network requests, or use credentials. If it is extended to accept external input, validate and sanitize that input before using it.

## How to Contribute?

1. Fork the repository.
2. Create a branch for your change.
3. Make and test your updates locally.
4. Open a pull request describing the change and its expected behavior.

## What's Next?

- Add examples for comparison and logical operators.
- Accept sample values through command-line arguments.
- Add automated tests for expected console output.
- Expand the examples to cover nested and compound conditions.

## License

No license has been specified for this repository. Add a license file before distributing or reusing the project.

## Acknowledgements

- [Node.js](https://nodejs.org/) for providing the JavaScript runtime.

## Author

Jack Sawyer
