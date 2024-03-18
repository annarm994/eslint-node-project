# eslint-node-project
Assignment 3

## Overview
This project is aimed at gaining hands-on experience in setting up and configuring ESLint in a Node.js project. ESLint is a powerful tool used to ensure code consistency and identify potential bugs by enforcing coding standards.

## Setup Instructions

1. **Initialize a New Node.js Project:**
   - Create a new directory for your project.
   - Navigate to this directory in your terminal.
   - Run `npm init` and follow the prompts to create a new `package.json` file.

2. **Install ESLint:**
   - Run the command `npm init @eslint/config` in your project directory.
   - Follow the setup prompts to install and configure ESLint.

3. **Exploring ESLint Configuration:**
   - After configuration, an `.eslintrc.js` file will be created in your project directory.
   - Open this file and examine the predefined rules.

4. **Modifying ESLint Rules:**
   - Change the rules for `(semi)` (semicolon usage) and `quotes` (quotation marks) in the `.eslintrc.js` file to fit your coding style preferences.

5. **Using Shareable Configs (Optional):**
   - Explore using shareable configs like `eslint-config-semistandard`.
   - Install a shareable config using `npm init @eslint/config --config eslint-config-semistandard`.

6. **Linting Your Code:**
   - Create a JavaScript file in your project.
   - Run ESLint on this file using `npx eslint yourfile.js`.
