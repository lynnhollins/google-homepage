NOTE: FEEL FREE TO ASSESS MY PROJECT AND GIVE ME AS MUCH FEEDBACK AS YOU WOULD LIKE.
/* DAY # 2 */
I started this google project with certainty that I would complete within 2 to 3 hours max, but I sure was mistaken! I on day 2 and I am just starting to see the light at the end of this particular tunnel.  The HTML portion seemed to go well, but the css is causing me some problems.  So far, I have been done this project without using Devtools on the google main page, just visually looking at google main; however I have used devtools on the mock page. Doing it this way is really making me work.  

/* DAY # 1 */
At this time I am doing a HTML/CSS project;

I am learning to perform many fjuntions using the Terminal/command line;

I have gone over how to clone the git repository to my local computer using
    git clone #    (# = the SSH address)

then use the remote command to ensure the repo and local client are connected;
    git remote -v   (the URL should appear if connected properly)

I then learned how to add a file to the current directory using touch command
    touch #         (# = the name of the file I am creating)

I also use the git status throughout the process to check on the status during processes;
    git status

I learned, whenever a file is red after performing a git status check, it means the file is unstaged;
    there are three stages to git 1) Unstaged or Working 2) Staged 3) Committed

To stage file, the file must be added suing the Git add command
    git add #       (# = the name of the file to be added)
        multipile file can be added using 
            git add .           (the (.) represents all files in that current folder)

Following staging I then perform another git status check, to ensure the file have been added, the should be Green in color;

Commit files: The files that have just been staged need to be committed next
    git commit -m "Add #"       NOTE: the A in Add is capitalized (# = the name of files to commit; (.) can be used as well to commit all files)

Check git status, status should show 

Perform git log, to verify what changes have taken place;
    git log

Press shift + Q to exit log screen

If all looks good, the items needs to pushed to the GIthub Servers
    git push origin master
