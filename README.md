# Employee-Review-System
A full stack, app used for reviewing employee. Hoisted Link : https://ers-ldj9.onrender.com

Description
A full stack app, in which the admin, can assign the employees, to review each other on the basic of there work. The admin has special power, to make any other employee as the new admin. Admin can also make the new employee, and they can also assing, the reviewer and revieweee. The admin can see the current employee, and according to the review, the admin can remove the employee. The review given to the employee, is always going to be store in the database.

Tech Stack
Node , Express, Mongodb , EJS , javaScript , html, css

How to setup the project on local system
Clone this project
Start by installing npm if you don't have it already.
Navigate to Project Directory.
After reaching the project directory you have to run the following the command.

     npm install 
     npm start || nodemon index.js
If you want to make an employee as admin then use the secret key :happy.
Features
You can review the employees. The admin has the special power to assing, the task to employee, remove the employee, add new admin, and also employee;

![01](https://github.com/pranayainchwar/ers/assets/122523118/3290cd4b-539
![register02png](https://github.com/pranayainchwar/ers/assets/122523118/c348033d-dd25-4060-a8a2-e8010101a4f0)
2-4b83-a
![employeelist](https://github.com/pranayainchwar/ers/assets/122523118/2c0a905d-1eff-4868-bdbc-cd85a0068d88)
b51-6b5d9e6f11f2)
![addmember](https://github.com/pran
![assignwork](https://github.com/pranayainchwar/ers/assets/122523118/debd450a-dd28-43f3-afff-0a0caa1e0bfc)
ayainchwar/ers/assets/122523118/e857a763-d0db-43ae-9247-f425615edb9a)
![surajview03](https://github.com/pranayainchwar/ers/assets/122523118/07bc6490-ccbe-4a9d-9113-767ded741b39)


```
Employee Review System
    |
    |               |--->css
    |--->assets---->|--->images
    |             
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->admin_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->review_controller.js
    |                  |-->user_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->admin.js
    |--->routes---->|-->index.js
    |               |-->review.js
    |               |-->user.js
    |
    |              |--->_header.ejs
    |              |---> addEmployee.ejs
    |              |---> admin.ejs
    |              |---> employe.ejs
    |--->views---->|--->forget_password.ejs
    |              |--->home.ejs
    |              |--->layout.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    ````
