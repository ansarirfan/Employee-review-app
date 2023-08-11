# Employee-review-app
#website link :- https://employee-review-app-lxbd.onrender.com
<br/>
A web application which help you to create, update,  delete and  review emp;oyee. 
It is user specific app, which mean a user review , and mark it as assign , or not assign. 
The project is built using a tech stack consisting of Node.js for the server-side scripting.
Express for handling HTTP requests and routing.
MongoDB for storing and managing the data and EJS for rendering the views and templates.

## Installation
To run this application on your local machine, please follow these steps:

Clone this repository using the following command:
```
$ git clone https://github.com/agentgrey/TodoList.git
```
Install the required dependencies using the following command:
```
$ npm install 
```
Start the application using the following command:
```
$ npm run dev 
```
Open the application in your web browser by visiting the following URL:
```
$ http://localhost:7500 
```

## Usage
Once you have the application up and running, you can start using it by following these steps:
* Sing-up/Sign-in into your account.
* Click on the "Add employ" button to create a new employee.
* Enter the name of the  you want to review.
* Click on the "Save" button to save the employee.
* To mark a  as complete/incomplete for the day, simply click on the corresponding icon.
* To delete a employee, click on the "Delete" icon next to it.
* To see today's emploee, click on "review" button.
* To edit a employee, click on the "Edit" icon next to it.

## Folder Structure
```
Habit Tracker
    |
    |               |--->css
    |--->assets---->|--->img
    |              
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport_local.js
    |
    |                  |-->dashboard_controller.js
    |--->controllers-->|-->review_controller.js
    |                  |-->users_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->index.js
    |--->routes---->|-->reviews.js
    |               |-->users.js
    |
    |              
    |              |--->_footer.ejs
    |               |---->user_sign_in.ejs
    |              |--->_header.ejs
    |              |--->add_employee.ejss
    |--->views---->|--->admin_dashboard.ejs
    |              |--->edit_employee.ejs
    |              |--->employee_dashboard.ejss
    |              |--->user_sign_up.ejs
    |              |--->layout.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
 ````

