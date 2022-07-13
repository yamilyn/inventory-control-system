# Project: 📊 Inventory Control System
![Screenshot](/assets/ics-dashboard-system.jpg)

## 👋 README by ***Yamily Benigni*** - [Linkedin](https://www.linkedin.com/in/yamilybenigni/) | [Portfolio](https://yamilycodes.com)

### 🔗 Quick Links
##### [PROJECT PHILOSOPHY](https://github.com/yamilyn/inventory-control-system#-project-philosophy) - [DEPLOYMENT](https://github.com/yamilyn/inventory-control-system#-deployment) - [TECHNICAL REQUIREMENTS](https://github.com/yamilyn/inventory-control-system#-technical-requirements) - [IDEA](https://github.com/yamilyn/inventory-control-system#-idea) - [TECHNOLOGIES USED](https://github.com/yamilyn/inventory-control-system#-technologies-used) - [DEVELOPMENT JOURNEY](https://github.com/yamilyn/inventory-control-system#-development-journey) - [TEAM COMMUNICATION](https://github.com/yamilyn/inventory-control-system#-team-communication) - [KEY LEARNINGS](https://github.com/yamilyn/inventory-control-system#-key-learnings) - [CHALLENGES](https://github.com/yamilyn/inventory-control-system#-challenges) - [DELIVERED FEATURES](https://github.com/yamilyn/inventory-control-system#-delivered-features) - [UNSOLVED PROBLEMS](https://github.com/yamilyn/inventory-control-system#-unsolved-problems) - [BUGS](https://github.com/yamilyn/inventory-control-system#-bugs) - [DEVELOPERS](https://github.com/yamilyn/inventory-control-system#developers)

***

### 📝 Project Philosophy
This is a Full Stack Application for micro, small and medium food businesses that could benefit from controlling stock rotation and avoid food waste. There were approximately 5,000 micro, Small and Medium Enterprises in the food and drink sector, according to [gov.uk](https://www.gov.uk/government/statistics/food-statistics-pocketbook/food-statistics-in-your-pocket).

***

### 🚀 Deployment
See completed project [here](https://inventorycontrolsystem02.herokuapp.com/)

***

### 🎯 Technical Requirements
#### User resource
* User must have a profile
* User must be able to edit their profile
* User must be able to change password

#### Authentication
* User must be able to sign up
* User must be able to sign in
* User must be able to sign out

#### Extra resources
* User must be able to create a resource
* User must be able to edit a resource
* User must be able to view all resources they created
* User must be able to view a single resource they created
* User must not be able to edit or delete other users' resources

***

### 💡 Idea
#### Entity Relationship Diagram
![ERD](/assets/ERD-SEI-project-2.jpg)

#### Dashboard wireframes
![WireFrames](/assets/dashboard.png)
![WireFrames](/assets/detail.png)


***

### 👩‍💻 Technologies used

- This project uses the [MVC design pattern](https://www.geeksforgeeks.org/mvc-design-pattern/) and is using JavaScript, jQuery, Express, [Mongoose](https://github.com/Automattic/mongoose#readme), Node.js, Chart.js, HTML and CSS.
- For the database, the system uses [MongoDB](https://www.mongodb.com/), a cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with schema.
- For the authentication, it uses [Passport](https://www.passportjs.org/) which is an authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped into any Express-based web application. 
    - For password protection, the system uses a dependency called [bcrypt](https://www.npmjs.com/package/bcrypt), a library to help hash passwords.
- For the styling, the project uses the [Bootstrap](https://github.com/twbs/bootstrap#readme) framework, it is a powerful, extensible, and feature-packed frontend toolkit. 
- As a team, we have used [GitHub Enterprise](https://github.com/enterprise) for version control.
- The final version has been deployed on [Heroku](https://inventorycontrolsystem02.herokuapp.com/).

#### Dependencies:

bcrypt, connect-flash, dotenv, ejs, express, 
express-ejs-layouts, express-session, method-override, 
moment, mongoose, nodemon, passport, passport-local

<code><img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-ar21.svg" height="50"></code>
<code><img src="https://www.vectorlogo.zone/logos/w3_css/w3_css-ar21.svg" height="50"></code>
<code><img src="https://www.vectorlogo.zone/logos/javascript/javascript-ar21.svg" height="50"></code>
<code><img src="https://www.vectorlogo.zone/logos/jquery/jquery-ar21.svg" height="50"></code>
<code><img src="https://www.vectorlogo.zone/logos/visualstudio_code/visualstudio_code-ar21.svg" height="50"></code>
<code><img src="https://www.vectorlogo.zone/logos/expressjs/expressjs-ar21.svg" height="50"></code>
<code><img src="https://www.vectorlogo.zone/logos/nodejs/nodejs-ar21.svg" height="50"></code>
<code><img src="https://www.vectorlogo.zone/logos/mongodb/mongodb-ar21.svg" height="50"></code>
<code><img src="https://www.vectorlogo.zone/logos/github/github-ar21.svg" height="50"></code>
<code><img src="https://www.vectorlogo.zone/logos/getbootstrap/getbootstrap-ar21.svg" height="50"></code>
<code><img src="https://www.vectorlogo.zone/logos/heroku/heroku-ar21.svg" height="50"></code>

***

### 🗓 Development journey
This was a team project (2 people) built in four days. We divided the work into four main requirements as described in ***tasks***. My responsibility was to develop the MVC components for `Product` and `Supplier` and also the relationship between them. After that, I have also used Chart.js to show charts on the main dashboard and Bootstrap for the full styling.
<br>
Each morning, we have started the day with a sprint stand-up to catch up with each other's code and also to commit and resolve any conflicts.

#### Tasks
* MVC for `Product`
* MVC for `Supplier`
* MVC for `User`
* Authentication/authorization

#### Day 1
I started planning the project with my co-worker about the basic working features we wanted, then finalised the ERD and wireframes. I also started coding the `product` model, controllers and some views `.ejs`.

#### Day 2
I started working on the `supplier` model and controllers, also the many-to-many relationship association between them. I continued working on the templates `.ejs` with some styling from Bootstrap classes. Me and my co-worker merged the authentication and user model and checked for any conflicts.

#### Day 3
I worked on the charts for the dashboard and coded frontend JavaScript for it to show. I also worked on the front end by adding some extra styling from the Bootstrap framework.

#### Day 4
On that day, all the technical requirements were met. However, me and my co-worker decided to work together in order to test, check for bugs, conflicts and apply more styling. By the end of the day, we have deployed the system on Heroku.

### 🔉 Team communication
I have worked remotely with my co-worker and for communication purpose, we have used **Zoom**, **Slack** and **Trello**. As previously mentioned, for the version control, we have used **GitHub enterprise**.

***

### 🌟 Key learnings
Besides the programming skills, this project has helped me understand the importance of time management for a small team, we were only two people with a short timeframe for delivery, I believe the success of delivery was because I have planned which basic function should be coded initially and them add a few more resources if I had the time. The communication with my co-worker was excellent too and this was also a valuable aspect of this project.  

***

### 🚨 Challenges
I had a few challenges along the journey, first, we decided to show the data as charts with info from products and suppliers, for this I have added few lines of code in order to show and populate those charts, below are some example of my coding:

```jsx
// Index list //
exports.product_index_get = (req, res) => {
    
    Product.find({}, null).populate('supplier')
    .then(products => {
        let scripts = ["https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.8.0/Chart.min.js", "/script/dashChart.js"]
        res.render('product/index', {products: products, scripts: scripts, moment})
    })
    .catch(err => {
        console.log(err);
    })
};
```

Code for the pie chart

```jsx
// Pie Chart for index //
exports.supplier_chart_get = (req, res) => {
    
    let results = []

    Supplier.find().populate("product")
    .then(suppliers => { 
        suppliers.forEach(( supplier) => {
        
            let result = {
                name: supplier.name,
                totalProducts: supplier.product.length
            }
            results.push(result)
        })
        
        res.json(results)
    })
    .catch(err => {
        console.log(err);
    })
};
```


***

### 🎉 Delivered Features
#### Authentication
* User can sign up and sign in
* User can sign out
* User can edit their own profile
* User can change their own password

#### Level Admin
* Admin can also see all other profiles
* Admin can also edit profiles and delete users

#### CRUD Data model
* Create and update products
* Create and update suppliers for products
* Assign one suppliers for each product
* Assigned suppliers cannot be deleted

#### Charts
* Show products received per day
* Pie chart show products assigned per supplier

***

### 🤔 Unsolved Problems

* Reset Password whilst logged out of application 
* Upload profile images
* Create Company accounts (Only displays data created by the company)
* Invite team members to join via email functionality 
* Ability for users to import data via csv files

***

### 🐞 Bugs
When the user is updating their profile, it is not asking to confirm the password. The charts needs to filter product that current user has added into the system, its current showing ***all*** products.

***

## Developers
* Yamily Benigni - [Linkedin](https://www.linkedin.com/in/yamilybenigni/)
* Christopher Carey - [Linkedin](https://www.linkedin.com/in/chriskcarey/)

