# Terminal 
Iterative and recursive 
Iterative algorithms will use control-flow statements such as 
for, while, and do. Recursive, a module call itself until the condition satisfies. 
Linux 
Some common symbols in Unix/Unix-like systems: ~ / . .. && # | * 
  mkdir dirname 
  cd /path/..../
  rm file1 file2 
  mv file1 file2 /source directory/
  mv old name new name 
  zip folder.zip file1.doc file2.doc
  unzip -v folder.zip 
  zip --help 
  tar -xjvf filename.tar.bz2 
  .....(c)ompress or (x)tract,filter,list,specify -> -xjvf 
  ......tool name tar and zip type bz2 
  ls -a 
  ls | grep keyfilename 
  cat keyfilename.pub 
  pbcopy < ~/keyfilename.pub 
  vim ~/.ssh/config 

Git 
Basic setup 
  git config --global user.name "name" 
  git config --global user.email "mail"
  git config --list
  git init
  ssh-keygen -t rsa -b 4096 -c "email" 

Work in the source code pushed from remote repository
  git clone "git repo url" 
  ...make changes 
  git status 
  ...check the work progress 
  git add<file> 
  ...To track changes 
  git checkout<file> 
  ...To discard changes 
  git push  
  ...Push your work to remote repository 

Start a repository locally 
  git init 
  git status 
  git add<file>
  git remote add origin "repo url" 
   ...origin project was cloned originally from 
  git remote -v 
  git push -u origin master 
  .......branching 
  git branch 
  git checkout -b branch name 
  


  






   
