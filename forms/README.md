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
Answer:  The action attribute gives the information where do we want to send the form data when the form is submitted. 
         So the value of the action is the page that will process the form.


2. What is the purpose of the _method_ attribute in the _form_ tag?
Answer: The method attribute in an HTML form specifies the HTTP method to be used when the form is submitted.
        The two most commonly used methods are "GET" and "POST".


3. What is the purpose of the _name_ attribute in the _input_ tag?
Answer: The name attribute is used to reference elements, or to reference form data after a form is submitted.
        Only form elements with a name attribute will have their values passed when submitting a form.


4. What is the purpose of the _type_ attribute in the _input_ tag?
Answer: The type attribute specifies the type of input that will be taken for eg. Text, password, checkbox, file etc. 


5. What is the purpose of the _label_ tag?
Answer:  The label tag is used to assign different labels for several form elements. 


6. What is the purpose of the _required_ attribute?
Answer: The required attribute specifies that an input field must be filled out before submitting the form.

