# LinuxCommands
*These commands shouldn't be used in production without properly checking that they wont conflict with existing configuration.*
*Beware of lowercase/uppercase format in some environments.*
## LetsEncrypt
### ./letsencrypt-auto run
* Updates LetsEncypt
* Runs LetsEncrypt *Will ask for a password*
* Tick which domains you want to enable HTTPS for
* Choose secure to redirect HTTP requests to HTTPS.
* Congratulations, you're domains are now running on HTTPS.

## Apt-Get
### apt-get update
Resychronises the package list files from their sources. The sources are specified in /etc/apt/sources.list
### apt-get upgrade
Upgrades all currently installed software packages, should be ran after apt-get update to ensure latest versions.
### apt-get install "package"
Installs a specified package, such as apache2.
### apt-get purge "package"
Removes the specified package, such as apache2.

## Git
### Git Init
Initialises the current directory as a repository.
### Git Add .
Adds all files in the currect directory to the repository, staging them for a commit.
### Git Commit -m "Comment"
Commits the files that you've staged via the previous command, along with a comment.
### Git Remote add origin "URL"
Adds the url for the remote repository for the local files to be pushed.
### Git Remote -v
Verifies the remote repository, will ask for a username and password.
### Git Push origin master
Pushes files to the origin master repository.

## Basic
### cd
Changes directory to root directory.
### cd "dir"
Changes directory to the specified directory.
### ls
Lists all files and folders in the current directory.
### mkdir "dir name"
Creates a directory with the specified name.
### whereis "package name"
Finds package location.
### poweroff
Shuts down the server.
### reboot
Reboots the server.

## Teamspeak 3 Server
### service teamspeak3 restart
Restarts the teamspeak3 server.
### service teamspeak3 stop
Stops the teamspeak3 server.
### service teamspeak3 start
Starts the teamspeak3 server.

## VNC
### service vncserver stop
Stops the VNC server.
### service vncserver start
Starts the VNC server.
