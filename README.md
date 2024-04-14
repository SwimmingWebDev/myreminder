# ACIT2520 Term project - Reminder App

**Course** ACIT2520 Developing Web Applications <br>
**Instructor** Armaan Dhanji <br>

## Requirements

☑️ Passport Local Authentication <br>
☑️ Admin Functionality <br>
☑️ View, editing, deleting for logged in users <br>
☑️ Hide the navbar if logged out <br>
☑️ **Bonus** Create a New Reminder with an option for a _banner_

```
[Administrator]
email: admin123@gmail.com / password: admin123!

[General Users]
email: jimmy123@gmail.com / password: jimmy123!
email: cindy123@gmail.com / password: cindy123!
```

## Additional Tasks

➕ Add registration function <br>

<!-- ➕ Edit Testimonials from Users in Database <br>
➕ Update Reminder View Interface <br> -->

## Breakdown of work

#### Yangyi Jung

1. Add `routes` directory and Edit `index.js` to find routes conveniently
2. Change structure of `database`to match the passport starter code database structure
3. Edit Authentication with email and password using `passport.js`
4. Edit login function and update `reminder/index.ejs`
5. Add logout in `auth_controller.js`
6. Add admin ability
7. Create `admin.ejs` to view admin functionality
8. Update the navigation of `index.ejs` to show the changes for logged in users
9. Update Bonus functionality (create a reminder with banner) in `reminder_controller.js`
10. Implemented registration function using `fs`

- reference : https://www.passportjs.org/tutorials/password/signup/
