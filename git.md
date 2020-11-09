# Git

## Every day
git push
git pull
git checkout <branch_name>
git checkout -b <new_branch_name>
git merge <remote_branch>

## Tidying up & removing mistakes

Delete local branch: `git branch -d <branch_name>` (not active branch)
Delete remote branch: ``
Undo last local commit: `` (e.g. accidentally committed passwords)


## Tagging
git checkout master
git pull
git pull --tags
git tag -l
git tag -a -m "Release notes for release 1.0.0" "1.0.0"
git push --tags
git checkout refs/tags/<tag_name>