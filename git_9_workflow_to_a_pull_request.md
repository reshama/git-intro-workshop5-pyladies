# Workflow to a Pull Request

### Step 1:  fork the repo
https://github.com/WiMLDS/python_advanced

### Step 2:  clone the repo
syntax:  
`git clone <url>`  
>example:  
`git clone https://github.com/reshamas/python_advanced.git`


### Step 3:  add an `upstream` remote
syntax:  
`git remote add upstream <original url>`  
>example:  
`git remote add upstream https://github.com/WiMLDS/python_advanced.git`

### Step 3:  create a working branch
syntax:  
`git branch <new_branch_name>`    
>example:  
`git branch reshama_wip`

### Step 4:  switch to working branch
syntax:  
`git checkout <branch_name>`
>example:  
`git checkout reshama_wip`

### Step 5:  create a file
- create a folder with your name here:  `/Users/reshamashaikh/git_work/python_advanced/submissions`
- `cd` into this folder, create a folder with your name
    >example:  `/reshama/`
- create a Python file with your name
    >example:  `reshama.py`

### Step 6:  start tracking the file
syntax:  
`git add <file_name>`
>example:  
`git add reshama.py`

### Step 7:  log the change 
syntax:  
`git commit -m 'message`
>example:  
`git commit -m 'adding my python name file'`

### Step 8:  finalize the change:  `push` changes to your 'working branch'
syntax:  
`git push <remote_name> <branch_name>`  
>example:  
`git push origin reshama_wip`

### Step 9:  On GitHub, submit a pull request (green button)
