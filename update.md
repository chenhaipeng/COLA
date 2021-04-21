
# 如何更新远程仓库
origin  git@github.com:ibrother/staticblog.github.io.git (fetch)
origin  git@github.com:ibrother/staticblog.github.io.git (push)

git remote add upstream https://github.com/staticblog/staticblog.github.io.git
origin  git@github.com:ibrother/staticblog.github.io.git (fetch)
origin  git@github.com:ibrother/staticblog.github.io.git (push)
upstream        https://github.com/staticblog/staticblog.github.io.git (fetch)
upstream        https://github.com/staticblog/staticblog.github.io.git (push)

git fetch upstream
git checkout master
git merge upstream/master

git push origin master