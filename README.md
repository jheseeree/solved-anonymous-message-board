# Anonymous Message Board

This is the boilerplate for the Anonymous Message Board project. Instructions for completing your project can be found at https://www.freecodecamp.org/learn/information-security/information-security-projects/anonymous-message-board

# Initial Setup
Run commands after cloning
- npm install
- npm run start

Additional script added:
- npm run watch ==> command for "node server.js --watch"

# MongoDB Connection
Create .env file on root directory and set following:

"DB" should be a connection string from your MongoDB database setup on your cloud database platform (Ex. Atlas)

PORT=
NODE_ENV=test
DB="mongodb+srv://adminadmin:adminadmin@messageboard.z6wdt9o.mongodb.net/?retryWrites=true&w=majority&appName=MessageBoard"