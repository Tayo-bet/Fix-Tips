# *Fix Manager*
<img src="static/assets/home.png">

Getting a technician to come fix a simple broken appliance or furniture in homes are most times costly and time wasting,  **Fix Manager** is a platform where people can share and learn basic tips to fix their home appliances and furniture. Tips are allowed to be update, deleted and pictures uploaded.


## UX
The idea of Fix Managers was to create a platform where people can get solution tips on how to make simple repairs in their homes, hence I focus on simplicity and intuitiveness.
The navbars were created to address registered and unregistered users: everyone can see the tips posted but only registered users can create, edit and delete tips.
I aslo created opportunity for users to add pictures to their post. Every registered user has the possibility of the following proces:


<img src="static/assets/ux1.png">
* A logged-in user would be able to see the necessary navbars to create a fix tip, profile,
 homepage where the general tips from all users are displayed and to also log-out.

<img src="static/assets/ux2.png">
* Users are only allowed to edit their personal tips without access to edit or delete the general public tips.


<img src="static/assets/admin.png">
* Only the admin has access to add, edit and delete the categories with the public exempted from this functionality.



### User Story
* Mike mistakenly broke the handle to his kitchen cupboard, it is still new and does not want to buy a new one. He called up a carpenter who wants to charge him almost the amount to buy a new one
and can only come after 10days due to work load. Mike called a friend that tells him about Fix Manager, a platform where he can get tips about how to make repairs to home appliances and furniture.
Mike visits the platform and:

* Register to get an account.
* Checks the different categories.
* Searches for relevant tips relating to what he wants.
* Applies the tips he say the platform.
* Follows the examples in the pictures.
* Discovers a way to make it better and shares the tips with other users with different pictures.


### User Experience Goals

* Help people learn and share tips to fix their broken home appliances.
* Users will be able to create a profile, using a personalized username and password for authentication.
* Users will be able to update, edit and delete tips shared at anytime of their choice.


#### Project Method:
The method use in the project are primarily acquire from the Code Institute Fullstack Software Development Course modules in HTML, CSS, JavaScript, Python Essentials and Backend Development particularly the All Task mini project Example. It is worthy of mention that I have studied other software development free materials, courses on Udemy, snippet codes, templates and Video tutorials on YouTube.



## FEATURES

* Navbar: Allows users to navigate to different options within the platform.
<img src="static/assets/home.png">

* Register: Users allow to create a profile with a username and password of their choice for authentication.
<img src="static/assets/register.png">

* Login: Users can login to the platform after creating the profile with details used when creating their profile.
<img src="static/assets/login.png">

* Tips/Homepage: All users can see the general tips posted by all users, with their names and dates when repair tips were added.
<img src="static/assets/tips.png">

* Add Tips: All users can add their repairs tips using category options and heading of the tips they which to share. They can also upload pictures for others users to follow.
<img src="static/assets/add_tips.png">
<img src="static/assets/add_tips2.png">

* Tips Search: A search options is allowed for quick access using name and description for all users.
<img src="static/assets/tips_search.png">

* Category Add/Delete Limitations: Only the Admin is allowed to manage/add categories or Delete Categories with access blocked to general users.
<img src="static/assets/manage_cate.png">
<img src="static/assets/add_cate.png">
<img src="static/assets/admin.png">

* Delete Defensive Coding: To delete any tips or category users are allow to re-consider and confirm delete action.
<img src="static/assets/delete_cate.png">

* Log Out: Users can log out of their profile with a log out message desplayed to confirm action.
<img src="static/assets/logout.png">

* Wrong Login Details: Wrong log in details alerts the users without suggesting what is wrong between username and password.
<img src="static/assets/wro.png">

* Footer: A footer with return links to Homepage, Login and Register. With a link to contact through a social media account.
<img src="static/assets/footer.png">

## Technology used

### Programming Languages:
* HTML
* CSS
* JAVASCRIPT
* PYTHON
* HEROKU
* MONGODB

### DataBase

* MongoDB

### Libraries
* Font Awasome  For icons.
* Materailizecss For source codes and styling.
* Jinja Framework Used for template execution and code re-usability.
* jQuery To simplify DOM manipulation.

## Testing

The tools were used for testing for code validation and beauty purpose:

* Freeformatter used to beautify the HTML code.
* BeautyTools used to beautify and validate the Javascript and CSS codes.
* Sentry trial version to debbug python scripts for error.

Navigation bars and buttons on this website has been tested, navigations all links to indended pages and the buttons functions as intended. 
The authentication requires a username and password to login, giving access to more functionalities and pages such as user profile, only the admin can update or delete a category. 
This website database uses mongoDB and all the endpoints created to carry out CRUD operations works properly; registered users of this website can create, read, update and delete data in the database as expected.

### Limitations

* User profile can be better with more options for personal details, password reset and option to delete profile by users that wishes to exit platform.
* A video upload will be better for users, to see tips givien being practicalised.
* A live chat will be a great addition to help users having problems on the platform.

### Deployment

Fix Managers is deployed on Github, connected to Heroku with automatic update with every Git Push. Necessary Files required by Heroku such as Procfile and requirements.txt have been added and sensitive folders gitignored.
GitHub is selected as the method during deployment to build and generate url.

Below is the step I followed to deploy my site to GitHub.

I used the below command to secure my work by pushing them to the repository file that was created for the project on GitHub.

* git add -A
* git commit -m " text to represent what is being committed"
* git push

Below are the step I used to deploy on Heroku:
After creating account

* Clicked on Settings
* Reveal Configvars
* Assigned the appropriate values for the below:

IP: 0.0.0.0
PORT: 5000
SECRET_KEY: FROM MONGODB DATABASE ACCESS,
MONGO_URI: URI FROM MONGODB AND I CORRECTED USER AND DATABASE NAME.
MONGODB_NAME: NAME OF THE DATABASE CREATED ON MONGODB COLLECTION.

* I connected to Github on Heroku through the name of Repo through the setting on create new app.


Below are the steps I used to create database on MongoDB:

After creating an account;
* Through Collections create DataBase.
* Assigned what categories, tips and users.

#### Github url: 
* https://github.com/Tayo-bet/Fix-Tips

#### Heroku url:
* https://fixtips.herokuapp.com/


### Credits:

* This project draws inspiration from Code Institute Mini Project Example during backend development module.
* https://www.youtube.com/watch?v=6WruncSoCdI&t=13s Was used as additional lessons for image upload in Flask.
* https://www.youtube.com/watch?v=zMhmZ_ePGiM&t=252s Was used as additional lessons for image upload in Flask.


#### Acknowlegment:
Special thanks to My Mentor Dick Vlaanderen for guidance and direction from my first mile-stone Project all through till now.
