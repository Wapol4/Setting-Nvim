```
Resource = https://github.com/Yash-Handa/logo-ls/releases/tag/v1.3.7
uname -m
select x86_64

pwd
/home/airist4
mv logo-ls .
tar -xzf tar-file
cp logo-ls /usr/local/bin/

logo-ls -a

# add aliases in bashrc
alias ils='logo-ls'
alias ila='logo-ls -A'
alias ill='logo-ls -al'

alias ilsg='logo-ls -D'
alias ilag='logo-ls -AD'
alias illg='logo-ls -alD'

shopt -s expand_aliases
source ~/.bashrc

```