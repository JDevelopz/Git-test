# Git- commit files to your github repositories explained


Open your terminal in destination folder of your project:

$ cd ./(your project)

____________________________________________________________

Run the following commands:

____________________________________________________________

<!-- Adds git to the project folder -->
$ git add .

<!-- Check if git is added, should be a . file -->
$ ls -a

<!-- Check if there are existing git repository in the folder -->
$git innit
_____________________________________________________________

Select your branch. Add new, or change. 

<!-- Check available branch -->
$ git branch

<!-- Add new branch -->
$ git branch (name of new branch here !without ()! ) 

<!-- Select branch you want to push too -->
$ git checkout ( name of branch you want to select !without ()! )

_________________________________________________________________

Commit your files to the branch internal 

<!-- Commit all files and folders in the main project folder -->
$ git commit -m "name here what is your commit"

<!-- Single commit one file located in same folder -->
$ git commit -m "name here what is your commit" test.txt

<!-- Single commit one file located in other folder inside the main folder -->
$ git commit -m "name here what is your commit" path/to/my/file.ext

<!-- Multiple commit on more files -->
$ git commit -m "name here what is your commit" test.txt test2.txt test3.txt

__________________________________________________________________

Add your remote repositories from github. 

_____________________________________________________________________

Create a repositorie on github with name and select the branch you going to use. 
Add new repositorie.

Create a personal acces token on github.com ( write it down )

Settings > Developer settings > Personal acces token > Generate new token

___________________________________________________________________

In terminal: 

Username = Your github username 
Yourresopitorie = Name of your resopitorie you created on github.

<!-- Adds your remote repositorie url to the folder -->
$ git remote add origin https://github.com/Username/Yourresopitorie.git

______________________________________________________________________

Push your files to the remote repositorie on github. 

<!-- Push your commited items to your repositorie on github -->
$ git push -u origin (Selected branch !without()! )

<!-- Terminal will ask you a username & Password -->

Username = Your username on Github

Password = The personal access code you created on github ( see above )


________________________________________________________________________


(▀̿Ĺ̯▀̿ ̿) 'Dont worry you got this' 




