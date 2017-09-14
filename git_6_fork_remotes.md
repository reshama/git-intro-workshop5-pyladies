# Forks & Remotes

---
## Forking a Repo
### Go to repo on GitHub
In my personal account on GitHub, go to repo to be cloned.

In this example, it is: https://github.com/WiMLDS/python_advanced

### Fork repo
Upper right of github page:  "Fork" the repo

Go to my forked repo: https://github.com/reshamas/python_advanced.git

 
### Clone repo
Clone that forked repo (which is now under my name)

In right column, find the link to **HTTPS clone URL** and **copy** that URL to be cloned.  
(Windows users may need to use ssh url.)  

### Go to working directory on local computer
```bash
▶ pwd
/Users/reshamashaikh

~  master ✗                                                                           ◒  
▶ mkdir git_work

~  master ✗                                                                           ◒  
▶ cd git_work

~/git_work  master ✗                                                                  ◒  
▶ pwd
/Users/reshamashaikh/git_work

~/git_work  master ✗                                                                  ◒  
▶ 
```

In terminal: 
* `cd` in to directory where repo will be cloned
 - Example:  `cd /Users/reshamashaikh/git_work`
* clone repo:   `git clone <url goes here>`
 - Example:  `https://github.com/reshamas/python_advanced.git`
* `cd` into cloned repo
 - Example:  `cd python_advanced`



#### Check out the repo
```bash
ls
```

---
## Adding a Remote
Remotes are copies of a repo on another computer **(or on a service like Github)**  

Example:  
* `upstream` [organization repo]
* `origin`   [your forked repo]


#### List remotes
```bash
▶ git remote -v
origin	https://github.com/reshamas/data-science-from-scratch.git (fetch)
origin	https://github.com/reshamas/data-science-from-scratch.git (push)

~/git_work/data-science-from-scratch  master ✔                                     498d  
▶ 
```
### Add a Remote
```bash
git remote add upstream https://github.com/WiMLDS/python_advanced.git
```

#### List remotes
```bash
git remote -v
```





