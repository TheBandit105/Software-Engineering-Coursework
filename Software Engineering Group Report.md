### Module Code: CS1SE16

### Assignment Report Title: Software Engineering Group Coursework 2

### Student Number: 27015244, 28007374, 28010596, 28004779, vn011949 (Left the course)

### Authors: Charith Avancha Fragoso, Shavin Croos, Ali Hussein Fadel, Axel Wise (Note: Desmond Dakura left the course at the time of the coursework)

### Date Completed: 20/03/20

### Actual Hours Spent: 18 Hours









































### Introduction

The aim of this project is to create a web - based game, in which the users, being university students, will log in and play a history-based, graphical adventure game. When playing the game, the students will earn points for every correct solution provided to the puzzles given. In order for them to obtain the solutions to these puzzles, the students will have been expected to have read and understood many historical sources (e.g. books, internet etc.). The game will include several sub - systems which will work together in order for the game to run and function correctly as intended by the developers. For example, the game will feature a login system, where the user will create an account for the game. During the gameplay, the score achieved by the user will be recorded to the user’s id and stored in the database entry for the account. Another system is for the puzzle solutions, where the correct answers will be revealed after the user inputs their answers to the questions given in the game. The game will also feature a system where the users can use an inline forum, which will allow them to collaborate on ideas with other users doing the same course. The game will run on the university’s internet network and will use a separate web-server to deliver the pages across the network to any device, of the students’ choice, that is connected to the network.

### Product plan

During development it is crucial that the order in which the parts of the project are developed is outlined before production begins. Within the software engineering group, we also established a task board using Trello. This helped us to create goals for ourselves that could be seen by other members of the group, and also to give us a general direction when completing tasks.

![Inline image](https://github.com/TheBandit105/Software-Engineering-Coursework/blob/master/Trello%20Snapshot.png)

As seen we set many goals with this task board and we could also use it to see which parts of the project team members had completed.
When it comes to planning which parts of the project will be developed first, it seems logical to develop the crucial features of the program first. This would include the log in system, followed by the implementation of the puzzles. Then the databases for scoring can be worked on. The reasoning behind this is because the earlier a module is implemented, the earlier it can be tested to ensure it is robust. It should be known that the graphical side of the project should be completed last, as it does not directly contribute to the main cycle of the program, and therefore is not a high priority at the beginning of the development cycle.





### Quality goals

When creating goals for a project, it is a good idea to follow the SMART criteria. These criteria include 5 factors, those being: Specific, Measurable, Achievable, Realistic and Timebound. Choosing goals for a project means that being specific is vital. This lets the developers know what you want as a final product and makes it easier and quicker for them to create it. It also allows you to create goals which mean that you know what to expect with the outcome of the project. When creating specific goals, you will most likely look at who you are going to involve achieving the goal of the product, in the case of this project it would be developers and designers as well as students as testers. What you are trying to accomplish with this product can get very detailed, for the web-game however, we are trying to achieve a game that will act as a learning platform for students. There may be requirements or stages of development that you will know beforehand will cause trouble, defining these will make things easier during future stages. The goals that you specify should be measurable and you should define the way you will measure it as well. For example, the popularity of the game amongst students for studying/revision purposes. These goals should also be achievable, having small goals that lead up to a final major achievement is a good way to develop the web-game. Setting realistic goals also means that a realistic time frame should be used. As the web-game is supposed to be a 2D design with 3 different scenarios. The 6 Month time frame should be enough. This however should consider any problems that the developers may run into during development or during testing.



### Test Process and Plans

4.1) Test Process

Before the web game is released to the public, the product needs to undergo several test processes to make sure that the web game works in accordance with the requirement specifications that were outlined by the client. The overall test process will require the game to go through 4 main stages of testing in order for the game to be certified for use. The first stage of the 3 part test process is called the component (or unit) testing. This type of testing will help to identify any underlying issues with the components that make up the architecture of the game. This test is normally carried out by the developers of the game. After this, the individual components of the web game will be integrated together and will go through integration testing.
This stage, the combined components are tested as a group to ensure that the integrated system is ready for system testing. The flow of the data from one group of components to the other is checked during this test. The system testing is the third stage of the testing process, where the web game is tested as a fully, integrated system. It is meant to check whether the system meets the requirements as asked for by the client and evaluates the functional and non-functional need for the testing. Finally, the acceptance testing is the last stage of the testing process, in which it is carried out in order to find out if the requirements of the specification are met as per its delivery. This part of the test process is done by the user or customer.

4.2) Component testing
  
Component testing is a software testing type, and it’s the process of testing each individual component alone, separately from the other components, to make sure all the components work perfectly. The diagram below shows the process of testing out the individual components.

![Inline image](https://github.com/TheBandit105/Software-Engineering-Coursework/blob/master/Component%20Testing%20Diagram.png)






[1]

Component testing varies from domain to domain and organization to organization, and they differ depending on what type of Development Life Cycle model has been chosen, the complexity of the software/applications that’s being tested, and testing the components individually or with other components within the software. The systems Development Life Cycle is a theoretical model used in project management that explains the process involved in an information system development project, from an initial feasibility study through maintenance of the completed application. There are many different System Development Life Cycle methodologies, such as Rapid Applications Development, Build and Fix, and Synchronize-and-Stabilize, to guide the processes involved. The original System Development Life Cycle is Waterfall, and another common model is called Agile Software Development.







4.3) System testing

System testing (ST) is simply the testing of the system in its entirety and fully integrated, which means that all the components are combined together in order to check and verify whether the system works as intended by the requirement specifications or not. ST is a type of testing that is known as black box testing, which assesses the running of the given system from a user point of view, given the specification document. This testing is important for many reasons. First of all, system testing allows for completing a full test cycle and secondly, it is carried out in an environment which is almost like the production environment and thus stakeholders can get a good concept of how the user will react to the system. This will lead to the reduction of after-deployment troubleshooting and calls for support on the usage of the system once the product goes live to the public. In this case, once the parts of the game have been tested individually, tested together and assembled, the game needs to go through ST. The game will be checked for different aspects, as clearly stated in the requirements, such as if performance of the game will run smoothly on any device used, if the graphics of the game are nicely designed and free of any bugs and if the user controls (e.g. using the WASD keys) work correctly as they should for the game. ST will also check and assess the other aspects of the web game such as the load capacity and security testing.

![Inline image](https://github.com/TheBandit105/Software-Engineering-Coursework/blob/master/System%20Testing%20Plan.jpg)






[2]

4.4) Acceptance testing

Acceptance testing is used at the end of the development cycle to determine whether the system requirements have been met. The results are given in a true or false matter. These tests are usually performed in collaboration with the buisness customers/analysts, this is to ensure that the tests are up to standard with the system requirements. The testing is meant to ensure that development is headed in the right direction and that the customers needs are satisfied. Acceptance testing is different from system testing as it does not test whether the system as a whole will crash, but rather that it satisfys the success criteria, which is often documented before development begins.
Applying acceptance testing to the project at hand, it must test that the software is satisfactory at providing historic learning material, this can be done by using a “test scenario”, where a client using the software is simulated. This test can be observed by the stakeholders and buisness analysts to determine the acceptability of the software.


### Test cases    

Valid Login:
Scenario: Logging in with valid credentials
Given the user is on the login page
When the user enters their credentials
And they enter the right Username and/or Password
And they click login
Then they should be directed to the Main Menu

Invalid Login:
Scenario: Logging in with invalid credentials
Given the user is on the login page
When they enter their credentials
And they enter the wrong Username and/or Password
And they click login
Then they should be redirected to the login page again with the message "Invalid credentials"



New High-score entry:
Scenario: Adding a new highscore entry
Given the user is working on a scenario
And the user finishes the scenario
And the score they recieve is the highest achieved for the said scenario
Then this new score should be shown on their profile and on the leaderboard


Sanitising User entered text:
Scenario: Inappropriate use of account
Given the user is trying to access files and websites that are not meant to be accessed
And the user successfully accessed the files of websites
And the user uses those files or websites inappropriately
Then the user will get temporarily banned for inappropriate use of account


### Project management

![Inline image](https://github.com/TheBandit105/Software-Engineering-Coursework/blob/master/Communications%20screenshot.PNG)

![Inline image](https://github.com/TheBandit105/Software-Engineering-Coursework/blob/master/Discord%20Communication%20Screenshot.png)

### References

Guru99 2020, What is System Testing? Types & Definition with Example, Guru99, viewed 13 March 2020, 11:24 pm, <https://www.guru99.com/system-testing.htm l>

Software Testing Help 2020, What Is System Testing - A Ultimate Beginner’s Guide, viewed 13 March 2020, 11:24 pm,  <https://www.softwaretestinghelp.com/system-testing/>

Guru99 2020, Levels of Testing in Software Testing, Guru99, viewed 20 March 2020, 12:48 am, <https://www.guru99.com/levels-of-testing.html>

Smartsheet. 2020. The Essential Guide To Writing S.M.A.R.T. Goals. [online] Available at: <https://www.smartsheet.com/blog/essential-guide-writing-smart-goals> [Accessed 10 March 2020].

Guru99 2020, What is Component Testing? Techniques, Example Test Cases, Guru99, viewed 19 March 2020, 7:00 pm, < https://www.guru99.com/component-testing.html>[1] 

Google.com. 2020. Gherkin Code Test Cases - Google Search. [online] Available at: <https://www.google.com/search?client=firefox-b-d&q=gherkin+code+test+cases#kpvalbx=_9Y90XtnwF_Xggwfe7ovwCA25> [Accessed 17 March 2020].

GeeksforGeeks 2020, System Testing, GeeksforGeeks, viewed 20 March 2020, 10:09 am, <https://www.geeksforgeeks.org/system-testing/>[2]

Note: We used Discord over Trello for the communication part of the work as it was more easier to use and we had more experience with Discord than with Trello.
