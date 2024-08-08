
# Vue 3 Application Template

## Prerequisites:


-   [Node.js](https://nodejs.org/)  >= 18

## Setup and Development Flow:


1.  Install dependencies  `npm install`
2.  Prepare  [Husky](https://typicode.github.io/husky/)  for git hooks  `npm run prepare`
3.  Create  `.env.local`  for local development and define `tip-tap` token
4.  Start the development server  `npm run dev`
6.  Build the application  `npm run build`

## Technical Stack:

-   [Vue 3](https://vuejs.org/)
-   [Vite](https://vitejs.dev/guide/)

## Package Managers:

[](https://github.com/asinnws/vue3-feature-sliced-starter#package-managers)

-   npm

## Code Quality:

-   [ESLint](https://eslint.org/)
-   [Stylelint](https://stylelint.io/user-guide/get-started)
-   Git hooks ([Husky](https://typicode.github.io/husky/))
-   [Prettier](https://prettier.io/)

## Commands

`npm install`

Installs dependencies

`npm run dev`

Starts local dev server at the port specified in  [vite config](https://github.com/asinnws/vue3-feature-sliced-starter/blob/main/vite.config.ts)

`npm run build`

Builds the project

`npm run preview`

Starts local server to serve  `dist`  folder on the specified port

`npm run format`

Formats the codebase using Prettier

`docker compose up`

Builds docker container

`npm compose down`

Destroys docker container
