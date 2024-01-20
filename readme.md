# TypeScript Demo

This project is a playground you can use to learn and better understand TypeScript.

## Using

1. Clone this GitHub repository to your computer

   ```sh
   git clone https://github.com/craigmckeachie/typescriptdemo
   ```

1. Open your terminal of choice
1. In the terminal, change your current directory to `typescriptdemo`

   ```sh
   cd typescriptdemo
   ```

1. Start the TypeScript compiler (tsc) in watch mode
   ```sh
   npm start
   ```
   > Note this command runs the npm start script `tsc --watch`
1. Open a NEW terminal window
   > Be sure to leave the terminal running the compiler open and running
1. In the new terminal, change your current directory to `typescriptdemo`
   ```sh
   cd typescriptdemo
   ```
1. Run the JavaScript code output by the TypeScript compiler
   ```sh
   node program.js
   ```

## How to create your own playground

1. Open terminal and run the following commands:

   ```sh
   mkdir typescriptdemo
   cd typescriptdemo
   npm install typescript
   ```

1. Open `typescriptdemo` in `VS Code` or your editor of choice
1. Add the start script
   ```diff
    "scripts": {
   +   "start": "tsc --watch"
     },
   ```
