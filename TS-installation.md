# Type Script Notes

## Installation

Install typescript globally 

`npm install -g typescript`

Create a typescript file in your project(Ex :- app.ts)

Compile your code :- 

```bash
tsc app.ts
```

The compiler creates app.js file.

### To update the html file automatically:- 

Install dependency:-

```bash
npm init
npm install --save-dev lite-server
```

In the package.json file, add the following code to scripts

```
"start": "lite-server"
```

Keep the following code running in the terminal

```
npm run start
```





