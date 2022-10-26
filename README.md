## What is TypeScript
- Superset of JavaScript created by Microsoft
- Allows static strict typing
- Extra features - interfaces, enum, tuples, and generics
- Supports latest features like arrow function, let, and const .etc
- Based on the .NET harmony specification

## Install TypeScript
- Install Node.js in your machine
- Install Typescript compiler
```
npm i -g typescript
```

## To run a TypeScript file
```
tsc script.ts
```
After run this command, a JS file (script.js) will be generated in the project directory which will to have to add in the project by import or include.

## Generate tsconfig.json file
```
tsc --init
```
## Specify root directory to input files
Just uncomment ``` "rootDir" : "./example-directory" ``` and put the desired directory name here.

## To control output directory
Just uncomment ``` "outDir" : "./example-output-directory" ``` and put the output directory name here.


