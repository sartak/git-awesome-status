You've been using git for years, you really don't need `git status` to tell you things like:

<pre>
(use "git reset HEAD <file>..." to unstage)
(use "git add <file>..." to update what will be committed)
(use "git checkout -- <file>..." to discard changes in working directory)
(use "git add <file>..." to include in what will be committed)
</pre>

So use this instead which gives you diffstats and local tracking branch information.

<pre>
Untracked files:
 README.md

Working tree:
 git-awesome-status |   30 <span color="#009900">+++++++++++++++++++++++++++++</span><span color="#990000">-</span>
 1 files changed, 29 insertions(+), 1 deletions(-)

Index:
 git-awesome-status |    5 <span color="#009900">+++++</span>
 1 files changed, 5 insertions(+), 0 deletions(-)

Local branches:
 master: <span color="#009900">+1</span>
</pre>
