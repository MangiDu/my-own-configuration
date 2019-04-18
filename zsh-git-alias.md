# git log alias
alias glc="git log --graph --pretty=format:'%C(auto)%d%C(reset) %C(#ffd700)%h%C(reset) (%C(#87ceff)%an%C(reset): %ar) - %C(#dddddd)%s%C(reset)%n'"
# git checkout alias
alias gco="git checkout"
# 删除已经合并到 master 的分支(git delete merged)
alias gdm="git branch --merged master | grep -v '^\*\|  master' | xargs -n 1 git branch -d"
