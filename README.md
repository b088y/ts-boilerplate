# TypeScript Starter

A simple TypeScript Node starter 

## Installation
Use Node 22

```
npm install
```

## Update dependencies

### 1. Update within existing semver ranges (safe)
This updates dependencies to the latest versions allowed by the current version ranges in `package.json`.

```bash
npm update
```
### 2. Upgrade to the latest versions (including majors)

If you want to update package.json itself to the absolute latest versions:
```bash
npx npm-check-updates -u
npm install
```

### 3. Update devDependencies (TypeScript included)
```bash
npm install --save-dev typescript@latest @typescript-eslint/eslint-plugin@latest @typescript-eslint/parser@latest

```

### 4. Verify updates before committing
```
npx npm-check-updates
```

---


# Learn TypeScript

Types are used by the TypeScript compiler to analyze our code for errors. A type commonly has properties and methods.

Types allow other engineers to understand what values are flowing around our codebase.

What is a type? A type is a shortcut to refer to the different properties and functions a value has. Source Udemy TypeScript: The Complete Developer's Guide.
In TypeScript, what has a type? Any value.

Why do we care about types? They give the TypeScript compiler information to analyze our code for errors.

Type Annotations. Code we add to tell TypeScript what type of value a variable will refer to.

Type Inference. Typescript tries to figure out what type of value a variable will refer to.

## IMPORTANT
When writing code, we want to avoid defining variables with 'any'. The point of TypeScript is to catch errors inside of our code editor which it does by knowing what types the variables are. If a variable is type 'any', TypeScript cannot do its job.

## Types in JavaScript
### Primitive types
- string
- number
- boolean
- null
- undefined
- void
- symbol


### Object types
- objects
- arrays
- functions
- classes

See [JavaScript types](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#javascript_types)



## Resources
[TypeScript docs](https://www.typescriptlang.org/)
[TypeScript Deep Dive](https://basarat.gitbook.io/typescript/)