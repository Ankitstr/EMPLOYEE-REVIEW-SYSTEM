# EMPLOYEE-REVIEW-SYSTEM


 Employee Review System

An application that allows employees to submit feedback toward each other’s performance.
#employee-review-system
#first create a admin
#sign up for some employee
#admin assigned a employee for a review other employee and if admin want to assigned new admin they also do this


# Features
- Admin view
    - Add/remove/update/view employees
    - Add/update/view performance reviews
    - Assign employees to participate in another employee's performance review
- Employee view
    - List of performance review requiring feedback
    - Submit feedback
- Made 1 login for admin and employee
- An employee can register, only admin can make an employee an admin

# Local setup

- Required
    - Nodejs
    - MongoDB
- commands
    -         npm init

    -         npm start
        or
    -         node index.js



Directory Structure and flow of The Code
This code follows MVC pattern and hence everything is differentiated and well managed:

Employee-Review-system
    |-----assets
    |       |--- css
    |            |-- Style.css        
    |       
    |------ config
    |         |--- mongoose.js
    |         |--passport-local-strategy.js      
    |------ controllers
    |         └--- employee.js
    |------ models
    |         └--- habit.js
    |         └--- user.js
    |------ routes
    |         └--- index.js
    |------ views
    |         |--- _header.ejs
    |         |--- _header.ejs
    |         └--- _header.ejs
    |         |--- add_emp.ejs
    |         |---all_emp.ejs
    |         |---assign_work.ejs
    |         |---emp_sign_in.ejs
    |         |---emp_sign_up.ejs
    |         |---home.ejs
    |------ .gitignore
    |------ index.js
    |------ package.json
    |------ package-lock.json
    └------ README.md
Contributing
If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

Fork the Project
Create your Feature Branch
Commit your Changes
Push to the Branch
Open a Pull Request
