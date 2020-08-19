# To Do List

As part of my milestone 3 project I decided to build a to do list web app mainly using Flask, Python and MongoDB.

The main goal of the project was to build something practical that could be used to manage ones workload.

The app has a user login system so that it can be used for more than one person. The app itself displays a 'To Do' list and enables the user to easily add, edit or delete items on the list.

## User Experience

User experience is at the forefront of the development of the app. The app is intended to be easy to use and intuitive.

When the app loads in the browser, the user is met with the option to login or register. The user can then see the current list accompanied with an expand arrow, a 'Done' and 'Edit' button. In the navbar, there is the option to add a new item. Overall, the app is user-friendly and intuitive.

## Features

User Login System - a user login system is built in the app. This allows the user to register an account or login if they are already a user. There is a subsequent  database to store user information (username, password and email).

To Do List - the 'To Do List' displays the users current list of items to get through. It is accompanied with an expand arrow, a 'Done' (delete) button and an 'Edit' (update) button.

Edit Item - the 'Edit Item' screen allows the user to edit the details of an item already in the list. This includes item name, item details, due date and the urgency of the task which are also all stored in the database.

Add Item - similar to the 'Edit Item', the 'Add Item' screen allows the user to add a new item to the list.

Username displayed under items - the users username is displayed in the expanded version of the item.

## Technologies Used

- Python
- Flask
- MongoDB
- jQuery
- HTML Templates
- CSS
- Jinja
- Materialize
- Forms

## Testing

In order to test my project I mainly used Google developer tools, I checked the project worked in different browsers and I also ensured the project worked on different devices to make sure that it's responsive.

Also I used Google Dev tools to debug certain sections of code. I used breakpoints to isolate snippets of code and test them. I also used the debugger statement to test certain functions.

With regards, to testing the interaction with the database that was done manually. I manually visited the MongoDB website to view the database.

I also used a code validator to ensure my code was of a sufficient standard.

I also tested the game in Google Dev Tools for responsiveness and also manually on the following devices:
- iPad
- iPhone

To test the register as new user function, I manually registed a new user and it worked.

I then logged in as an existig user and this worked too.

I tested logging out manually in the app and this also worked.

I then tested the add item to list functionality and this worked too.

I then proceeded to test the edit item and update functionality which also worked.

I then registered a new user in order to check if the list cleared and wasn't displaying list items of other users.

I then logged in as the original user and tested the delete function. The item I checked as Done disappeared, proving the function was working.

Where relevant, for all of the above, I also manually checked the database to ensure everything was working and the database was connected.

## Deployment

I deployed my project on Heroku

## Credits

### Content

- Tutor Support and help from my mentor were used to get help with issues I was struggling with.

### Media

N/A

### Acknowledgements

- I got inspiration from the mini-project in the data-centric development module. I chose this over the project ideas because I wanted to build something that would be of practical use to me.
