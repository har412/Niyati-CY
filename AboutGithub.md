# What is Github?

- Github is called as ```Distributed version control System ```. 

1. Version control feature .
2. Collaboration .
3. we can deploy static website .
4. Managable code on cloud .

## Steps to host a static website on github

- Create a public repository on github.
- go to your local folder where code is present and open terminal.
- Command in terminal :-
- ls(list)  --> gives all the files and folder present
- cd (change directory) --> move to the next folder in which we want to go.
- Use the folowing Commands:-
- ```git init``` we are initializing this folder as a git repository. [Use for first time only]
- ```git add .``` add all the changes we did
- ```git commit -m "initial commit"```  here we create a breakpoint to come back as a version with a message
-  Create a connection betwen the local and cloud repostory
 ```git remote add origin https://github.com/har412/testLoginForm.git```  [Use for first time only]
- Push the Code ```git push origin master```