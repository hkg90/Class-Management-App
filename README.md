# Class-Management-App
Web application to help hypothetical art school manage their classes, students and faculty and class registrations.

*Setup:*
1. Ensure Node is installed
2. Ensure your MySQL database is up and running using theSQL_Table_Setup_ddq.sql file (in 'reference docs' folder - it will setup the database tables file) either locally or using your choice of hosting method. Make sure your dbcon.js file is adjusted accordingly with your db account info.
3. Install dependencies and run app with:
npm install
node index.js
4. Open http://localhost:54545/.

*Directory Layout*
index.js
The driving program which starts the server and loads everything else in as required.

dbcon.js
The local dbcon.js file which stores your database login info. It can either be configured to point to a local database, or the OSU-hosted databased.

/static/
Stores all static resources such as CSS/images and JS processing code for some page's route handling.

/routes/
Stores the JS processing code for each page's handling route handling.

/views/
Stores the HTML templates for each page (including folders for the base template, footer and header of each page).

Frameworks/Libraries being used
Node
Essentially the backend server runetime environment, see above

https://nodejs.org/en/ https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction

Express
The framework that processes HTTP requests, accepting input (e.g. from a GET or Post request), processing it, and serving the relevant content back to the requestor. See above.

http://expressjs.com/

Handlebars
HTML templating (based in Javascript), e.g. dynamically injecting pages with content

Bootstrap
Very popular CSS styling/layout framework

https://getbootstrap.com/