# Ex.08 Customer Registration Form
## AIM
  To write a program in JavaScript for creating a customer registration form for an agro-based company.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define different functions to register the customers based on their qualifications.

### STEP-3
  Using form elements to create the registration details of a customer.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<script src="registration-form"></script>
</head>
<body onload="Customer Registration Form();">
<body style="background-color:pink;">
<h1>Customer Registration Form</h1>
 <h2>Registration for college faculty</h2>
<ul>
<li><label for="Full Name">First Name:</label></li>
<input type="text" name="Full Name" size="15" />
<li><label for="Full Name">Last Name:</label></li>
<input type="text" name="Last Name" size="15" />
<li><label for="Dateofbirth">Date of Birth:</label></li>
<input type="DateofBirth" name="Date of Birth" size="12" />
<li><label for="EmailID">Email ID:</label></li>
<input type="text" name="EmailID" size="50" />
<li><label for="contactno">Contact Number:</label></li>
<input type="text" name="contactno" size="30" />
<li><label for="Country">Country:</label></li>
<select name="Country">
<option selected="" value="Default">(Please select a country)</option>
<option value="AF">INDIA</option>
<option value="AL">TURKEY</option>
<option value="DZ">RUSSIA</option>
<option value="AS">AMERICA</option>
<option value="AD">EUROPE</option>
</select>
<li><label for="address">Address:</label></li>
<input type="text" name="address"size="70"/>
<li><label for="City">City:</label></li>
<input type="text" name="city" size="30" />
<li><label for="Pincode">Pincode:</label></li>
<input type="text" name="Pincode" />
<li><label for="State">State:</label></li>
<input type="text" name="State" size="30" />
<li><label id="gender">Gender:</label></li>
<input type="radio" name="msex" value="Male" /><span>Male</span>
<input type="radio" name="fsex" value="Female" /><span>Female</span>
<li><label>Language:</label></li>
<input type="checkbox" name="en" value="en" checked /><span>English</span>
<input type="checkbox" name="nonen" value="noen" /><span>Non English</span>
</ul>
<form action="/action_page.php" onsubmit="myFunction()">
<li><label for="desc">Your Qualification:</label></li>
<textarea name="desc" id="desc"></textarea>
</ul>
  <input type="submit" value="Submit">
</form>
<script>
function myFunction() {
  alert("The form was submitted");
}
</script>
</form>
</body>
</html>
```

## OUTPUT
![Screenshot (62)](https://github.com/SrivarshanGurumoorthy/EX08_Web-Design/assets/127816583/0aa465c0-520d-4725-8cca-32c1630c9836)
![Screenshot (63)](https://github.com/SrivarshanGurumoorthy/EX08_Web-Design/assets/127816583/75411324-e14c-4539-b47b-abccc2ebab7d)


## RESULT
  Customer registration form using JavaScript is created successfully.
