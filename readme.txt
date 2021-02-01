1. create a folder
2. open the directory in IDE
3. Create some file in the directory
4. Run the command : git init

MacBook-Air:from_local username$ git init
Initialized empty Git repository in directory path/from_local/.git/

5. now its a git repository
6. Now do git add .
7. git commit -m "First commit"
8. create repository 'from_local' in github
9. copy the ssh key for that git repository
10. Run the command : git remote add origin git@github.com:git_user_name/from_local.git

this is done sothat local git knows to which remote repository in the github we need to push the code

11. now if we do 'git push' it wont work

12. we can use the command git push origin master

this command we explicitly mention, we want to push the changes to the master branch of the origin


13. to use the short form of the command(git push origin master) we can run the below command
git push --set-upstream origin master

Now local master branch is linked to remote(github) master branch


14. now we can do some changes, do 'git add .', do git commit -m "second commit",
then with only 'git push' it will update the remote

