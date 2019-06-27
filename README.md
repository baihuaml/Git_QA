# Git_QA
Git新手使用的常见问题汇总

# 1 在进行commit以后，发现忘记添加gitignore文件或者想要修改以后，再重新进行提交，这时候怎么办？

git rm -r --cached .  
git add.
git commit -m "****"
