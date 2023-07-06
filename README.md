This is a Next.js app set up with prettier, and prettier-tailwind.

To use this:
  1) Run the official create-next-app to get the latest version of a NextJs app.
  2) Copy the devDependencies in package.json and the whole .eslintrc.json to your newly generated backbone.
  3) Enjoy.

Note: If your are not using Tailwind for your project, you can remove prettier-tailwind from .eslintrc.json

# Getting Started

First, run the development server:

```
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

To format your code:
```
npx prettier --write .
```
or
```
npx prettier --write [file/folder path]
```

To format your code based on code quality:
```
npx eslint src/**
```
# Best Practice(For Javascript) Checklist

### UI
1. Choose a UI Framework: MUI, Tailwind, Chakra
2. Use 	[Storybook]([https://www.example.com](https://storybook.js.org/)https://storybook.js.org/) to create and manage your UI.

### Code
1. Remove any unused files, imports and package from the project.
2. Use comments to indicate what a part of your code is doing.
3. Use a state management tool to make your life easier by separating states, states actions and UI: Context, Zustand, Jotai, Recoil are all good choices.
4. Run prettier and eslint periodically when you are done with your stuffs.
5. Use consistent naming conventions across your codes, snake_case, PascalCase, camelCase doesn't matter as long as they stay consistent.

### Build and Test
1. NPM Scripts (`scripts` in package.json) can be the most basic unit of your CI/CD process. Use scripts to simplify multiple lines of commands that run build, tests and start development server, or deploy to cloud(Vercel, Firebase).
2. Use testing framework like Playwright(Recommented), Pupetter or (Jest + react-testing-library) for E2E integration test if you are doing frontend. Use Jest if you are doing REST APIs, or unit testing for specific functions.
