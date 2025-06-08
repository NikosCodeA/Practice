# Practice
(This directory will stay the same except this specific file)

This is a test repository to exercise the workflow (i have the description of 
some of the git commands so as to remember )   
Basic git commands: 

git init (initialize, that is create the .git in the local directory)   
    add . (add all the files contained in the local directory )  
    log --graph (display a story of commits with a small graph)  
    diff (display the difference between the current state of the folder and the latest commit)
    diff --cached (show the differences between the files before using the add command )  
    commit (create a time stamp of the files at the state it were after the add)  
git clone http..(it makes  a copy of a remote file )  
git remote add origin http... (Like a shortcut in order to operate commands as it was reffered   
                               to a local folder. When you clone a dir there is no need to do
                               that )  


git restore --source=<hash> -- . (restore the folder in a previous state defined by the commit)  
                                 (the folder changes but commits stay as they are)

-> HEAD~5   : That means 5 commits back from HEAD (it is not a command, just mentioning it)

git revert (Safe for shared commits since it does not  delete any commits )
git rebase -i (-i means interactive. You can edit the commits, that is change description or d
                elete) leave the first and squash (s) all the others. If you want to change 
                the description of a commit replace <pick> with <reword>. After that 
                write git rebase --continue 
git commit --amend (Change the last commit message) 
    reset --hard <HASH> (Goes to the commit mentioned by <HASH> and deletes all 
                            other commits after it )                
                

git cat-file -t <HASH> (Show what kind of thing is the object described by <HASH>)                
git cat-file [commit|tree|blob|tag] (show the file decripted)
git ls-tree <HASH> (show the tree decripted )



