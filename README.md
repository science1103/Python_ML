  
 My Repositoy : https://github.com/science1103/Python_ML.git
 
1. Bash my File 
  1.1. If this process is first move to repository
  
  <On Bash Terminal Setting> 
 > git config --global user.name "My Git Hub name" 

 > git config --global user.email "My Email" \ 

2. git status (check working dierctory) 
  - check my working directory which are my files on the folder  

3. Let's add my file to Staging Area 
  > git add '<File name>' or git add * \
  > git status (check my file has added to staging area)  
  
 4. Let's Commit to my Github's Repository 
  > git commit -m '<MEMO>' \
  > git push origin master \
    - origin : Remote Storage
    - master : branch's name 
  > Enter My github Account (ID / PW) \ 
  
  4,1 if error has occured ? 
- [rejected] master -> master (fetch first)
  > git push origin +master

  5. Done 
    - Now I'm ther Master of Commit 
