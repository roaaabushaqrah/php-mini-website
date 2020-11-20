# php-mini-website

You will create a simple admin dashboard using PHP , Bootstrap,
## Requirements: 
### Landing Page:
Your landing page should include :
- Nav bar : the nav bar includes login/register buttons, 
    - The register button should disappear if the user logged on .
     - The login button should disappear if the user logged on and replaced with ; Welcome , userName
- Sliders contain random images.
### Login Page:
- Create a login form in PHP page, the page should contain :
  - User name
  - Password
  - Submit button 
- Create an associative array the array will contain five users, with passwords and roles. Ex: [username=>adam, password =>testpass, role =>admin]
- The login form should be handled using PHP : 
    - All the input fields are required. 
    - The user should not access the inner welcome pages, and the username and the password should be matched.
         -If the user is admin , the user should be redirected to the welcome_admin Page
         -If the user is normal user , the user should be redirected to the welcome_user Page 
-The Admin page should display all the users that are stored in the array.
### Register Page :
- The register page should contain  :
  - Username 
  - Password
  - Re-type Password 
  - Phone number 
- The register form should be handled using PHP.
- All the input fields are required. 
- Only the guests can  see the register button 
- The register button should save a user and add it to the users array

### Welcome Admin Page :
The welcome admin page should include : 
- List of all users that are saved on the array, the users should be listed as table. The last column of the table is the action column.
- In the action column , a delete button should be next to each user, the delete button should delete the user from the  array and the users page. 



