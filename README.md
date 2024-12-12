# intro-nodejs

# Setup node project
`npm init`

# Install serve package
`npm install serve`

# Start a file server
`npx serve -p 5050 static`

# Create NPM Shell Commands
Add the following to `scripts` object in `package.json`  
```
"scripts" : { 
    "static": "serve -p 5050 static"
}
```
And run with:  
`npm run static`
