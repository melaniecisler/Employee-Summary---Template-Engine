# Employee-Summary---Template-Engine
This app builds a Node CLI that takes in information about employees and generates an HTML webpage that displays summaries for each person. The file contents also ensure that all unit tests pass.

# Template Engine - Employee Summary

This app builds a Node CLI that takes in information about employees and generates an HTML webpage that displays summaries for each person. The file contents also ensure that all unit tests pass.

# Install 

In the `Develop` folder, there is a `package.json`, so make sure to `npm install`.  Use the Inquirer npm package to prompt user for  their email, id, and specific information based on their role with the company. For instance, an intern may provide their school, whereas an engineer may provide their GitHub username.

# Run

To run use node app.js

# Test 

You can run the tests at any time with `npm run test`. Be sure to make this command in the root.

# Contributions

By Melanie Cisler

# Questions

Direct any follow up questions to github.com/melaniecisler or melanie.cisler@yahoo.com

Link to video demo: https://drive.google.com/file/d/1Xn8IcYMc9NbSmsals1Cyx2Vgx8seQ5_w/view

# Directory Structure

```
lib/           // classes and helper code
output/        // rendered output
templates/     // HTML template(s)
test/          // jest tests
  Employee.test.js
  Engineer.test.js
  Intern.test.js
  Manager.test.js
app.js         // Runs the application
```

