# Web-Registration
Using HTML, CSS &amp; JS built one Registration Form


Three user inputs: Username, Password, and telephone number
Requirements: 
  Username and Password: need to have length between 6 and 12 letters
  Telephone number: need to have 11 number length and the first number need to be 1


What I did: 
  1. Get the input of username input: document.getElementById("username");
  2. Connect the onblur case : usernameInput.onblur = checkUsername;
  3. Regular expression: var reg = /^\w{6,12}$/; 
                         var reg = /^[1]\d{10}$/;
                         var flag = reg.test(tel);
                         
  4.document.getElementById("tel_err").style.display = 'none';
