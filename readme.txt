this is a combination of several python scripts from several sources

 
1. first fork the repository 

2. the clone the fork locally 

	git clone git@github.com:<your github name>/PythonScripts.git

3. add the PythonScripts master branch as a remote
	cd PythonScripts
	git remote add ps git@github.com:margauxmolina/PythonScripts.git

4. bring the master up to date with PythonScripts/master
	git pull --rebase ps master:master

5. Create a topic branch to make changes on
	git checkout -b <topic_name>

6. make some changes 
	add python scripts or update the readme.txt

7. push changes to your origin to save work
	git add .
	git commit -m "useful commit message"
	git push origin <topic_name>:<topic_name>

8. issue a pull request and solicit a review


