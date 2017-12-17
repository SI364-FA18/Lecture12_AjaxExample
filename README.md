# SI364-Final-Project

### What my program does:
* My program uses user authentication to have users create a username and password that is used to store each user's individual 'wishlist'. Once they are signed in, they can view their saved wishlist of restaurants or search for restaurants by using the cuisine and city and state. Restaurants matching the search criteria are then pulled up in a form and users can view the Zomato pages of these restaurants, or select which ones to add to their wishlist. When a new restaurant is added, an email is sent to the user's email alerting them of what restaurants have been added.
* **Search results are matched to the best of the Zomato API's search capabilities. I have found one of the most accurate searches is Asian cuisine in Livingston, NJ. This common search can be seen with an ajax function that is run by clicking the button under the search fields.

### How to run my program:
* To run my program, a database called jullockefinalproject must be created. MAIL_USERNAME (can be jullocke364), MAIL_PASSWORD (will be written in comment on canvas), and ADMIN (can be jullocke364) must also be exported in terminal.

* A static folder with an imgs subfolder must also exist, as this is where any profile pictures will be saved and accessed. Profile pictures can be added when running my project on localhost, but should not be uploaded when registering as a user on heroku.
* **My application is deployed on heroku (julia-locke-finalproject.herokuapp.com) and can access the registration page, page not found, and the log in page, but is currently giving an internal server error when trying to log in. For grading purposes, it would be best to run my project on the localhost to see all of the functionality.

* Requests is used when gathering the API data so this should be installed, but this as well as all other modules needed have been used in class.

* After the database has been created and the necessary MAIL_USERNAME, MAIL_PASSWORD, and ADMIN, have been exported, my project can be run with python finalproject.py runserver.

### Thank you for a great semester. Have a happy holidays.