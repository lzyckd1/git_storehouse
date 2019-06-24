some tips about git:
the normal submit:
in a local file which is named as "aaa"
git init
git add .
git commit -m "balabala...."
then,you should create a new repo on github named "aaa"
when you submit the local "aaa" to origin,in the file "aaa":
git remote add origin git@github.come:yourID/aaa.git
git push -u origin master
master meas the branch name

if there is some differences between you local file and the origin, the bash might return an error,
and you can try 
git pull --rebase git@github.come:yourID/aaa.git