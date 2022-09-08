# CMPG323-Project2-34484612

## When Page is not found
### Testing:
Ensure the URL ends with /swagger/index.html to interact with the API via Swagger.

### Seeing API file:
Ensure the URL contains /swagger/v2/swagger.json

## Authentication
### Step 1: Login
1. Press on the /api/Authenticate/login with the credentials: Username: 'steve' and Password: 'Abc123@'

2. If an 401 error is encountered  it means the credentials are wrong or the user is not added to the database this can be fixed by registering an user (See Registering users section).

3. If the credentials are correct, a token will then be generated.

4. Copy the token within the parenthesis ("<Token>").  <Token> represents you're token and will last an hour.
  
### Step 2: Autherise
1. Press on the Autherise button in the top right conner.
  
2. Enter 'Bearer <Token>' into the promt.

3. You will now be autherised to use the Methods of the controllers.

## Registering users:
1. For normal users press on api/Authenticate/register

2. For admin users press on api/Authenticate/register-admin
 
  ### Passwords:
  Passwords require atleast A capital leter, a number and a special charachter.
  
3. Enter the required data into the fields within the parenthesis
  
## Methods:
  
  ### Get:
  The get methods return all the entries of their respected table.
  
  ### Post:
  The post methods creates a new record within
  
  ### Get with {id}:
  This get method returns a specific record that is selected by reciveing its ID.
  
  ### Put:
  Updates a specific record in their respected table that is selected by reciveing its ID.
  
  ### Delete:
  Removes a specific record in their respected table that is selected by reciveing its ID.
  
  ### Get with Catagory id:
  Returns all the devices that have the same catagory id
  
  ### Get with Zone id:
   Returns all the devices that have the same catagory id
  
