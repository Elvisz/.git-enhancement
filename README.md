# .git-enhancement
Make a better git for daily development. 

## Requirements
  * vim

## Get Start with macOS
  * `brew install git && brew install bash-completion`
  * `git clone https://github.com/bobthecow/git-flow-completion.git ~/git-flow-completion.git`
  * `git clone https://github.com/Elvisz/.git-enhancement.git ~/.git-enhancement && cd ~/.git-enhancement`
  * `touch .bash_profile`
  * `echo "source ~/git-flow-completion/git-flow-completion.bash" >> .bash_profile`
  * `rm ~/.gitconfig && ln -s ~/.git-enhancement/.gitconfig ~/.gitconfig`
  * `echo "source ~/.git-enhancement/.alias" >> ~/.bash_profile`
