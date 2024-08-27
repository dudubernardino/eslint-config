# ESLint config

## Whats included?

- Standard config base;
- Typescript eslint;
- Prettier;

## Setup

### Node.js

Install dependencies:

```
npm i -D eslint @dudubernardino/eslint-config
```

Inside `.eslintrc.json`

```
{
  "extends": "@dudubernardino/eslint-config/node"
}
```

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @dudubernardino/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@dudubernardino/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```
