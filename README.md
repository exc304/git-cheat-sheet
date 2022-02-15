# git-cheat-sheet
A cheat sheet for Git workflows.

`git` is a version control system that lets you manage and keep track of your source code history and is responsible for everything GitHub related that happens locally on your computer. GitHub is a cloud-based hosting service that lets you manage Git repositories.

### A cheat sheet for Git workflows
![Git Cheat Sheet](https://cdn.filestackcontent.com/nXssKoRBQQOxnVIfrEfX)

### Local Setup
Configures user information used across all local repos

| Command | What it does |
| --- | --- |
| git config --global user.name `firstname lastname` | sets a name to be associated |
| git config --global user.email `valid-email` | sets an email address to be associated |
| git config --global color.ui | autosets automatic command line color |
| git config --global init.defaultBranch `<name>` | sets local initial branch name to use in all new repos |

### Repo Setup & Init
Configuring user information, initializing and cloning repos

| Command | What it does |
| --- | --- |
| git init | initializes an existing directory as a git repo |
| git clone `url` | retrieves an entire repo from a url |
| git clone `url; cd <local_folder_name>` | retrieves an entire repo from a url then creates and saves it to a specified local location |


### 🍬 This next section assumes the remote repository is represented by a remote or Git server 🍬

### Pushing and Pulling
| Command | What it does |
| --- | --- |
| git clone `url` | retrieves an entire repo from a url |
| git clone `url; cd<local_folder_name>` | retrieves an entire repo from a url then clones it to a specified local folder |
| git remote add `origin<link>` | to add a link |
| git push | to push to master |
| git push -u origin master | to push to origin |

### Branching and Merging
| Command | What it does |
| --- | --- |
| git checkout `-b branchname` | to create a new branch |
| git status | to see everything that's been modified |
| git merge origin/master | to merge master into your new branch |
| git branch | to list branches |
| git branch -a | to list all the branches (might be the same as 👆) |

### Adding and Removing Files
| Command | What it does |
| --- | --- |
| git add `<filename>` | to add a file |
| git add `<1st filename> <2nd filename> <3rd filename>` | to add multiple files |
| git add -all or * or -A | to add all updated files |
| git rm -r `<filename>` | to remove a file |
  
### Committing Changes
| Command | What it does |
| --- | --- |
| git commit -m _"body of commit message"_ | to pass a message with your commit |
| git commit --amend -m _"amend reason message"_ | to amend the last commit or the last message |


#### 🙇‍♀️ Pro tip: If you're using Mac OS, to show hidden files in a directory use `cmd + shift + .` 


Made by Erin Hess, this work is licensed under the Creative Commons Attribution 4.0 License.
