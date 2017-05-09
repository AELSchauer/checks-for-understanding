## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
How to set up Node projects.

2. What are some tools to help debug JavaScript code?
Pry & console.log

3. What are some tools you need in order to unit test your JavaScript?
Mocha & Chai

4. What is the syntax for invoking a function?
functionName(arguments)

5. What's the difference between `==` and `===` in JavaScript?
== will do a type conversion (so, for example, undefined == null would be true)
=== is a strict equals with no type conversion (so, for example, undefined === null would be false)

6. What's the difference between asynchronous and synchronous JavaScript? 
Synchronous Javascript will load everything in a specific order, and one script must finish before the next one can start. Asynchronous Javascript utilizes multi-threading, and so a script will run on a secondary thread and then be called back to the primary thread once it's complete; meanwhile, other scripts will run on the primary thread.

7. What's a callback function and what are some reasons when we use/need callback functions?
With asynchronous Javascript, we can run a script on different threads so multiple scripts can run simultaneously and the entire package can load faster. The callback function is the one that is run after the script completes that delivers the data back to the original source.

8. What's the biggest difference between a promise and a callback?
A promise is a callback functionality, but has syntax similar to synchronous Javascript so it can be written more easily and clearly.

9. How do we setup a route when creating an API with Node and Express?
Create the route in the server.js file

10. What's `npm` and what do we use it for?
npm is the package manager (probably stands for Node Package Manager). It's just like gems for Ruby. We use npm to install packages to a project and manage depenedencies.

#### Review  
11. What's the MVC design pattern? Describe each part of MVC?
Model, View Controller. The controller directs information between the view and the model. The model interacts with the database and provides "structure" or "behavior" for the data. The view is what the user interacts with.

12. What is AJAX? What are some benefits of using AJAX?
AJAX is a way to render individual components on a view rather than the entire view. The benefit is that it uses fewer resources and is faster to render only the components that are changing.

13. What's a background worker? When would we want to use a background worker?
There are probably a ton of different kinds of background workers, but the one I'm most familiar with is a decorator or presenter. Basically, these provide another way of refactoring data from the model.
