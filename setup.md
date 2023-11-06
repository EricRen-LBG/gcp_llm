# Setup 

## For using GitHub repository: EricRen-LBG
1. Create ssh keys for using github   
$ `ssh-keygen -t ed25519 -C "Eric.Ren@lloydsbanking.dev"`

2. Start the ssh agent and add the newly generated key   
$ `eval "$(ssh-agent -s)"`   
$ `ssh-add ~/.ssh/id_ed25519`   


3. Upload the ssh public key to github
Github: Settings --> SSH and GPg keys --> New SSH key

## For using git
$ `git config --global user.name "Eric Ren user.email Eric.Ren@lloydsbanking.dev core.editor vi`   
$ `git config --global alias.lol "log --graph --decorate --pretty=oneline --abbrev-commit --all"`   

To check all setting:   
$ `git config --list`

## For gcp?
