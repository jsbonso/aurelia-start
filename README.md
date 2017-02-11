# Overview
An Aurelia seed project which contains all the required files that 
helps you create your own Hello World Aurelia Application

# Create your "Hello World" application

1. First create a TypeScript file named: **app.ts** 
2. Then copy and paste this code to the file:
```
export class App {
  msg = "Hello World!";  
}
```

3. Create an HTML file named: **app.html**
4. Afterwards, copy and paste this code: 
```
<template>
  <h1>${msg}</h1>
</template>
```

# How to Run

You can run this in any HTTP server that you prefer.
If you have NodeJS and NPM installed, you can add a HTTP-Server by running these commands:

   sudo -i
   npm install http-server -g
  
Afterwards, run this:

   http-server -o -c-1

Then open your browser and go to:

   http://127.0.0.1:8080/