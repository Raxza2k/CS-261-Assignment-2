So I think this is how to use git easily.
You have to initialize repos online, to reserve the server space. Then operate from local using a SSH.
Go to your to CS 261 directory and initialze it as a git folder.
1) git init
Then clone the repo contents from the server.
2) git clone <SSH or HTML link from github.com>
After that the repo will be pulled locally, and you can cd into it and work. 
3)cd /dirctory from git
If you create a new file, you need to tell git to add it.
4)git add file.whatever
Then commit any changes with a message.
5)git commit -m "What you have to say."
Once you've committed to changing the files, push the updates to the server.
6)git push
