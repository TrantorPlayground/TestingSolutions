Setup config.properties file
1. We have all the parameters defined in this file, we can add values of thesse parameters as per requirements
2. To change the sender email, update sender's email id and run encryptPassword window batch file
3. Input password in encryptpassword batch file, it will automatically update "senderEmailPassword" parameter in encrypted format in config.properties file
4. We can add more recipient separated by comma
5. We can change response code threshold as per condition(send mail if get response code greater then mentioned code)it will send notification email
4. Run ExecuteHealthCheck to execute the program
6. Define website URL, which you want check in URL parameter of config.properties file
