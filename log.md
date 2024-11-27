# Windows PowerShell
# Copyright (C) Microsoft Corporation. All rights reserved.

# Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows

PS C:\Users\bheem> cd ../..
PS C:\> cd .\Users\
PS C:\Users> cd .\bheem\
PS C:\Users\bheem> cd .\Downloads\
PS C:\Users\bheem\Downloads> ls


    Directory: C:\Users\bheem\Downloads


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        11/27/2024  11:30 PM                node-todo-cicd-master
d-----        11/26/2024   8:33 PM                Portfolio-website
d-----        11/23/2024   5:21 PM                simple-java-docker-main
d-r---         11/6/2024  11:26 AM                Telegram Desktop
-a----        10/24/2024  10:02 PM         400018 1729787562389-certificate.png
-a----        10/24/2024   5:18 PM          39010 3-tire_App.pdf
-a----        10/24/2024   1:33 PM           1674 Application_server.pem
-a----        10/23/2024  11:33 AM         200289 AWS Certification Series Invoice.pdf
-a----        10/22/2024  10:42 AM         135509 chfi-computer-hacking-forensic-investigator-ec-chfi.pdf
-a----        11/20/2024  11:14 PM        1271872 Computer Networks And Internet Protocol.pdf
-a----        11/20/2024  11:14 PM        2621136 Marklist.pdf
-a----        10/25/2024   7:38 PM         124717 Offer Letter.pdf
-a----        11/27/2024  11:32 PM     4960331438 Unconfirmed 390228.crdownload


PS C:\Users\bheem\Downloads> cd .\node-todo-cicd-master\
PS C:\Users\bheem\Downloads\node-todo-cicd-master> dir


    Directory: C:\Users\bheem\Downloads\node-todo-cicd-master


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        11/27/2024  11:30 PM                DevSecOps
d-----        11/27/2024  11:30 PM                k8s
d-----        11/27/2024  11:30 PM                kustomize
d-----        11/27/2024  11:30 PM                terraform
d-----        11/27/2024  11:30 PM                views
-a----        11/27/2024  11:29 PM             24 .gitignore
-a----        11/27/2024  11:29 PM           2614 app.js
-a----        11/27/2024  11:29 PM            108 docker-compose.yaml
-a----        11/27/2024  11:29 PM            208 Dockerfile
-a----        11/27/2024  11:29 PM           1152 Jenkinsfile
-a----        11/27/2024  11:29 PM         220311 package-lock.json
-a----        11/27/2024  11:29 PM            530 package.json
-a----        11/27/2024  11:29 PM            155 README.md
-a----        11/27/2024  11:29 PM            395 sonar-project.properties
-a----        11/27/2024  11:29 PM            888 test.js


PS C:\Users\bheem\Downloads\node-todo-cicd-master> git init
Initialized empty Git repository in C:/Users/bheem/Downloads/node-todo-cicd-master/.git/
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git remote -v
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git remote set-url origin https://github.com/BhimSingh-cloudEr/NodeJs-App.git
error: No such remote 'origin'
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git remote -v
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git remote set-url origin https://github.com/BhimSingh-cloudEr/NodeJs-App.git
error: No such remote 'origin'
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git remote add origin https://github.com/BhimSingh-cloudEr/NodeJs-App.git
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git remote set-url origin https://github.com/BhimSingh-cloudEr/NodeJs-App.git
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git remote -v
origin  https://github.com/BhimSingh-cloudEr/NodeJs-App.git (fetch)
origin  https://github.com/BhimSingh-cloudEr/NodeJs-App.git (push)
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git add .
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'DevSecOps/Jenkinsfile', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'DevSecOps/README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Dockerfile', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'app.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'docker-compose.yaml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'k8s/deployment.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'k8s/pod.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'k8s/replica-sets.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'k8s/service.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/base/app-1/app-1.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/base/app-1/kustomization.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/base/ingress/ingress.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/base/ingress/kustomization.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/overlays/dev/dev-ingress-patch.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/overlays/dev/kustomization.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/overlays/prd/kustomization.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/overlays/prd/prd-ingress-patch.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'package-lock.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'package.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'sonar-project.properties', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'terraform/main.tf', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'terraform/terraform.tf', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'test.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'views/edititem.ejs', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'views/todo.ejs', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git commit -m "Updates"
[master (root-commit) 3e21547] Updates
 29 files changed, 6623 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 DevSecOps/Jenkinsfile
 create mode 100644 DevSecOps/README.md
 create mode 100644 Dockerfile
 create mode 100644 Jenkinsfile
 create mode 100644 README.md
 create mode 100644 app.js
 create mode 100644 docker-compose.yaml
 create mode 100644 k8s/deployment.yml
 create mode 100644 k8s/pod.yml
 create mode 100644 k8s/replica-sets.yml
 create mode 100644 k8s/service.yml
 create mode 100644 kustomize/README.md
 create mode 100644 kustomize/base/app-1/app-1.yml
 create mode 100644 kustomize/base/app-1/kustomization.yml
 create mode 100644 kustomize/base/ingress/ingress.yml
 create mode 100644 kustomize/base/ingress/kustomization.yml
 create mode 100644 kustomize/overlays/dev/dev-ingress-patch.json
 create mode 100644 kustomize/overlays/dev/kustomization.yml
 create mode 100644 kustomize/overlays/prd/kustomization.yml
 create mode 100644 kustomize/overlays/prd/prd-ingress-patch.json
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 sonar-project.properties
 create mode 100644 terraform/main.tf
 create mode 100644 terraform/terraform.tf
 create mode 100644 test.js
 create mode 100644 views/edititem.ejs
 create mode 100644 views/todo.ejs
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/BhimSingh-cloudEr/NodeJs-App.git'
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git push --force origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/BhimSingh-cloudEr/NodeJs-App.git'
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git branch
* master
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git checkout
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git branch
* master
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git pull origin main --rebase
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 876 bytes | 109.00 KiB/s, done.
From https://github.com/BhimSingh-cloudEr/NodeJs-App
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
Auto-merging README.md
CONFLICT (add/add): Merge conflict in README.md
error: could not apply 3e21547... Updates
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
hint: Disable this message with "git config advice.mergeConflict false"
Could not apply 3e21547... Updates
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/BhimSingh-cloudEr/NodeJs-App.git'
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git rebase --continue
README.md: needs merge
You must edit all merge conflicts and then
mark them as resolved using git add
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/BhimSingh-cloudEr/NodeJs-App.git'
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git branch main
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git branch
* (no branch, rebasing master)
  main
  master
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git checkout main
README.md: needs merge
error: you need to resolve your current index first
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git branch
* (no branch, rebasing master)
  main
  master
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git push origin main --force
Everything up-to-date
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git remote -v
origin  https://github.com/BhimSingh-cloudEr/NodeJs-App.git (fetch)
origin  https://github.com/BhimSingh-cloudEr/NodeJs-App.git (push)
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git push origin main
Everything up-to-date
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git branch
* (no branch, rebasing master)
  main
  master
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git checkout main
README.md: needs merge
error: you need to resolve your current index first
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git status
interactive rebase in progress; onto 4d39d19
Last command done (1 command done):
   pick 3e21547 Updates
No commands remaining.
You are currently rebasing branch 'master' on '4d39d19'.
  (fix conflicts and then run "git rebase --continue")
  (use "git rebase --skip" to skip this patch)
  (use "git rebase --abort" to check out the original branch)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   DevSecOps/Jenkinsfile
        new file:   DevSecOps/README.md
        new file:   Dockerfile
        new file:   Jenkinsfile
        new file:   app.js
        new file:   docker-compose.yaml
        new file:   k8s/deployment.yml
        new file:   k8s/pod.yml
        new file:   k8s/replica-sets.yml
        new file:   k8s/service.yml
        new file:   kustomize/README.md
        new file:   kustomize/base/app-1/app-1.yml
        new file:   kustomize/base/app-1/kustomization.yml
        new file:   kustomize/base/ingress/ingress.yml
        new file:   kustomize/base/ingress/kustomization.yml
        new file:   kustomize/overlays/dev/dev-ingress-patch.json
        new file:   kustomize/overlays/dev/kustomization.yml
        new file:   kustomize/overlays/prd/kustomization.yml
        new file:   kustomize/overlays/prd/prd-ingress-patch.json
        new file:   package-lock.json
        new file:   package.json
        new file:   sonar-project.properties
        new file:   terraform/main.tf
        new file:   terraform/terraform.tf
        new file:   test.js
        new file:   views/edititem.ejs
        new file:   views/todo.ejs

Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add <file>..." to mark resolution)
        both added:      README.md

PS C:\Users\bheem\Downloads\node-todo-cicd-master> git restore --staged README.md
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git add README.md
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git commit -m "Resolved merge conflict in README.md"
[detached HEAD 84ca5fa] Resolved merge conflict in README.md
 29 files changed, 6626 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 DevSecOps/Jenkinsfile
 create mode 100644 DevSecOps/README.md
 create mode 100644 Dockerfile
 create mode 100644 Jenkinsfile
 create mode 100644 app.js
 create mode 100644 docker-compose.yaml
 create mode 100644 k8s/deployment.yml
 create mode 100644 k8s/pod.yml
 create mode 100644 k8s/replica-sets.yml
 create mode 100644 k8s/service.yml
 create mode 100644 kustomize/README.md
 create mode 100644 kustomize/base/app-1/app-1.yml
 create mode 100644 kustomize/base/app-1/kustomization.yml
 create mode 100644 kustomize/base/ingress/ingress.yml
 create mode 100644 kustomize/base/ingress/kustomization.yml
 create mode 100644 kustomize/overlays/dev/dev-ingress-patch.json
 create mode 100644 kustomize/overlays/dev/kustomization.yml
 create mode 100644 kustomize/overlays/prd/kustomization.yml
 create mode 100644 kustomize/overlays/prd/prd-ingress-patch.json
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 sonar-project.properties
 create mode 100644 terraform/main.tf
 create mode 100644 terraform/terraform.tf
 create mode 100644 test.js
 create mode 100644 views/edititem.ejs
 create mode 100644 views/todo.ejs
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git checkout main
Warning: you are leaving 1 commit behind, not connected to
any of your branches:

  84ca5fa Resolved merge conflict in README.md

If you want to keep it by creating a new branch, this may be a good time
to do so with:

 git branch <new-branch-name> 84ca5fa

Switched to branch 'main'
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git push origin main
Everything up-to-date
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git branch
* main
  master
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git add .
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git commit -m "Update"
On branch main
Last command done (1 command done):
   pick 3e21547 Updates
No commands remaining.
You are currently editing a commit while rebasing branch 'master' on '4d39d19'.
  (use "git commit --amend" to amend the current commit)
  (use "git rebase --continue" once you are satisfied with your changes)

nothing to commit, working tree clean
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git remote -v
origin  https://github.com/BhimSingh-cloudEr/NodeJs-App.git (fetch)
origin  https://github.com/BhimSingh-cloudEr/NodeJs-App.git (push)
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git rebase --continue
Successfully rebased and updated refs/heads/master.
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git branch
  main
* master
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git checkout main
Switched to branch 'main'
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git branch
* main
  master
PS C:\Users\bheem\Downloads\node-todo-cicd-master> dir


    Directory: C:\Users\bheem\Downloads\node-todo-cicd-master


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        11/27/2024  11:59 PM             26 README.md


PS C:\Users\bheem\Downloads\node-todo-cicd-master> git checkout master
Switched to branch 'master'
PS C:\Users\bheem\Downloads\node-todo-cicd-master> dir


    Directory: C:\Users\bheem\Downloads\node-todo-cicd-master


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        11/27/2024  11:59 PM             26 README.md


PS C:\Users\bheem\Downloads\node-todo-cicd-master> ls


    Directory: C:\Users\bheem\Downloads\node-todo-cicd-master


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        11/27/2024  11:59 PM             26 README.md


PS C:\Users\bheem\Downloads\node-todo-cicd-master> ls


    Directory: C:\Users\bheem\Downloads\node-todo-cicd-master


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        11/27/2024  11:59 PM             26 README.md


PS C:\Users\bheem\Downloads\node-todo-cicd-master> ls


    Directory: C:\Users\bheem\Downloads\node-todo-cicd-master


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        11/28/2024  12:04 AM                DevSecOps
d-----        11/28/2024  12:04 AM                k8s
d-----        11/28/2024  12:04 AM                kustomize
d-----        11/28/2024  12:04 AM                terraform
d-----        11/28/2024  12:04 AM                views
-a----        11/27/2024  11:29 PM             24 .gitignore
-a----        11/27/2024  11:29 PM           2614 app.js
-a----        11/27/2024  11:29 PM            108 docker-compose.yaml
-a----        11/27/2024  11:29 PM            208 Dockerfile
-a----        11/27/2024  11:29 PM           1152 Jenkinsfile
-a----        11/27/2024  11:29 PM         220311 package-lock.json
-a----        11/27/2024  11:29 PM            530 package.json
-a----        11/27/2024  11:29 PM            155 README.md
-a----        11/27/2024  11:29 PM            395 sonar-project.properties
-a----        11/27/2024  11:29 PM            888 test.js


PS C:\Users\bheem\Downloads\node-todo-cicd-master> git branch
  main
* master
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git checkout main
M       README.md
Switched to branch 'main'
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git branch
* main
  master
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'DevSecOps/Jenkinsfile', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'DevSecOps/README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Dockerfile', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'app.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'docker-compose.yaml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'k8s/deployment.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'k8s/pod.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'k8s/replica-sets.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'k8s/service.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/base/app-1/app-1.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/base/app-1/kustomization.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/base/ingress/ingress.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/base/ingress/kustomization.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/overlays/dev/dev-ingress-patch.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/overlays/dev/kustomization.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/overlays/prd/kustomization.yml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'kustomize/overlays/prd/prd-ingress-patch.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'package-lock.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'package.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'sonar-project.properties', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'terraform/main.tf', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'terraform/terraform.tf', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'test.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'views/edititem.ejs', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'views/todo.ejs', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git commit -m "Updates"
[main c26f427] Updates
 29 files changed, 6623 insertions(+), 2 deletions(-)
 create mode 100644 .gitignore
 create mode 100644 DevSecOps/Jenkinsfile
 create mode 100644 DevSecOps/README.md
 create mode 100644 Dockerfile
 create mode 100644 Jenkinsfile
 create mode 100644 app.js
 create mode 100644 docker-compose.yaml
 create mode 100644 k8s/deployment.yml
 create mode 100644 k8s/pod.yml
 create mode 100644 k8s/replica-sets.yml
 create mode 100644 k8s/service.yml
 create mode 100644 kustomize/README.md
 create mode 100644 kustomize/base/app-1/app-1.yml
 create mode 100644 kustomize/base/app-1/kustomization.yml
 create mode 100644 kustomize/base/ingress/ingress.yml
 create mode 100644 kustomize/base/ingress/kustomization.yml
 create mode 100644 kustomize/overlays/dev/dev-ingress-patch.json
 create mode 100644 kustomize/overlays/dev/kustomization.yml
 create mode 100644 kustomize/overlays/prd/kustomization.yml
 create mode 100644 kustomize/overlays/prd/prd-ingress-patch.json
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 sonar-project.properties
 create mode 100644 terraform/main.tf
 create mode 100644 terraform/terraform.tf
 create mode 100644 test.js
 create mode 100644 views/edititem.ejs
 create mode 100644 views/todo.ejs
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git push origin main
Enumerating objects: 44, done.
Counting objects: 100% (44/44), done.
Delta compression using up to 4 threads
Compressing objects: 100% (41/41), done.
Writing objects: 100% (42/42), 71.85 KiB | 5.99 MiB/s, done.
Total 42 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/BhimSingh-cloudEr/NodeJs-App.git
   4d39d19..c26f427  main -> main
PS C:\Users\bheem\Downloads\node-todo-cicd-master> history

  Id CommandLine
  -- -----------
   1 cd ../..
   2 cd .\Users\
   3 cd .\bheem\
   4 cd .\Downloads\
   5 ls
   6 cd .\node-todo-cicd-master\
   7 dir
   8 git init
   9 git remote -v
  10 git remote set-url origin https://github.com/BhimSingh-cloudEr/NodeJs-App.git
  11 git remote -v
  12 git remote set-url origin https://github.com/BhimSingh-cloudEr/NodeJs-App.git
  13 git remote add origin https://github.com/BhimSingh-cloudEr/NodeJs-App.git
  14 git remote set-url origin https://github.com/BhimSingh-cloudEr/NodeJs-App.git
  15 git remote -v
  16 git add .
  17 git commit -m "Updates"
  18 git push -u origin main
  19 git push --force origin main
  20 git branch
  21 git checkout
  22 git branch
  23 git pull origin main --rebase
  24 git push -u origin main
  25 git rebase --continue
  26 git push origin main
  27 git branch main
  28 git branch
  29 git checkout main
  30 git branch
  31 git push origin main --force
  32 git remote -v
  33 git push origin main
  34 git branch
  35 git checkout main
  36 git status
  37 git restore --staged README.md
  38 git add README.md
  39 git commit -m "Resolved merge conflict in README.md"
  40 git checkout main
  41 git push origin main
  42 git branch
  43 git add .
  44 git commit -m "Update"
  45 git remote -v
  46 git rebase --continue
  47 git branch
  48 git checkout main
  49 git branch
  50 dir
  51 git checkout master
  52 dir
  53 ls
  54 ls
  55 ls
  56 git branch
  57 git checkout main
  58 git branch
  59 git add .
  60 git commit -m "Updates"
  61 git push origin main


PS C:\Users\bheem\Downloads\node-todo-cicd-master> git branch
* main
  master
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git commit -m "Updates"
[main fe6aecc] Updates
 1 file changed, 71 insertions(+)
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 851 bytes | 851.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/BhimSingh-cloudEr/NodeJs-App.git
   c26f427..fe6aecc  main -> main
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git commit -m "Updates"
[main 621f063] Updates
 1 file changed, 60 insertions(+), 62 deletions(-)
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 851 bytes | 851.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/BhimSingh-cloudEr/NodeJs-App.git
   fe6aecc..621f063  main -> main
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git commit -m "Updates"
[main 7cccee8] Updates
 1 file changed, 59 insertions(+), 59 deletions(-)
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 689 bytes | 689.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/BhimSingh-cloudEr/NodeJs-App.git
   621f063..7cccee8  main -> main
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git commit -m "Updates"
[main 516b704] Updates
 1 file changed, 58 insertions(+)
PS C:\Users\bheem\Downloads\node-todo-cicd-master> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 681 bytes | 681.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/BhimSingh-cloudEr/NodeJs-App.git
   7cccee8..516b704  main -> main
PS C:\Users\bheem\Downloads\node-todo-cicd-master>
