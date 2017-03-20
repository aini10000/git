#git diff --cached/git diff --staged 已经暂存起来的文件和上次提交时的快照之间的差异
#git commit -a -m 'update' 就会自动把所有已经跟踪过的文件暂存起来一并提交，从而跳过 git add 步骤：
#git rm -f 1.txt 手动删除之后再用git rm -f
#git rm --cached readme.txt