# Dashtoon

This is a Dashtoon page exercise. It is an exercise, not a product I shipped.

## Run

```bash
git clone https://github.com/LifeAyush/dashtoon.git
cd dashtoon
npm install
npm start
```

The page calls a Hugging Face endpoint. Put the token in a `.env` file as `REACT_APP_HF_TOKEN` and do not commit that file.

`npm start` runs the page locally. Other scripts from `package.json`:

- `npm test` runs the tests.
- `npm run build` creates the production bundle.
- `npm run deploy` publishes the `build` folder. The `predeploy` script runs `npm run build` first.
