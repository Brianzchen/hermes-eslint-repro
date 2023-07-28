# hermes-eslint-repro

Showcasing that eslint with parser of hermes-eslint fails to parse syntax in `./src/index.js`

```
export * as routes from './routes';
```

After installing dependencies, try `npx eslint .` which will fail but `npx flow` works as expected.

![screenshot](./Screenshot%202023-07-28%20at%209.28.53%20pm.png)
