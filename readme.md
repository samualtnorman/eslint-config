# Samual's ESLint Config (`@samual/eslint-config`)
Use this if you want your code to look like my code.

## Install
```sh
npm install --save-dev @samual/eslint-config
```

## Setup
### JavaScript
`.eslintrc`
```json
{
	"root": true,
	"extends": "@samual/eslint-config"
}
```

### Typescript
`.eslintrc`
```json
{
	"root": true,
	"extends": "@samual/eslint-config",
	"parserOptions": { "project": [ "./tsconfig.json", "./src/tsconfig.json" ] }
}
```

`src/.eslintrc`
```json
{
	"extends": "@samual/eslint-config/typescript.yml"
}
```
