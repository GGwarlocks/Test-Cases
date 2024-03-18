# Test-Cases Samples

*Description*
Check if the login works when user enters the correct credentials.

#Steps to reproduce#

1. Open website.com/login

2. Add correct user/pass

3. Click "Login" button

*Expected result*
User should be able to login and is redirected to his profile page.

Test data:
User: ioana
Pass: 123456

Pre-conditions
User should have a valid account.

Post-conditions
-

--------------------------------------------------------------------------------------------
Description:
Check if the login works when the user uses the incorrect username.

Steps to reproduce:

1. Go to website.com/login

2. Add an incorrect username

3. Press the login button

Expected result: 
User should recive an error message informing that the username/passward is incorrect.

Test data:
User: ioana
Pass: 123456

Pre-conditions
User should have a valid account.

Post-conditions
-

--------------------------------------------------------------------------------------------
Description:
Check if the login works when using the incorrect passward.

Steps to reproduce:

1. Go to website.com/login

2. Add an incorrect passward

3. Press login button

Expected result: user should recive an error message informing that username/passward is incorrect.
Test data:
User: ioana
Pass: 023456

Pre-conditions
-
Post-conditions
-

--------------------------------------------------------------------------------------------
Description:
Check if the login works when a user uses both username and passward incorrect.

Steps to reproduce:

1. Go to website.com/login

2. Add an incorrect username

3. Add an incorrect passward

4. Press login button

Expected result: 
User should recive an error message informing incorrect username/passward.

Pre-conditions
-
User should have a valid account

Post-conditions
-

--------------------------------------------------------------------------------------------
Description:
Check if the login works without typing passward.

Steps to reproduce:

1. Go to website.com/login

2. Add the correct username

3. Press the login button

Expected results: 
User should recive a message informing a passward is needed.

Pre-conditions
User should have a valid account

Post-conditions
-
