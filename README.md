face-forward
A Social Media app for motivating yourself and others in your circle.
Let's make goals!
  
---
## Table of contents
  
### 1-Description
### 2-Technologies
### 3-Challenges
### 4-Issues
### 5-Desired Features
### 6-Contributors

---
### 1-Description
A social media app based on what you're going to do rather than showing off what you've done. Users login to a profile page that lists their own tasks, filterable by category. Then you can see a list of all tasks, 10 at a time, and also filterable by category. You can find your friends (or whoever you're curious about) and look at their tasks, too.

Users gain points by completing tasks (categorized as tasks, goals, bucket list items, and ideas). How many points a task is worth depends on its average rating, and if it hasn't yet been rated, it isn't worth any points. All tasks can be rated just once, and you can't rate a task you created. 

When completing a task, you can choose to keep a record of it, or remove it from your list altogether. You'll get the points, but no record will remain. You can also drop a task if you no longer want it. Removing a task from your list, whether upon completion or by dropping it, does not delete it from general use.

You can update your information, upload or change a picture, or change your password at any time.

---
### 2-Technologies
  This project utilizes the following technologies:
- HTML
- CSS
- Vanilla JavaScript
- [jQuery](https://jquery.com/)
- [Node.js](https://nodejs.org/en/)
- [passport](https://www.npmjs.com/package/passport)
- [bcrypt](https://www.npmjs.com/package/bcrypt)
- [session](https://www.npmjs.com/package/express-session)
- [Express](https://expressjs.com/)
- AJAX
- Web APIs
- [Google Fonts](https://fonts.google.com/)
- Responsive Design
- [Sequelize](http://docs.sequelizejs.com/)
- [Handlebars](https://handlebarsjs.com/)
- [Heroku](https://www.heroku.com/)
- [MySQL](https://www.mysql.com/)

---
### 3-Challenges
Some of the challenges presented by this project include: setting up user authentication with passport and express-session; tracking project complexity through routes, controllers, handlebars files, and client-side javascript; and detailed database queries with Sequelize - specifically, using offsets and limits in conjunction with "show more results" buttons on the client side; and nesting sequelize queries in callback functions inside other queries. A fun project overall, and definitely a learning experience.

---
### 5-Future Development
  Below is a list of possible features that I would like to add to the project.
1.  When a task's creator drops the task and no one else has picked it up, the task is removed from the database.
2.  Possibly linking with imgur.com as a place to post pictures related to tasks.

Some other ideas:
1.  Allow users to create groups
2.  Add functionality to associate tasks to goals, and goals to bucket list items in a kind of hierarchy of accomplishments
3.  Create a more robust rating system that would boost point scores if a task has been rating by a large number of users

---
### 6-Contributors
- [Wood Jerry Remelus](https://github.com/DrWood89/)
- Keith Allmon
- Jason Hansen
