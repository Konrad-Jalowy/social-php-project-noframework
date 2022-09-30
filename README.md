# social-php-project-noframework
Project social network with udemy course - https://www.udemy.com/course/make-a-social-media-website/

# Weaknesses </br>
-Use of mysqli over more versatile PDO </br>
-Use of error suppressor operator instead of some proper error handling </br>
-Use pure PHP instead of a framework (but thats the idea of the project!) </br>
-Aside from includes classes, use of typical functional approach, mixing html, php and js in script tags </br>
-Use of jQuery (in my opinion, use of libraries like jQuery or axios is often just nothing but a habit and main advantage of jQuery - on instead of obscure addEventListener - can be done using simple alias:
Node.prototype.on = Node.prototype.addEventListener) </br>
-use of md5 hash (it is better to forget about the existence of md5 function even if we dont need some security, md5 are not safe and it function should always
create some red alert just like eval, exec, wakeup and so on...) </br>
-not sure if the project if secure - not sure if i saw enough escaping, filtering, secure sql queries and so on </br>

# Strengths and Summary: </br>
-Aside from above mentioned critique this is still a great project im greatful i could complete. Introduces the idea of how to approach creating social network project</br>
-Uses OOP, althoigh it could use more</br>
-Manages the job of managing users, their friends, posts, notifications, messages as well as the relations between them and their counterparts in the database</br>
-Use of built-in php functions</br>
-Use of regular expressions</br>
-Solves other typical PHP sub-problems, such as file uploads, pagination or convert timestamp into "Yesterday" or "X days ago" (typical PHP exercises taught at other courses) </br>
-Author knows CSS, JS and PHP well so I could learn something </br>
-Not the best course from this author, Ive completed similar but better projects with him on Udemy, but still worth doing </br>
-This projects actually contains a lot of content and does a lot of job, this is not a simple ToDo list</br>
-Could be done better and with more features in node.js and socket.io and in fact this author actually made such course and I completed it</br>
-Could be re-factored as an exercise or re-done in some framework like Laravel </br>


