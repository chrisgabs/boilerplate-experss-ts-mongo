# REST API Boilerplate

A Typescript Express API boilerplate that utilizes mongoDB as database and chalk for logging.

## Configuration

Create a .env file for mongo db credentials.

```json
MONGO_USERNAME = name
MONGO_PASSWORD = password

SERVER_PORT = 1337
```

Boilerplate uses prettier with the following configuration:

```json
{
    "printWidth": 200,
    "tabWidth": 4,
    "jsxBracketSameLine": false,
    "semi": true
}
```

.vscode settings.json configuration:

```json
{
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.bracketPairColorization.enabled": true,
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true,
    "editor.wordWrap": "off",
    "dotenv.enableAutocloaking": false
}
```