# TypeScript Cheat Sheet
- [Setup](#setup)
  - [Install globally](#install-globally)
  - [Check version](#check-version)
  - [Create tsconfig.json file](#create-tsconfig.json-file)
- [Compiling](#compiling)
  - [Compile TS file](#compile-ts-file)
  - [Compile with specified name or path](#compile-with-specified-name-or-path)
  - [Watch file](#watch-file)
  - [Watch all](#watch-all)

## Setup
### Install globally
```
npm i -g typescript
```
### Check version
```
tsc -v
```
### Create tsconfig.json file
```
tsc --init
```

## Compiling
### Compile TS file
Will compile into JS file of same name and same directory
```
tsc index.ts
```
### Compile with specified name or path
```
tsc index.ts --outfile output/script.js
```
### Watch file
```
tsc index.ts -w
```
### Watch all
tsc will compile all TS files in rootDir and output in outDir
```
tsc -w
```
