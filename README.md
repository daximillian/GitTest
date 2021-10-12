# GitTest
This repo is meant to help you get some basic hands on experience with the most basic git commands.  
It consists of a Spice Girls lyrics txt file - wannabe.txt - that needs some fixing,
And a simple python script that contains a few very simple bugs.

To work with this git repo, follow the following steps: 
1. Fork the https://github.com/daximillian/GitTest.git to your Github user. There's a fork button on the top left of the Github site. Now you have a copy of my repo to work on privately, without affecting my repo. I'll refer to your copy with the $USER variable here. Replace that with your Github user name. 
2. Create two __separate__ folders on your local machine. Call one folder Sheldon, and one folder Penny.
3. cd into the Sheldon folder
4. git clone https://github.com/$USER/GitTest.git
5. cd into the Penny folder
6. git clone https://github.com/$USER/GitTest.git
7. cd out of the Penny folder
8. You are now going to simulate two programmers working on the same codebase at the same time: Penny and Sheldon.
9. cd into the Sheldon folder and fix all the BOTH and SHELDON lines in the wannabe.txt file.
10. cd into the Penny folder and fix all the BOTH and PENNY lines in the wannabe.txt file.
11. Your changes in both folders are local. You are now going to add them to the server copy, the repo you forked and cloned from Github in this case.
12. You're going to stage all your changes, and comment on them with the following commands:
13. git add .
14. git comment -m "add Penny's fixes to the wannabe.txt file"
15. Now you're going to push the staged Penny changes to your forked folder:
16. git push origin main
17. Did it work?
18. cd into the Sheldon folder. 
19. You're going to stage the Sheldon changes now:
20. git add .
21. git comment -m "add Sheldon's fixes to the wannabe.txt file"
22. Now you're going to push the staged Sheldon changes to your forked folder:
23. git push origin main
24. Did it work?

