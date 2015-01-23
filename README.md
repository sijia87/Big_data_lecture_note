# Big_data_lecture_note
Jan, 22, 2015
=============

Git: when you have a repository, you have all copies of all versions?

* Repositories (main part)
* Branches (side away to try things out, can be merged back to repository later?)
* Pull requests (ask who is in charge of repositories to integrate changes to the code, you can not change by yourself, just give suggestions)
* Issues: bug tracking
* Organizations: people
* Team: group of people within organizations

working -> staging (packaging) -> history (commit)

working -> (add) staging -> (commit) history

Configure Git and other commands: 
=================================
* git config user.name "Your name"
* git config user.email "Email Address"
* git config color.ui auto
* git config core.autocrlf [input]
* git config core.editor
* git clone https://github.com/sijia87/Big_data_lecture_notes.git
* vi README.md (to edit the file)
* cat README.md (to view in terminal)
* git status
* git add README.md
* git commit
* git log (give a unique hashcode)
* git push (to push onto github)
* git push origin add-a-student (push the branch up)
* git checkout master
* git pull
* git branch (show the list of branches)
* git checkout add-a-student
* git branch -d add-a-student (delete the branch)
* git diff (to check difference bewteen copies)
* git diff --cached
* echo "SECRETS" > credential.txt
* vim .gitignore (write credential.txt in it)
* git status (then you can not see credential.txt any more)
* (try) rm .gitignore, then you can see credential.txt by typing git status

Jan, 22, 2015
===============
MapReduce: take code to the data rather than take data to the code
