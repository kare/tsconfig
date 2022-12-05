# @kare/tsconfig

> Shared [Typescript build config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for Kare's projects.

## Install

```bash
npm install --save-dev @kare/tsconfig
```

*This config requires TypeScript 4.9 or later.*

## Usage

`tsconfig.json`

```json
{
	"extends": "@kare/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "ES2022"
	}
}
```
