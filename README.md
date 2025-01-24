# reddaiahAT1059

1.	Clone the repository.

	git clone “URL”
	Change cd to “repository name”

2.	Create the five files.

	Create the files by using  =  touch “filename.txt, py, html, css, json, xml.
	Add the data by using  =  vi “filename” -> click the I -> add data, edit the data --> click the ESC  -> enter :wq! -> click enter btn.

3.	Tracking the files.

	Check the status  by using  =  git status
	If file is untracked  =  git add “file name”

4.	Restore.

	Restore is used to return the file from the stagging area to the working area (stagging area -> working area).
	git restore  --staged “filename”.
	After we edit or add data to that file and then perform -> git add “file name”

5.	Commit the changes.

	Commit the changes by using  =  git commit -m “msg”  -> for new files
           =   git commit -am “msg”  -> for old files

6.	Push the files from local to remote.

	Push the file by using  =  git push -u origin “branch name”
                                        =  git push  -> shortcut command


7.	Add the additional data to the files, which we created previously.

	Add data by using   =   vi “file name”  -> for editing and adding data.
                                   =   cat >>”file name”  -> for adding data only.


8.	git commit -am “msg”:

	Instead of performing git add and git commit separately, we perform it in single command   =   git commit -am “msg”.

9.	Git amend:

	Git amend is used to re-edit the commit msg
o	git commit - -amend “msg” -> for latest commit
o	git commit - - amend -m “commit id” “msg”   -> for specific command

10.	Revert :


	Add the data to the files that we created previously for more commit ids, (a minimum of 3 commits is required for better understanding).

o	git revert “commit id” “commit id”  (latest commit id  -> oldest commit id)
o	After performing revert, editor is opened -> click insert -> change the commit-msg -> click ESC -> enter “:wq!”.
o	Once the revert is completed, check whether the data is deleted or not.


11.	Push:

	The purpose of the push is to update changes that ever we did in locally in the remote repository
	git push -u origin “branch name”


12.	Create a new Branch:

	git branch     -> for list out the branches
	git branch “branch name”  -> for creating new branch
	git switch “branch name”  -> for switching branch
(or)
		git checkout “branch name”


13.	Again perform everything like creating the file, adding data, committing, pushing, revert, and restore.

14.	Merge:

	Merge is used to combine data from one branch to another branch.
	Merge test branch with master branch
	git merge “branch name”

15.	Tag:

	A tag in GitHub is a label used to mark a specific point in a repository’s history, like a version or milestone.
	git tag -a “annotation (or) alias” -m “msg”  -> for creating a tag
	git tag  -> for list out the tags.
	git push   -> we have to push files and tags individually.
	git push  --tags  -> for pushing tag to remote repository.






