# Install
```
npm i --save-dev eslint-config-memcrab
```

Add to the tsconfig next lines
```json
  "parserOptions": {
    "project": [
      "./tsconfig.json"
    ]
  },
```

If using npm 5+, use this shortcut
```
npx install-peerdeps --dev eslint-config-memcrab
```

If not 
```
npm i --save-dev eslint eslint-plugin-no-loops @typescript-eslint/parser eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-jsdoc @getify/eslint-plugin-proper-arrows @typescript-eslint/eslint-plugin
```
