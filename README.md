# Test Scenarios for Face Book

## signup Test Scenarios:

- verify registration using valid phone number
- verify registration using valid email address
- verify registratin while choosing male as a gender
- verify registraton while choosing female as a gender
- verify leaving first name feild empty
- verify leaving surname feild empty
- verify providing one character in the first name feild.
- verify providing one character in the last name feild.
- verify providing two character in the first name feild.
- verify providing two character in the surname feild.
- verify providing numbers in the first name feild.
- verify providing numbers in the last name feild.
- verify providing special character in the first name feild.
- verify providing special character in the last name feild.
- verify providing non-english first name,last name feild [Arabic,german,bangla]
- verify leaving phone number or email address feild empty
- verify providing invalid phone number very shortjj[123]
- verify providing invalid phone number very big [43434345345335435]
- verify providig bangla input in the phone number feild.
- verify registration using an already used email.
- verify using an empty password
- verify registration using short password[Ab12#]
- verify registration using a password that does not include lowercase letter [ABC123$]
- verify registratin using a password that does not include uppercase letter [abc123*]
- verify registratin using a password that does not include any letter [12345]
- verify registration using a password that does not include any number [ABCD#]
- verify registration using a password that does not include any special character [ABC123]
- verify registrationn using a very young age [2 years]
- verify registration using a date in the future
- verify registration using a young age [between 4 and 13]
- verify registratin using a very large [more than 120]
- verify leaving the gender scenario empty

## Login Test Scenarios:

- login using valid email and valid password
- login using valid phone number and valid password [with country code +20]
- login using valid phone number and valid password [with country code +880]
- login using valid phone number and valid password [without country code 01772921632]
- login using valid phone number and valid password [arabic format phone number]
- verify clicking on the eye icon to show password
- trying coping and pasting the password into the word or notes
- verify leaving email or phone number feild empty
- verify leaving passord feild empty
- verify login an invalid email address(not registered)
- verify login while making a spelling mistake in the email feild
- verify using an invalid phone number
- verify login using invalid password
- verify login 10 tiems using invalid password.
- verify login using and old password.
