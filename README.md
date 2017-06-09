# Homework #6

## Instructions
---
1. Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old.  Doing this will help you quickly discover any holes in your understanding.  Ask your questions on Slack.

	* Functions
			Functions are very useful when it comes to programming. They allow us to store code in a 'function home' and then we can retrieve that code any time we call that function. It's a great way of being organized. Think of it like having a homework folder. If your teacher gives you science homework, you place that homework in your science folder. When you need to retrieve that homework - you know where to find it.

	* Parameters
	    Parameters are what we put in between a functions parenthesis. By storing the name our code is able to recall once our function is run.  
			Ex:
			function addByFive(num) {
				return num + 5;
			}
      In this example, 'num' is the Parameter. 

	* Arguments
	    Parameters and Arguments work together. Parameters sets the stage with the name between the functions parenthesis (when we first create a function), and when we are about to call the function, we input an Argument that is stored in that Parameter.
      Ex:
			addByFive(5);
			We get 10.
      5 takes the place of 'num'.

	* `if` statements
	    If statements allows us to have options with how we want our code to run. If (option A) do this. Else (do that). Think of it like getting ready for school in the morning. If I wake up on time - I won't be late. Else - I'll be late.

2. Install Node and NPM.  NPM comes packaged with Node. https://nodejs.org/en/download/

3. Download (clone) this project folder from GitHub.

4. Navigate into the downloaded folder using Terminal(Mac) or Command Prompt(Windows).  `ls`(Mac), `dir`(Windows) and `cd <directory_name>` are the commands you need to navigate around.

5. Once you are in the folder type the command `npm install`.  This will fetch all of the needed requirements for the project.

6. Run `npm test` to run the automated tests.  At first all of the tests will be broken.  You will fill out the functions in `exercises.js` to make the tests pass.


#### Congratulations on finishing Homework #1!
Apply to our full-time or part-time immersive program to learn cutting edge technologies that are used by top technology companies around the world.

Our part-time and full-time courses are 13 intense weeks of focused study on the most relevant technologies.  

Class sizes are small to ensure that each student gets individual attention from our world class instructors to help them succeed.  We also provide career support both during and after the course to help you succeed.  We are committed to your success.

For more information visit: https://www.lambdaschool.com
