Directions:
Create an object called facebookProfile. The object should have 3 properties:

your name
the number of friends you have, and
an array of messages you've posted (as strings) -- include at least two messages.
The object should also have 4 methods:

postMessage(message) - adds a new message string to the array
deleteMessage(index) - removes the message corresponding to the index provided
addFriend() - increases the friend count by 1
removeFriend() - decreases the friend count by 1
HINT! Here are some array methods you might want to use:

addition at the end is done using the push() method - MDN: Array.prototype.push()
addition or removal at a specific index is done using the splice() method - Array.prototype.splice()
deletion from the end is done using the pop() method - MDN: Array.prototype.pop()
Running Your Code
Enter the following in the terminal to run your code and the test code:

node facebook-friends.js
When your code runs, you should get output that looks something like this:

Name:  Udacian
Messages:  [ 'Message 1', 'Message 2', 'Message 3', 'Message 4' ]
Messages:  [ 'Message 1', 'Message 2', 'Message 3', 'Message 4', 'New message!' ]
Messages:  [ 'Message 1', 'Message 2', 'Message 4', 'New message!' ]
Friends:  25
Friends:  26
Friends:  25