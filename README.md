# Employee-App---api

The essentails apis for employee app - The Kite is included in this directory.

Back end is written in node js with MongoBD as database. We can set the apis in our local machines.
To set up the apis, go through the following steps.
1. Step up MongoBD to your system.
2. Setup node js and npm
3. Inside api directory, 
  3.1 Run npm install for installing dependencies.
  3.2 Run npm start for start the api server.

 API specifications 
  
1	API used for Login registered uses
  URL - Baseurl+/login
  Method - POST	
  Input Params- {email: "abc@gmail.com" , password : "Abc@2020"}	
  Output Response - Success - return token
2	API used for change password of registered users
  URL - Baseurl+/resetpassword
  Method - POST	
  Input Params- {email: "abc@gmail.com" , password : "Abc@2020"}	
  Output Response -Success - return success message
3	API used for user registration
  URL - Baseurl+/signup
  Method - POST	
  Input Params- {email: "abc@gmail.com" , password : "Abc@2020"}	
  Output Response -Success - return success message
4	API used for getting all employee details
  URL - Baseurl+/employees
  Method - GET	
  Input Params- no parameters
  Output Response -Success - return all employee data
5	API used for create/update employee details	put		
  URL - Baseurl+/employees
  Method - PUT	
  Input Params- {"Name":"John","EmployeeId":"34QQW","Grade":"A1","ContactNumber":67865655344,"Designation":"software engineer","_id":"60015a9ed4c35631841d9c77"} 
                (_id not send when create a employee details)
  Output Response -Success - Return success message
