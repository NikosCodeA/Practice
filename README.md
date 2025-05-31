# Practice
This is a test repository to exercise the workflow   
Basic git commands:  
git init (initialize, that is create the .git in the local directory)   
    add . (add all the files contained in the local directory )  
    log --graph (display a story of commits with a small graph)  
    diff (display the difference between the current state of the folder and the latest commit)
    diff --cached (show the differences between the files before using the add command )  
    commit (create a time stamp of the files at the state it were after the add)  
git clone http..(it makes  a copy of a remote file )  
git remote add origin http... (Like a shortcut in order to operate commands as it was reffered   
                               to a local folder )  


git restore --source=<hash> -- . (restore the folder in a previous state defined by the commit)  

-> HEAD~5   : That means 5 commits back from HEAD

git revert (Safe for shared commits since it does not  delete any commits )
git rebase -i (-i means interactive. You can edit the commits, that is change description or d
                elete) pick the first and squash all the others 
                

git cat-file -t <HASH> (Show what kind of thing is the object described by <HASH>)                
git cat-file [commit|tree|blob|tag] (show the file decripted)
git ls-tree <HASH> (show the tree decripted )

