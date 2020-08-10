# Introduction to JavaScript and TypeScript

This is the class starter project for learn JavaScript and TypeScript. We will use this project to explore JavaScript and TypeScript.

## Instructions

1. Open a termina window, and clone this repository to the folder of your choice. Specify whatever FOLDER_NAME you would like.

```bash
git clone https://github.com/ericwgreene/js-ts-starter-app.git FOLDER_NAME
```

2. Change into the folder.

```bash
cd FOLDER_NAME
```

3. Install the NPM Packages.

```bash
npm install
```

4. For your editor, please install the TSLint extension.

5. To run the application, you will need two terminal sessions. In the first terminal session, run the following command:

```bash
npm start
```

This first terminal session will run the web server, but TypeScript type checking is not occuring.

6. In the second terminal window, run the following command:

```bash
npm run typecheck
```

This second terminal will run in "watch" mode and report TypeScript compilation errors. These errors along with the errors and warnings reported by TSLint in your editor will help you resolve strong typing issues.