LEVEL 0:

Level Goal

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

Solution 
pretty easy, not much to say other than this is how ssh works.

ssh bandit0@bandit.labs.overthewire.org -p 2220
when asked for the password type it in. could you pass the password in the shell with your first request? Yup. Should you do it? Probably not as it might become part of your shell history! 

Afterwards, check out what`s on your drive. Simply use
ls

it will show you the readme. now, use:
cat readme

and the password will be shown.
The password you are looking for is shown there...  