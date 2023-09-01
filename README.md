# aleodoni-fullstack ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D @aleodoni-fullstack/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@aleodoni-fullstack/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D @aleodoni-fullstack/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@aleodoni-fullstack/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D @aleodoni-fullstack/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@aleodoni-fullstack/eslint-config/node"
}
```