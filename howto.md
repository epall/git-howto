Find a command
--------------

git howto SEARCH-TERMS

Add a definition to git-howto
-----------------------------

git howto add "DESCRIPTION" "GIT-COMMAND"

Delete a remote branch
----------------------

git push REMOTE :BRANCH

Discard the most recent commit
------------------------------

git reset --hard HEAD^

Push to a remote branch
-----------------------

git push REMOTE LOCAL-BRANCH:REMOTE-BRANCH

edit commit message
-------------------

git commit --amend

Fix / change git author email and name
--------------------------------------

git filter-branch -f --env-filter "GIT_AUTHOR_NAME='NAME'; GIT_AUTHOR_EMAIL='EMAIL';" START_COMMIT_..END_COMMIT

Create a new named branch and check it out
------------------------------------------

git checkout -b BRANCH_NAME
