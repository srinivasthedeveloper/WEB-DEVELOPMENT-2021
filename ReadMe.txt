STEPS TO FOLLOW:-

DISCLAIMER:-
	"MOBILE USERS" please enter the site with desktop mode you may get that in "options"

STEP 1:- (FORK)
	Search for "WEB DEVELOPMENT 2021" repo in "srinivasthedeveloper" account
	then open that repo you will see a small button called "fork" in the top right side.

	click "fork" then you will be redirected to your account with the copy of that repository.

STEP 2:- (CLONE)
	you will see now a green color button named "code"
	click on it then click on download as zip option
	download and extract the repo

STEP 3:- (NEW BRANCH)
	git checkout -b <yourBranchName>
		{	checkout is used to switch brance
			-b is used to create a new branch
		}

STEP 4:- (COMMIT YOUR CHANGES)
	git add .
	git commit -m "<yourOwnMeaningfulMessage>"

STEP 5:- (PUSH IT)
	git push
	(you will get a command followed by an error){that command may seems like "git push --set-upstream origin <yourBranchName>}
	copy paste and run that command 

	"boom you have completed localy guys... congragulations..."

STEP 6:- (CHECK IT)
	open the repository that you have forked you should see something like
		<changedBranchName> had recent pushes is less/more than some time
		if not make sure that you have completed the above steps clearly

STEP 7:- (PULL REQUESTS)
	click on "pull requests" button
	don't change the "base repository" and "base"
	change the "head repository" to your account and repo
	change the "compare" into "your branch name" which has changes

	then fill the "input" and "textarea" with your meaningful message (don't annoy with changes,new change,...) (do like i have changed this in that path it has those bugs and i fixed that)

	finally click on "create pull request"

