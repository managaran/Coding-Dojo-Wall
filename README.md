# Private-Wall

Objectives
Practice connecting a Flask application to a MySQL database
Include login and registration
Self Join relationships
Continue to think about web security and how others could potentially hack your site
For this assignment, a user's "wall" is a list of their private messages. Once a user has logged in, they can view their wall and, on this same page, the logged in user can also send messages to other users. The yellow sticky notes indicate basic functionality. Review the green sticky notes for Ninja Bonuses and purple sticky notes for Sensei Bonuses.

<img src="https://s3.us-east-1.amazonaws.com/General_V88/boomyeah2015/codingdojo/curriculum/content/chapter/1631032718__private_wall.gif">


Additional Sensei Bonus
For the delete functionality, do not allow someone to remove a message that doesn't belong to them. If someone tries to remove a message that doesn't belong to them, have your app display the following:

<img src="https://s3.amazonaws.com/General_V88/boomyeah2015/codingdojo/curriculum/content/chapter/danger.png">


You don't really need to build the feature to report the IP address, but do log the user out if they try to remove a message that doesn't belong to them for the second time in a row. We'll leave it up to you to find out how to find the IP address of the user (a simple google search will show you how to do this in Flask).
