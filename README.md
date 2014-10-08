github-sandbox
==============

sandbox for me to test the github features, and also to record some
notice in there.

## background
#### 1. git
* http://git.or.cz/course/svn.html
* https://www.atlassian.com/git/tutorials/setting-up-a-repository
* http://gitready.com/

#### 2. github
* https://pages.github.com/


#### 3. github.io
* https://pages.github.com/

-----------
## github

#### 1. setup ssh key
* click "Edit profile"
* click "SSH keys" (https://github.com/settings/ssh)
* click "Add SSH Key"

#### 2. create repository
* in "Repositories tab", click "New"
* enter name and description
* select gitignore and license - [information about  open source license ](http://choosealicense.com/)
    <i>suggests  MIT license<i>

------
## git

#### 1. git - init

create ssh key

     ssh-keygen -t rsa -C "xxxx@gmail.com

setup git parameters

     git config --global user.name "xxxx"
     git config --global user.email "xxxx@gmail.com"

### 2. git - clone

     git clone git@github.com:xxx/xxxx.git



### 3. git - add/edit file(s)

    git add --all
    git commit -m "test 1"

    git rm XXX

### 4. git - push  

    git push

-> _this file is edited by [atom - hackable text editor](https://atom.io)_  <-
