# Lambda Generator

This is a generator that creates a very simple lambda template based on user input. Properties specified in the template are:
 - General lambda settings (name, memory, runtime etc.)
 - Lambda Log Group
 - API Gateway
 - Alarms
 
## Usage

 - Clone the project
 - Run ```npm install```
 - Navigate to project directory ```cd lambda-generator```
 - Run ``` sudo npm link```
 - Run ```npx yo lambda``` to execute the generator
 - Once all the questions have been answered, your template will be stored in 'deploy/stacks/main.yml`
 

