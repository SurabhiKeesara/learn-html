## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
The action attribute defines where the HTTP request from the form submit button is sent.
2. What is the purpose of the _method_ attribute in the _form_ tag?
The method attribute defines the type of HTTP request to make on submit.
3. What is the purpose of the _name_ attribute in the _input_ tag?
The name attribute of input defines the key of user input. On submit, the form content is sent to the provided action url in the form of a JSON, and name is the key value.
4. What is the purpose of the _type_ attrbute in the _input_ tag?
The type attribute refers to what the user input type is (can also be a checkbox, radio button, etc). Password is a type that hides input characters
5. What is the purpose of the _label_ tag?
The label tag is a text tag (in a form) that hints to users what each input corresponds to.

6. What is the purpose of the _required_ attribute?
The required attribute indicates that a given input must be provided by users before the submit action can be executed.