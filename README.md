This is a Next.js app set up with prettier, and prettier-tailwind.

To use this:
  1) Run the official create-next-app to get the latest version of a NextJs app.
  2) Copy the devDependencies in package.json and the whole .eslintrc.json to your newly generated backbone.
  3) Enjoy.

## Getting Started

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
