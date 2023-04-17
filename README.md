# Steps that I followed to create this project:

### Install pnpm globaly

`npm install -g pnpm`
If you are using `nvm` the pnpm will be linked to the current `node` version that you are using.

### Create a default pnpm `package.json` at the root level

`pnpm init`

### Adjust the `package.json` and add `.gitignore`

We can delete the `"main": "index.js",` line because each app will live in its respective folder. Add the files you want to ignore to the `.gitignore`

###
