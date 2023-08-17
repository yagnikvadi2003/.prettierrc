[![Prettier Banner](https://unpkg.com/prettier-logo@1.0.3/images/prettier-banner-light.svg)](https://prettier.io)

<h3 align="center">Prettier</h3>

<p align="center">
  The `.prettierrc` file configures code formatting standards. Its structured settings ensure a consistent and professional code style, enhancing readability and collaboration.
  <br>
  <br>
  🔹
  <a href="https://github.com/yagnikvadi2003/prettier/issues">Report bug</a>
  🔹
  <a href="https://github.com/yagnikvadi2003/prettier/pulls">Pull requests</a>
</p>

<br />


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this application locally, follow these steps:

1. Install the package in your typescript react project:
   ```bash
   yarn add prettier -D
2. Start the development server:
    ```bash
    yarn run dev
Open your web browser and visit `http://localhost:5173/` to access the application

## Usage

The `.prettierrc` file is a key tool for maintaining consistent code formatting across your project. Each configuration option serves a specific purpose in achieving a professional and readable codebase.

### Configuration Overview
Below is an explanation of the configuration settings in your `.prettierrc` file:

- **printWidth:** Limit each line's length to 100 characters for improved readability.
- **tabWidth:** Set the tab width to 4 spaces, aiding in consistent indentation.
- **useTabs:** Utilize tabs for indentation, facilitating adherence to coding standards.
- **semi:** Enforce semicolons at the end of statements for code consistency.
- **singleQuote:** Avoid single quotes, promoting uniformity in string representation.
- **quoteProps:** Quote object properties only if needed, enhancing code clarity.
- **jsxSingleQuote:** Maintain consistency by using double quotes for JSX attributes.
- **bracketSpacing:** Add spaces inside brackets for improved visual separation.
- **bracketSameLine:** Place multiline object/array brackets on separate lines for cleaner code.
- **arrowParens:** Omit parentheses around single arrow function arguments.
- **insertPragma:** Prevent insertion of a @format pragma comment.
- **proseWrap:** Wrap prose-style text, such as comments, to adhere to formatting.
- **htmlWhitespaceSensitivity:** Apply CSS rules for HTML whitespace handling.
- **endOfLine:** Automatically detect and set the appropriate end-of-line character.
- **parser:** Specify the parser to be used for TypeScript code.

### Integration into Workflow

- **Create `.prettierrc`:** In your project's root directory, create a `.prettierrc` file.
- **Customize Settings:** Copy the provided configuration settings into the .prettierrc file.
- **Formatting with Prettier:** Use Prettier to format your code by running:

   ```bash
    npx prettier --write "src/**/*.ts" "src/**/*.tsx"
This command formats TypeScript and JSX files in the `src` directory.

- **Editor Integration:** Enable automatic formatting in your code editor by installing a Prettier plugin.

### Benefits of Configuration
- **Uniform Style:** Consistent code formatting improves readability and collaboration.
- **Automated Workflow:** Automate formatting tasks to maintain code quality efficiently.
- **Clearer Codebase:** Properly formatted code enhances codebase clarity and comprehension.
- **Adherence to Standards:** Enforce coding standards across the team, minimizing inconsistencies.

### Customization
Adjust the configuration settings to match your project's specific coding guidelines and style preferences.

### Conclusion
By applying the configuration settings from your .prettierrc file, you establish a foundation for maintaining professional, consistent, and easily readable code throughout your project.


## Features

The `.prettierrc` file is a powerful tool that empowers developers to maintain a consistent and professional codebase through automated formatting. This section highlights the key features and advantages it brings to your development workflow.

- **Consistent Code Style** `.prettierrc` enforces a uniform coding style across the entire project. Regardless of team size or collaboration, your code will consistently adhere to the established formatting rules.

- **Readable and Maintainable Code** Formatted code is more readable, leading to easier comprehension and maintenance. Clear indentation, spacing, and line lengths contribute to a codebase that's easy to work with.

- **Automated Formatting** By integrating Prettier into your workflow, you can automatically format your codebase. This eliminates manual formatting efforts and ensures that code is consistently styled.

- **Configurable Options** The flexibility of `.prettierrc` allows you to configure various formatting options. Customize settings such as indentation, line length, and quote styles to match your project's requirements.

- **Integration with Editors and IDEs** Prettier offers integrations with popular code editors and IDEs. This means you can format your code seamlessly without leaving your development environment.

- **Version Control Compatibility** Formatted code is more version control-friendly. Because formatting is consistent, code changes are isolated to logical edits, reducing unnecessary noise in version history.

- **Ease of Onboarding** New team members can quickly adapt to the project's coding style, thanks to automated formatting. This accelerates the onboarding process and reduces the learning curve.

- **Cross-Language Support** Prettier supports various programming languages beyond JavaScript and TypeScript, making it a versatile tool for projects with diverse codebases.

- **Continuous Code Quality** By integrating Prettier into your CI/CD pipelines, you can ensure that every commit adheres to the established formatting rules, maintaining code quality over time.

- **Customizable for Project Needs** `.prettierrc` configuration can be tailored to your project's specific coding standards and style preferences, ensuring a balance between convention and customization.

- **Community-Driven Tool** Prettier is a widely adopted tool in the developer community. Its popularity ensures ongoing updates, support, and improvements.

- **Time and Effort Savings** Automated formatting reduces the time and effort spent on manual code cleanup. Developers can focus on writing code and solving problems, rather than worrying about formatting.

- **Consistent Documentation** Well-formatted code often translates to well-documented code. Clear formatting enhances the visibility of comments and explanations within your codebase.

- **Enhanced Collaboration** A consistent code style improves collaboration among team members. Developers can review, understand, and contribute to code more effectively.

- **Maintainable Styling Across Environments** `.prettierrc` ensures that code maintains its style across different development environments and systems, preserving its readability and professionalism.

## Contributing

While this prettier is a representation of my personal projects and achievements, I'm always open to feedback and suggestions. If you have ideas for improvements or notice any issues, feel free to reach out or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
