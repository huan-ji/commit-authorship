# commit-authorship
git commit authorship change code

git filter-branch -f --env-filter "GIT_AUTHOR_NAME='Huan Ji'; GIT_AUTHOR_EMAIL='kkiiji@gmail.com'; GIT_COMMITTER_NAME='Huan Ji'; GIT_COMMITTER_EMAIL='kkiiji@gmail.com';" HEAD
