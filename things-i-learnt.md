BUILDING AN API

1. cd into 02_expressjs
2. run "npm init -y" which initializes a new package.json file
3. to make this an express app, go ahead and run "npm install express"
3. under scripts remove the test script and add a dev script in the package.json file.
4. we go back into 01, and remove the hhtp server function we wrote and replace with and express server fctin
 ref: server.js; 
 this is what a route looks like "
app.get('/', (req, res) => {
    
})
"
5. for you to get the serve to run correct you need to go into the package.json and chage the type from commonjs to module.
