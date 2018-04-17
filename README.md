# .git-enhancement
Make a better git for daily development. 

## Requirements
  * vim

## Get Start with Linux
  * `brew install git && brew install bash-completion`
  * `git clone https://github.com/Elvisz/.git-enhancement.git ~/.git-enhancement && cd ~/.git-enhancement`
  * `git submodule update --init`
  * `rm ~/.gitconfig`
  * `ln -s ~/.git-enhancement/.gitconfig ~/.gitconfig`
  * `echo if [ -f $(brew --prefix)/etc/bash_completion ]; then . $(brew --prefix)/etc/bash_completion fi`
  * `echo "source ~/.git-enhancement/.git_profile" >> .bash_profile`
