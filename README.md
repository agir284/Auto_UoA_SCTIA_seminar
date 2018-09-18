# Auto_UoA_SCTIA_seminar
This project is for a seminar in continuation techniques and to study their implementation in Auto07p


I don't know if this will help anyone but I'm new to GitHub so I did a quick guide to see how to use it. 

Firstly you'll want to download the desktop GitHub version and create an account (if you don't have one). Then If you are in a mac, open the terminal find a folder where you want to place the project and run the following command:

git clone https://github.com/agir284/Auto_UoA_SCTIA_seminar

This should create a folder with all the files in the GitHub straight into your computer. Then (for those of us who use Sublime) whenever you open a new file make sure you add Folder to project -- using the folder created by the GitHub clone command -- and voila! 


To see all the new files in the GitHub repository: go to the terminal  and use git status to show whats different from your computer and the "cloud". 

Then type git add. This will add all the changes you've made in the repository. For instance, I created a python "hello world" program just to test that everything was running smooth. So I typed (in the terminal): git add test.py. This will make the change but you have to "commit them".

To do so, you type git commit -m "added test.py". You dont have to give it a message (i.e. -m "bla bla") but I did. Note: at this stage this is still not synced up! 

To do so. type: "git push".

Now, everyone in the repository can "pull" the new data that someone synced by typing(in the terminal): git pull.

NOTE: THIS WILL ONLY WORK WHEN YOU'RE IN THE DIRECTORY OF THE REPOSITORY.

