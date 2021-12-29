# Collaborate With Git
# Collaborate With Git Command

## Installation 

  > Install Git Nano on Windows 
 
  > https://oznetnerd.com/2017/09/02/git-nano-windows/
  
  > git config --global core.editor nano

## 1. First Clone it from GitHUb : 

  > git@github.com:kaamrul/CollaborateWithGit.git

## 2. Create a New Branch :

	> git checkout -b kamrul

## 3. Do Your Work & Push from Local Server to Live Server
	
	> git status
  
	> git add .
  
	> git commit -m "Now Give Your Comment"
  
	> git checkout master
  
	> git pull origin master
  
	> git checkout kamrul
  
	> git rebase master
  
	> git push origin kamrul
  
	
## 4. Create Pull Request From GitHub Live Server

## 5. If Conflict 

  > git add .
  
  > git commit --amend
  
  > Ctrl+o hit enter & Ctrl+x hit enter
  
  > git rebase --continue
  
  > git push origin kamrul
	
  
# Picture of These Command


![gitCollaborateCMD](https://user-images.githubusercontent.com/37633219/147628951-51405e7e-0614-4709-89ec-74c56aa6b458.JPG)

  
# If Conflict

![conflict](https://user-images.githubusercontent.com/37633219/147629878-4cdd68a4-d626-44e0-9423-4f08008b1078.JPG)

  

