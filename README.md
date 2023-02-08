# CS615 WEEK 2
HELLO 
## changes here on project
need to save this change to git 
git status show you the changes(modify/new/delete) you made but haven't been saved/commited yet.

newly added html is untracked. so you need to add it to git
'git add .'   period meand ask git to track all files 

'git status'  double confirm the track 

'git commit -m "Added html" -m "to some desrib" '  to save to git.  '-m' is for message, you need a message in order to commit your files. could be other letter you want,. but need a message.  it's the title of the message

now we saved our code locally. still not alive on githun

'git push'  to make it online on github/remote repos.. where the project is. To push online you need to prove you own the account - SSH keys. To generate ssh KEY
~ ssh-key -t rsa -b 4096 -C "emailaddress"

'git push origin master'  origin is optional setup stands for location of our respository.  master is the brach you want to push to


git init -- initialize new git repo/folder locally  - untracked file
git add .    -- save  --- track 
git commit -m "Title" -"descrip"  -- commit change 
git remote add origin ...  (add link) ---- this is to connect 


