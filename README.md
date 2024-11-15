# gitlab_test

## Environment

virtualbox

vs code -> terminal

(bash)

    gcc -v

    sudo apt-get install build-essential gdb

vs code -> Run C/C++ file -> g++ build and debug active file

## Push

(bash)

    git init

    git add .

    git config --global user.email "your email"

    git config --global user.name "your account name"

    git commit -m "first commit"

    git remote add origin http://gitlab.com/snoopycheng/gitlab_test.git

    git branch -M main

    (go to gitlab website setting -> repository -> protected branches -> unprotected)

    git push -uf origin main

## Push new

(bash)

    git status

    git add newfile

    git status

    git commit -m "add README"

    git push origin main

## Reference

https://code.visualstudio.com/docs/cpp/config-linux

https://docs.gitlab.com/ee/topics/git/commit.html

https://github.com/easy-ebpf