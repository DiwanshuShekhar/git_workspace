# learn_git
#use git prompt and enable git auto completion
1. move the files git-completion.bash and git-prompt.sh to the home directory
2. copy the contents of bash_profile to .bash_profile in the home directory
3. Restart the terminal
#configure git to use a default text editor for commit message
git config --global core.editor "vim"
git config --global push.default matching
git config --global merge.conflictstyle diff3
