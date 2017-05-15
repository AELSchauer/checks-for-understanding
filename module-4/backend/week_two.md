## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What is Webpack and why is it useful?

Not sure exactly. Is it a compiler of some type for front end Javascript?

2. When do you want to use event delegation?

I don't know

3. What's one difference between ES5 and ES6?

ES5 uses prototypes when creating "classes", ES6 actually uses classes that is similar to other OOP languages.

4. What's the deal with semi-colons in JavaScript?

They're useful, but not really necessary any more. They're supposed to indicate the end of a command.

5. How are you using the MVC design pattern in your Quantified Self project?

MVC on the backend with the output being an API instead of a traditional view. On the front end, our model is supposed to be consuming the API instead of a database. I don't really know how a "controller" comes into play on the front end. FE is more confusing.

6. How do you execute raw SQL in node?

With the 'raw' method.

7. What is CORS?

Not sure. Some PITA thing on the backend that, to use Nate's words, really shouldn't be a problem but it is.

8. What are some steps to avoid CORS?

Install some 'gem' and add some config stuff to our server file.

#### Review  

9. Why do people say "HTTP is stateless"?

Stateless because the server is not holding some information about the browser session. It sends the request and then terminates the connection.

10. What is a RESTful API?

An API that uses the CRUD (GET, POST, PUT, DELETE) requests.

11. What are some main characteristics of a team following an agile workflow?

Regular delivery of the product to the end users for feedback. Doing all steps of product development (requirements, design, build, test, and deliver) at the same time instead of discretely, one after another.

12. What are some advantages/disadvantages to using OAuth to authenticate a user?

Advantages is that you don't have to worry about storing passwords and your user doesn't have to worry about storing another password. Disadvantage is that you don't have control over your user accessing your app. Another app does. Plus, tokens and refreshing are a PITA.
