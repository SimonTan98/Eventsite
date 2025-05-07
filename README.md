# Eventsite
Eventsite is an event planning website that allows users to create an account, create/modify/delete events, and register for events. This project allowed me to learn about back-end scripting and data manipulation using PHP. The front-end was made using HTML, CSS, and Javascript. The project was made using XAMPP (WAMP stack).

## Installation Instructions
To download this project, you will need a WAMP stack software package. To view this project...
1. Create a folder called "Eventsite" in the document root folder of your WAMP stack (usually htdocs for XAMPP).
2. Download and move the "private" and "public" folders into the new "Eventsite" folder.
3. In phpMyAdmin (or your mySQL server), create a new user called "simonuser" with a password of "simonPassword".
4. Under private/database, copy the contents of database.sql and paste them into the SQL editor of phpMyAdmin.
5. Run the database script. This will create the back-end database along with some sample events/accounts.
6. Start Apache and MySQL using your WAMP control panel.
7. Open your web browser and navigate to "localhost/Eventsite/public/server/index.php".
