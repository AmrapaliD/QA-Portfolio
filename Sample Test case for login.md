|**🧪 Sample Requirement: Login Functionality for a Web Application**|||
| :- | :- | :- |
||||
|The application must allow registered users to log in using their email and password.|||
|1|The login form should have fields for email and password.||
|2|The "Login" button should be enabled only when both fields are filled.||
|3|If credentials are valid, the user should be redirected to the dashboard.||
|4|If credentials are invalid, an error message should appear: “Invalid email or password.”||
|5|The password field should mask input characters using password masking button.||
|6|The "Forgot Password?" link should redirect to the password recovery page.||
||||
||||
|**Sr. No.**|**Summary**||
|1|Validate Login Page.||
|1|||
|1|||
|2|Validate the 'Login' button when 'Email' and 'Password' fields are blank.||
|2|||
|2|||
|3|Validate the 'Email' textfield with valid email id.||
|3|||
|4|Validate the 'Password' textfield with valid password according to the requirement.||
|4|||
|5|Validate the 'Login' button after entering valid data in both the text fields.||
|5|||
|6|Validate navigation to the 'Dashboard' Page.||
|7|Validate the 'Email' textfield with invalid data.||



|7||
| :- | :- |
|7||
|8|Validate the 'Password' textfield with invalid password referring to the requirement.|
|8||
|8||
|9|Validate the 'Email' field with unregistered email id and Login.|
|9||
|9||
|9||
|10|Validate the error message displayed in Sentence case.|
|10||
|11|Validate the password masking functionality after entering in the field.|
|11||
|11||
|12|Validate the "Forgot password?" button.|
|12||
|12||


|||
| :- | :- |
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|**Actions**|**Expected result**|
|Check if the Login Page is opened.|User should be able to view the Login Page is opened.|
|Check if the Page title is displayed as 'Login' or 'Sign up'.|User should be able to view the page title is displayed as 'User' or 'Sign up'.|
|Check if all the valid fields are displayed on the Page.|User should be able to view the fields as : 'Email' textfield, 'Password' textfield and 'Login' button.|
|Check if the 'Login' button is displayed on the page on a valid position.|User should be able to view the 'Login' button displayed below the textfields.|
|Check if the 'Login' button is displayed as disabled.|User should be able to view the 'Login' button is displayed as disabled.|
|Check if the 'Login' button is clickable.|User should be able to view that the 'Login' button is not clickable.|
|Click on the 'Email' textfield.|User should be able to click on the 'Email' textfield.|
|Enter any valid Email id in the field.|User should be able to enter a valid email id in the field without getting any error message.|
|Click on the 'Password' textfield.|User should be able to click on the 'Password' textfield.|
|Enter the valid Password according to the requirement in the field.|User should be able to enter valid Password according to the requirement in the field without getting any error message.|
|Check if the 'Login' button is displayed as enabled.|User should be able to view the 'Login' button is displayed as enabled.|
|Check if the 'Login' button is clickable.|User should be able to view that the 'Login' button is clickable.|
|Check if the user is successfully navigated to the 'Dashboard' Page.|User should be able to view the 'Dashboard' Page opened.|
|Click on the 'Email' textfield.|User should be able to click on the 'Email' textfield.|



|Enter any invalid format Email id in the field.|User should be able to enter any Email id in invalid format in the field.|
| :- | :- |
|Check if error message is displayed for the invalid data entered.|User should be able to view an error message displayed as “Invalid email or password.”|
|Click on the 'Password' textfield.|User should be able to click on the 'Password' textfield.|
|Enter any invalid format Password in the field.|User should be able to enter any invalid format Password in the field.|
|Check if error message is displayed for the invalid data entered.|User should be able to view an error message displayed as “Invalid email or password.”|
|Click on the 'Email' textfield.|User should be able to click on the 'Email' textfield.|
|Enter an unregistered email id in the field.|User should be able to enter the unregistered email id in valid format in the field.|
|Enter a valid format password in the field.|User should be able to enter valid format password in the field.|
|Click on the 'Login' button.|User should be able to click on the 'Login' button and an error message should be displayed as "Unregistered user email id."|
|Check if the error messages are displayed in sentence case.|User should be able to view the error messages are displayed in sentence case.|
|Check if the error messages are displayed in valid UI on the Page.|User should be able to view the error messages are displayed in valid UI on the Page.|
|Enter a password in the field.|User should be able to enter a password in the field.|
|Check if the password masking button is displayed on the field.|User should be able to view the password masking button on the button.|
|Click on the password masking button and check if the password is hidden.|User should be able to click on the password masking button and the password should be hidden.|
|Check if "Forgot password?" button is displayed on the Page.|User should be able to view the "Forgot password?" button is displayed on the page.|
|Click on the button.|User should be able to click on the button.|
|Check if the password recovery page is displayed.|User should be able to view the password recovery page is displayed.|



|||||
| :- | :- | :- | :- |
|||||
|||||
|||||
|||||
|||||
|||||
|||||
|||||
|||||
|||||
|**Data**|**Priority**|**Test type**|**Pre-condition**|
||Highest|UI|Enter valid URL of the App Login Page.|
|||||
|||||
||High|UI|User should be on the valid App Login Page and should not enter any data in the textfields.|
|||||
|||||
||High|Functional|User should be on the valid App Login Page and should not enter any data in the textfields.|
|username123@emailid.xyz||||
||High|Functional|User should be on the valid App Login Page and should not enter any data in the textfields.|
|eg. Pass@123||||
||Highest|UI|User should be on the valid App Login Page and should have entered valid data in both textfields.|
|||||
||High|Functional|User should be on the valid App Login Page and should have entered valid data in both textfields and clicked on the 'Login' Page.|
||High|Functional|User should be on the valid App Login Page and should not enter any data in the textfields.|



|user#name@9876.150&\*||||
| :- | :- | :- | :- |
|||||
||High|Functional|User should be on the valid App Login Page and should not enter any data in the textfields.|
|password||||
|||||
||High|Functional|User should be on the valid App Login Page and should not enter any data in the textfields.|
|unregistered@emailid.abcde||||
|Password@1234||||
|||||
||High|UI|User should be on the valid App Login Page and enter data in a way that error messages are displayed.|
|||||
||High|UI|User should be on the valid App Login Page and a password should be entered in the field.|
|||||
|||||
||High|Functional|User should be on the valid App Login Page.|
|||||
|||||

