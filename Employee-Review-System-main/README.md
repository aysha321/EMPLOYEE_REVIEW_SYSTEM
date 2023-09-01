# Employee-Review-System
This Employee review web application is created for employees to submit feedback on each other's performance. Users could have either an "employee" or an "admin" role. There are two dashboard pages based on the role of the employee those dashboard pages will be rendered, Users with the role of admin can assign employees to participate in the review of other employees. Employees can only submit feedback required by assigned reviews.
### Hosted link:


## Inside this project
### From Admin's panel
- Add employee
- Delete employee
- Update employee details
- Assign review to employee
- Update review of employee

### From Employee's panel
- Submit reviews assigned to it
- View reviews given by others

## How to set the project on the local system
- Clone this project from https://github.com/kunaldeep799/Employee-Review-System.git
- Start by installing npm if you don't have it already.
- Navigate to Project Directory and run the following command.
```bash
npm install
```
- Run project
```bash
npm start or nodemon index.js
```
- Visit in your local browser- http://localhost:5000/
 
## Tech Stack
- NodeJS
- MongoDB
- ExpressJS
- EJS
- Bootstrap

## Libraries:

- bcryptjs
- connect-flash
- connect-mongo
- cookie-parser
- dotenv
- ejs
- express
- express-ejs-layout
- express-session
- mongoose
- passport
- passport-jwt
- passport-local
