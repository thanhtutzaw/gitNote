1.git clone --filter=blob:none --sparse  repoLink.git  
git sparse-checkout init --cone  
git sparse-checkout add foler/subfolder  // to download specific folder from big repo  

/////////


2.git init = initialize git for new project


3.git clone = clone the existing repository to local machine


4.git status = to see changes in the project


5.git add file_name = save changes of selected file before commiting
git add . = save changes of all files before commiting


6.git commit -m "commit_name" = commit changes to the repository
git checkout code_number = switch to another commit
git reset --hard code_number = switch to previous commit & delete all commits after that switched commit


git log = to show commit logs
git log --oneline = to show logs in single-line per log
git log --oneline -n [nth] = to show nth logs ( nth should be 1, 2, 3, 4, ... )
	Example: git log --oneline -n 2  = only 2 logs will show


git restore --staged file_name(or). = restore to previous version after git add (removed all added changes from local git)


git restore file_name(or). = restore to previous version before commiting the latest changes
Note:
- git restore file_name(or). doesn't removed newly added folders & files
- this will remove your latest changes permanently


git clean -f = remove newly added files
git clean -fd = remove newly added folders


git branch = to inspect branch list of the repository
git branch branch_name = to add new branch to repository
git checkout branch_name = switch to another branch
git branch -D branch_name = to delete branch


git fetch origin = get the latest updates form origin to local machine


git push -u origin branch_name = to push changes from local machine to github


git pull origin branch_name = to pull changes from github to local machine


ssh-keygen = to generate SSH Key
cat -/.ssh/id_rsa.pub = to lookup the generated SSH Key


_________________________________________________________________________
26 Must-Know Git Commands in 2021 - 
https://raftlabs.medium.com/26-must-know-git-commands-in-2021-4160fbe7272
