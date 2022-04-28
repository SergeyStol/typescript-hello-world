# Type script hello-world application
https://www.typescripttutorial.net/typescript-tutorial/typescript-hello-world/

## Prerequisites
- node.js (https://nodejs.org/en/download/)
- TypeScript(https://www.typescriptlang.org/download) 
  - `npm install -g typescript`

## Optional
- ts-node (https://www.typescripttutorial.net/typescript-tutorial/setup-typescript/)
  - `npm install -g ts-node`

## For creating new TypeScript project
1. Create a new TypeScript file called `app.ts`
2. Add code 
    ``` typescript
      let message: string = 'Hello, World!';
      console.log(message);
    ```
3. `tsc app.ts`, `node app.js` or `ts-node app.ts` 