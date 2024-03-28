Case 1:
$ git init 

$ git add .

$ git status

$ git remote add origin https://github.com/DucHuy245/2011060374_PhoDucHuy.git

$ git commit -m'Huy commit'

$ git push origin master

$ git branch

$ git branch Huy

$ git checkout Huy

//Sửa code ở nhánh

$ git add .

$ git status 

$ git commit -m'Huy test'

$ git push origin Huy

$ git checkout master

$ git merge -m'merge Huy into master' Huy

$ git push origin master

$ git branch -d Huy

Case 2:

$ git clone https://github.com/DucHuy245/KTBT.git

$ git add 'testcase2.html'

$ git commit -m 'add file test'

$ git pull

$ git push origin -u master

$ git remote -v 

$ git remote add newup https://github.com/DucHuy245/2011060374_PhoDucHuy.git

$ git remote -v

$ git fetch huy

$ git merge huy/master

$ git add .

$ git commit -m'case 2'

$ git pull

$ git branch Huy

$ git checkout Huy

$ git add .

$ git commit -m'new branch'

$ git push origin -u Huy

$ git checkout master

$ git merge -m'merge Huy into master'

$ git push origin -u master -f

$ git branch -d Huy

$ git commit --amend

$ git push
