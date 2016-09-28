
Anna Villani
CSCI 5828 - Foundations of Software Engineering
Homework 02

  603  git init
  
  604  vim README.md
  
  605  git add README.md
  
  606  git commit -m "commit 0"
  
  607  vim README.md
  
  608  git add .
  
  609  git commit "commit 1"
  
  610  git commit -m "commit 1"
  
  611  vim README.md
  
  612  git add .
  
  613  git commit -m "commit 2"
  
  614  git log
  
  615  git checkout 1cda6e43af76f0e75a18ab3fdfeb7510023db3f2
  
  616  git checkout -b bug-fix
  
  617  vim README.md
  
  618  git add .
  
  619  git commit -m "commit 3"
  
  620  vim README.md
  
  621  git add .
  
  622  git commit -m "commit 4"
  
  623  git checkout master
  
  624  git merge bug-fix
  
  625  vim README.md
  
  626  git add .
  
  627  git commit -m "commit 5"
  
  628  git checkout bug-fix
  
  629  vim README.md
  
  630  git add .
  
  631  git commit -m "commit 6"
  
  632  git log
  
  633  git checkout f40650058569a32ed1fb6bebf29d5d221035cdaf
  
  634  git checkout -b bug-fix-experimental
  
  635  vim README.md
  
  636  git add .
  
  637  git commit -m "commit 7"
  
  638  vim README.md
  
  639  git add .
  
  640  git commit -m "commit 8"
  
  641  vim README.md
  
  642  git add .
  
  643  git commit -m "commit 9"
  
  644  git checkout master
  
  645  vim README.md
  
  646  git add .
  
  647  git commit -m "commit 10"
  
  648  git checkout bug-fix
  
  649  git merge bug-fix-experimental
  
  650  vim README.md
  
  651  git add .
  
  652  git commit -m "commit 11"
  
  653  vim README.md
  
  654  git add .
  
  655  git commit -m "commit 12"
  
  656  git checkout master
  
  657  vim README.md
  
  658  git add .
  
  659  git merge bug-fix
  
  660  vim README.md
  
  668  git add .
  
  669  git commit -m "commit 13"
  
  672  git add .
  
  673  git commit -m "commit 14"
  
  674  git checkout master
  
  675  git push -u origin master
  
  676  git checkout bug-fix
  
  677  git checkout master
  
  678  git checkout bug-fix
  
  680  git push -u origin bug-fix
  
  681  git checkout bug-fix-experimenta
  
  682  git checkout bug-fix-experimental
  
  683  git push -u origin bug-fix-experimental
  
  684  git checkout master
