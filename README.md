426 Final Project: Plant Store Database

For our final project, we were inspired by our teammate Dylan Nicks' real-world business venture.  Dylan operates a plant business out of his home where he grows and sells plants to other students.  Our project is a user-friendly database designed with the administrators of a plant store in mind.  It provides a way to track plants, orders, and customers.  

Front end that is interactive and event-driven:
We designed our front-end using a flask app for the efficiency and flexibility of design it offers.  The front-end is fully interactive, allowing the user to make permanent changes to the database at the click of a button.  The user also interacts by submitting their login credentials and selecting a theme for the database.

Back end that serves at least two resources with a RESTful CRUD (create, read, update, and delete) API.:
We designed our back-end using sqlite to construct a simple but powerful database for tracking business information.  We have different routes within our database.py file that interact with the sqlite database through queries upon user interaction through the frontend.  Users have full ability to create, read, update, and delete records in the database.

Uses at least one 3rd party API: 
We used the trefle api to generate random plant facts displayed on the screen to emphasize the plant theme of the database and to enhance the aesthetics of the user experience.  Upon each reload of the app, a new plant fact will be displayed.

Uses session-persistent state in some way.:
Users are first faced with a login screen where they must submit a valid username and password to enter the database.  This provides security so that only the administrators of the business are able to alter the records.  Upon entering, the username is displayed in the top left, and the user has the opportunity to go to preferences and select their preferred website visual theme.  Their preference is stored in the user_preferences database, and will remain consistent for that specific user.
