# TS-NODE-TOOLING

### Create config files

 ```bash
    mkdir -p src .vscode &&  \
    touch -a .vscode/settings.json \
    .eslintrc.js .gitignore prettier.config.js \
    babel.config.js tsconfig.json vite.config.js
 ```
 
### Fill files

##### settings.json
 ```bash
   echo "$(curl -fsSL https://raw.githubusercontent.com/nereumelo/ts-node-tooling/main/.vscode/settings.json)" > .vscode/settings.json
```

##### .eslintrc.js
```bash
  echo "$(curl -fsSL https://raw.githubusercontent.com/nereumelo/ts-node-tooling/main/.eslintrc.js)" > .eslintrc.js
```

##### .gitignore
```bash
  echo "$(curl -fsSL https://raw.githubusercontent.com/nereumelo/ts-node-tooling/main/.gitignore)" > .gitignore
```

##### prettier.config.js
```bash
  echo "$(curl -fsSL https://raw.githubusercontent.com/nereumelo/ts-node-tooling/main/prettier.config.js)" > prettier.config.js
```

##### babel.config.js
```bash
  echo "$(curl -fsSL https://raw.githubusercontent.com/nereumelo/ts-node-tooling/main/babel.config.js)" > babel.config.js
```

##### tsconfig.json
```bash
  echo "$(curl -fsSL https://raw.githubusercontent.com/nereumelo/ts-node-tooling/main/tsconfig.json)" > tsconfig.json
```

##### vite.config.js
```bash
  echo "$(curl -fsSL https://raw.githubusercontent.com/nereumelo/ts-node-tooling/main/vite.config.js)" > vite.config.js
```


#### References:
[Set up Node.js project with Typescript, ESLint, and Prettier](https://blog.tericcabrel.com/set-up-a-nodejs-project-with-typescript-eslint-and-prettier)

[Vitest Docs](https://vitest.dev/guide/)
