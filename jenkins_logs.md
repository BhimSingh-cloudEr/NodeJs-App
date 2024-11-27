# Jenkins build process logs_001

Started by user Bhim Singh
Running as SYSTEM
Building in workspace /var/lib/jenkins/workspace/Nodejs-Todo-App
The recommended git tool is: NONE
using credential Github-Jenkins
 > git rev-parse --resolve-git-dir /var/lib/jenkins/workspace/Nodejs-Todo-App/.git # timeout=10
Fetching changes from the remote Git repository
 > git config remote.origin.url https://github.com/BhimSingh-cloudEr/NodeJs-App.git # timeout=10
Fetching upstream changes from https://github.com/BhimSingh-cloudEr/NodeJs-App.git
 > git --version # timeout=10
 > git --version # 'git version 2.43.0'
using GIT_SSH to set credentials This is for Github and Jenkins integration.
Verifying host key using known hosts file
You're using 'Known hosts file' strategy to verify ssh host keys, but your known_hosts file does not exist, please go to 'Manage Jenkins' -> 'Security' -> 'Git Host Key Verification Configuration' and configure host key verification.
 > git fetch --tags --force --progress -- https://github.com/BhimSingh-cloudEr/NodeJs-App.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git rev-parse refs/remotes/origin/main^{commit} # timeout=10
Checking out Revision 96497909f8e16b7c12bcadd68972243a32cb5260 (refs/remotes/origin/main)
 > git config core.sparsecheckout # timeout=10
 > git checkout -f 96497909f8e16b7c12bcadd68972243a32cb5260 # timeout=10
Commit message: "Update todo.ejs"
 > git rev-list --no-walk 96497909f8e16b7c12bcadd68972243a32cb5260 # timeout=10
[Nodejs-Todo-App] $ /bin/sh -xe /tmp/jenkins15181275510076903417.sh
+ docker build . -t node-todo-app
DEPRECATED: The legacy builder is deprecated and will be removed in a future release.
            Install the buildx component to build images with BuildKit:
            https://docs.docker.com/go/buildx/

Sending build context to Docker daemon  25.37MB

Step 1/7 : FROM node:12.2.0-alpine
 ---> f391dabf9dce
Step 2/7 : WORKDIR /node
 ---> Using cache
 ---> d9ff7977ae2f
Step 3/7 : COPY . .
 ---> Using cache
 ---> 8245848fd0e3
Step 4/7 : RUN npm install
 ---> Using cache
 ---> d4ade2989113
Step 5/7 : RUN npm run test
 ---> Using cache
 ---> ef645aafaaf1
Step 6/7 : EXPOSE 8000
 ---> Using cache
 ---> f58a1c066661
Step 7/7 : CMD ["node","app.js"]
 ---> Using cache
 ---> 65ed310bc42d
Successfully built 65ed310bc42d
Successfully tagged node-todo-app:latest
+ docker run -d --name web-node-001 -p 8000:8000 node-todo-app
docker: Error response from daemon: Conflict. The container name "/web-node-001" is already in use by container "1e150f7a48383c87cc559b79b12610bd4a44ef81fcaf072285b2bcb2e0d3c265". You have to remove (or rename) that container to be able to reuse that name.
See 'docker run --help'.
Build step 'Execute shell' marked build as failure
Finished: FAILURE


# Jenkins build process logs_002

Started by user Bhim Singh
Running as SYSTEM
Building in workspace /var/lib/jenkins/workspace/Nodejs-Todo-App
The recommended git tool is: NONE
using credential Github-Jenkins
 > git rev-parse --resolve-git-dir /var/lib/jenkins/workspace/Nodejs-Todo-App/.git # timeout=10
Fetching changes from the remote Git repository
 > git config remote.origin.url https://github.com/BhimSingh-cloudEr/NodeJs-App.git # timeout=10
Fetching upstream changes from https://github.com/BhimSingh-cloudEr/NodeJs-App.git
 > git --version # timeout=10
 > git --version # 'git version 2.43.0'
using GIT_SSH to set credentials This is for Github and Jenkins integration.
Verifying host key using known hosts file
You're using 'Known hosts file' strategy to verify ssh host keys, but your known_hosts file does not exist, please go to 'Manage Jenkins' -> 'Security' -> 'Git Host Key Verification Configuration' and configure host key verification.
 > git fetch --tags --force --progress -- https://github.com/BhimSingh-cloudEr/NodeJs-App.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git rev-parse refs/remotes/origin/main^{commit} # timeout=10
Checking out Revision 96497909f8e16b7c12bcadd68972243a32cb5260 (refs/remotes/origin/main)
 > git config core.sparsecheckout # timeout=10
 > git checkout -f 96497909f8e16b7c12bcadd68972243a32cb5260 # timeout=10
Commit message: "Update todo.ejs"
 > git rev-list --no-walk 96497909f8e16b7c12bcadd68972243a32cb5260 # timeout=10
[Nodejs-Todo-App] $ /bin/sh -xe /tmp/jenkins8733336002402236990.sh
+ docker build . -t node-todo-app
DEPRECATED: The legacy builder is deprecated and will be removed in a future release.
            Install the buildx component to build images with BuildKit:
            https://docs.docker.com/go/buildx/

Sending build context to Docker daemon  25.37MB

Step 1/7 : FROM node:12.2.0-alpine
 ---> f391dabf9dce
Step 2/7 : WORKDIR /node
 ---> Using cache
 ---> d9ff7977ae2f
Step 3/7 : COPY . .
 ---> Using cache
 ---> 8245848fd0e3
Step 4/7 : RUN npm install
 ---> Using cache
 ---> d4ade2989113
Step 5/7 : RUN npm run test
 ---> Using cache
 ---> ef645aafaaf1
Step 6/7 : EXPOSE 8000
 ---> Using cache
 ---> f58a1c066661
Step 7/7 : CMD ["node","app.js"]
 ---> Using cache
 ---> 65ed310bc42d
Successfully built 65ed310bc42d
Successfully tagged node-todo-app:latest
+ docker run -d --name js-node-001 -p 8000:8000 node-todo-app
856ea656a689a8be2735fd496f4cdaa9ea5bd50f3ab30e4e4dc38f27434a323a
Finished: SUCCESS

# Jenkins process build logs_003

Started by user Bhim Singh
Running as SYSTEM
Building in workspace /var/lib/jenkins/workspace/Nodejs-Todo-App
The recommended git tool is: NONE
using credential Github-Jenkins
 > git rev-parse --resolve-git-dir /var/lib/jenkins/workspace/Nodejs-Todo-App/.git # timeout=10
Fetching changes from the remote Git repository
 > git config remote.origin.url https://github.com/BhimSingh-cloudEr/NodeJs-App.git # timeout=10
Fetching upstream changes from https://github.com/BhimSingh-cloudEr/NodeJs-App.git
 > git --version # timeout=10
 > git --version # 'git version 2.43.0'
using GIT_SSH to set credentials This is for Github and Jenkins integration.
Verifying host key using known hosts file
You're using 'Known hosts file' strategy to verify ssh host keys, but your known_hosts file does not exist, please go to 'Manage Jenkins' -> 'Security' -> 'Git Host Key Verification Configuration' and configure host key verification.
 > git fetch --tags --force --progress -- https://github.com/BhimSingh-cloudEr/NodeJs-App.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git rev-parse refs/remotes/origin/main^{commit} # timeout=10
Checking out Revision 89fe5dd2669e58f66d68b640dc7fec3b968f9a10 (refs/remotes/origin/main)
 > git config core.sparsecheckout # timeout=10
 > git checkout -f 89fe5dd2669e58f66d68b640dc7fec3b968f9a10 # timeout=10
Commit message: "Updates"
 > git rev-list --no-walk 89fe5dd2669e58f66d68b640dc7fec3b968f9a10 # timeout=10
[Nodejs-Todo-App] $ /bin/sh -xe /tmp/jenkins1407831947290765167.sh
+ docker build . -t node-todo-app
DEPRECATED: The legacy builder is deprecated and will be removed in a future release.
            Install the buildx component to build images with BuildKit:
            https://docs.docker.com/go/buildx/

Sending build context to Docker daemon  25.37MB

Step 1/7 : FROM node:12.2.0-alpine
 ---> f391dabf9dce
Step 2/7 : WORKDIR /node
 ---> Using cache
 ---> d9ff7977ae2f
Step 3/7 : COPY . .
 ---> Using cache
 ---> 7c8927d525da
Step 4/7 : RUN npm install
 ---> Using cache
 ---> 911eadefe781
Step 5/7 : RUN npm run test
 ---> Using cache
 ---> 86facf806ef6
Step 6/7 : EXPOSE 8000
 ---> Using cache
 ---> ce25afb64260
Step 7/7 : CMD ["node","app.js"]
 ---> Using cache
 ---> 3b2c0e98540b
Successfully built 3b2c0e98540b
Successfully tagged node-todo-app:latest
+ docker run -d --name todo_001 -p 8000:8000 node-todo-app
ce7fe6a30ff9dbd2eff86441f9c766f648d44510466c113b727ba1d97eb01ae2
Finished: SUCCESS


# Jenkins process build logs_004

Started by user Bhim Singh
Running as SYSTEM
Building in workspace /var/lib/jenkins/workspace/Nodejs-Todo-App
The recommended git tool is: NONE
using credential Github-Jenkins
 > git rev-parse --resolve-git-dir /var/lib/jenkins/workspace/Nodejs-Todo-App/.git # timeout=10
Fetching changes from the remote Git repository
 > git config remote.origin.url https://github.com/BhimSingh-cloudEr/NodeJs-App.git # timeout=10
Fetching upstream changes from https://github.com/BhimSingh-cloudEr/NodeJs-App.git
 > git --version # timeout=10
 > git --version # 'git version 2.43.0'
using GIT_SSH to set credentials This is for Github and Jenkins integration.
Verifying host key using known hosts file
You're using 'Known hosts file' strategy to verify ssh host keys, but your known_hosts file does not exist, please go to 'Manage Jenkins' -> 'Security' -> 'Git Host Key Verification Configuration' and configure host key verification.
 > git fetch --tags --force --progress -- https://github.com/BhimSingh-cloudEr/NodeJs-App.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git rev-parse refs/remotes/origin/main^{commit} # timeout=10
Checking out Revision 89fe5dd2669e58f66d68b640dc7fec3b968f9a10 (refs/remotes/origin/main)
 > git config core.sparsecheckout # timeout=10
 > git checkout -f 89fe5dd2669e58f66d68b640dc7fec3b968f9a10 # timeout=10
Commit message: "Updates"
 > git rev-list --no-walk 89fe5dd2669e58f66d68b640dc7fec3b968f9a10 # timeout=10
[Nodejs-Todo-App] $ /bin/sh -xe /tmp/jenkins13412611208865465476.sh
+ docker build . -t node-todo-app
DEPRECATED: The legacy builder is deprecated and will be removed in a future release.
            Install the buildx component to build images with BuildKit:
            https://docs.docker.com/go/buildx/

Sending build context to Docker daemon  25.37MB

Step 1/7 : FROM node:12.2.0-alpine
 ---> f391dabf9dce
Step 2/7 : WORKDIR /node
 ---> Using cache
 ---> d9ff7977ae2f
Step 3/7 : COPY . .
 ---> Using cache
 ---> 7c8927d525da
Step 4/7 : RUN npm install
 ---> Using cache
 ---> 911eadefe781
Step 5/7 : RUN npm run test
 ---> Using cache
 ---> 86facf806ef6
Step 6/7 : EXPOSE 8000
 ---> Using cache
 ---> ce25afb64260
Step 7/7 : CMD ["node","app.js"]
 ---> Using cache
 ---> 3b2c0e98540b
Successfully built 3b2c0e98540b
Successfully tagged node-todo-app:latest
+ docker run -d --name app_001 -p 9000:9000 node-todo-app
27bbe9ffd8480872d895deda430c9a049e37353b6ba05521f7da8a6f98423af2
Finished: SUCCESS