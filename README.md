## Step 1 - Add Vueform package

Move your vueform instance to `packages` folder. Eg: `./packages/vueform-0.0.0-YOUR_KEY`.

## Step 2 - Replace folder name in `package.json`

Open `package.json` and replace the following line with your actual folder name:

```
// package.json

{
  "dependencies": {
    "@vueform/vueform": "file:./packages/vueform-VERSION-KEY",
    // ...
  },
  // ...
}
```

## Step 3 - install dependencies

Run `npm install` to install dependencies.

## Step 4 - run development server

Run `npm run serve` to start the development server.