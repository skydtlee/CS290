Motivation
This week's assignment is to get set up with node on engineering server and GitHub. It is primarily a technical hurdle that needs to be overcome. We will go into details of Node.js in Week 7 module when we start to learn server side interactions.  For now, you only need to get the node running.  If all steps go smoothly, this assignment should be a 20 minute process, but be prepared for things to not go smoothly. Make sure to get started early on this as it can take awhile to troubleshoot problems.

Many students question why we spend Week 1 setting up a Node server when we don't cover that topic until much later in the course. This is a fair question, but the goal is to try to set up all the tools you will need early in case there are problems that we need to contact the support team about. This small amount of time invested now, will hopefully catch all the issues so you can concentrate on creating the server in Week 7, not fighting your tools.

From 2016 fall, we started to run Node on OSU's engineering server instead of Amazon server. So far, students don't have too much trouble getting it done smoothly. Just follow every step in the tutorial and don't make careless mistakes. If you run into any issues, please check/post on Piazza for clarifications.

NOTE: Setting up the Node.js on the engineering server requires the MySQL account which will be created for you by the OSU's support team at the beginning of the term.  Please don't start this work until you get a notification from the instructor that the account has been created. Otherwise, you will get errors while trying to connect to the database. You can set up your GitHub account first. If you add the course late please email Luyao Zhang(zhangluy@oregonstate.edu) as soon as possible because the support team needs to manually update their rosters to include anyone not present from Day 1.

Requirements:

Set up Node on Engineering servers
Start the Node.js process
Create a GitHub account (We would highly recommend requesting a student dev pack as well from https://education.github.com/ (Links to an external site.), you get a premium account for free and some other neat software). If you already have an account, you can use that one for this course and do not need to create a new one.
Create a GitHub repository and add some content to it.
 

What to turn in
Submit the following two addresses on Canvas as text.

The address where we can access Node on Engineering Servers.
This will be an URL in the form of http://flipX.engr.oregonstate.edu:YYYYLinks to an external site., where flipX should be flip1, flip2, or flip3, and YYYY is the port number you choose, for example, 5678.
After following all the steps,  once you go to view the webpage flipX.engr.oregonstate.edu:YYYY, the page displays "MySQL results...", that means your link is working and the forever process is up.
A link to your GitHub repository
This repository should have at least 2 files (any file type or content works) added to it.
If you set your repository as public, everyone can access it.  If you set it as private, please add OSU-CS290-Tester as a collaborator (you do not need to wait for the response from the Collaborator) so TAs can use the tester account to check your repository for grading.
Any submissions that do not include the Flip server URL, GitHub repo URL, and/or do not add OSU-CS290-Tester as a collaborator, will receive a 1 point deduction.

Hints/Tips
Before you start the first step, connect to OSU VPN and keep the VPN connection during the whole setup process.
You do not need to change your default password and we think it is better to leave it as default since if something is not working for you, the TAs and instructors can test your account on our side.
If you do change the default password, you need to update it in the dbcon.js file.
When you try one port number and it is not working, you need to switch to another port number by repeating from step 5; each server requires a unique port number.
Be careful of typos when you change the content of the files.
Try running your application using node first. It will spit out error messages on the command line that you can use to debug your program. Forever suppresses these error messages and puts them in a logfile. If the error message you get says "EADDRINUSE" it means you need to select a different port. If it says "ECONNREFUSED" or something along those lines it means that there may be an issue with your database configuration file. So double-check your dbcon.js and compare it to the instructions provided.
If you already have the GitHub account, you can use that for this course.
