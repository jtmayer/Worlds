# Worlds
Terraria game worlds used by a community of friends.

# How To Setup (Once per Computer)
1. Download & install Git: https://git-scm.com/downloads You may continue up to and including step 4 while you wait for step 1 to finish.
2. Sign-up for Github if you do not have one already: https://github.com/
3. Message me on Steam with your Github username: http://steamcommunity.com/id/moronicacid/
4. Open Command Prompt.
5. Type 'git config --global user.email "\<your email>"'.
6. Type 'git config --global user.name "\<your IRL name>"'.
5. Type "cd C:\Users\\\<your user name>\Documents\My Games\Terraria\Worlds". This will bring you to the correct directory.
6. Type "git init". This initializes a repository locally in your Worlds directory, do not delete the .git directory.
7. Type "git remote add origin https://github.com/jtmayer/Worlds.git".
8. You may want to delete/backup worlds with the same file name as the one in this repository, then type "git pull origin master". This is the command that actually fetches the files. 

# How to Host (Once at the Beginning of the Session)
1. Close Terraria, if it is already open.
2. Open Command Prompt.
3. Type "cd C:\Users\\\<your user name>\Documents\My Games\Terraria\Worlds".
4. Type "git pull origin master", if your local world is out-of-date. If you just performed the setup above, please ignore this step.
5. Open Terraria.
6. Select "Multiplayer" from the main menu, then "Host & Play".
7. Select the desired world and host.

# How to Update the Online Repository (Once at the End of the Session)
1. Quit the world. You should not be hosting a game while performing the following steps.
2. Open Command Prompt.
3. Type "cd C:\Users\\\<your user name>\Documents\My Games\Terraria\Worlds".
4. Type 'git commit -a -m "\<message>"' Where \<message> contains a condensed description of changes made to the world.
5. Type "git push origin master".

# FAQ
TBD
