1. Add New File to Repository:

	git add "file"
	git commit -m "message"

2. Check the work status

	git status
	
	if <git status> tell there are modification, use:
	git diff (check the differences)

3. Back to previous versions

	git log --pretty=oneline
	git reset --hard HEAD^
		  --hard HEAD^^
		  --hard HEAD~n
		  --hard HEAD 495966sed
	git reflog