.install
.git --version
.mkdir sri
.cd sri
.git init
.git status
.echo>test.txt
.echo "my">test.txt
.git status
.git add test.txt
.git commit -m ""

.git checkout -b feature
."changes in above test.txt"
.git checkout new
git checkout master
.git merge sathwik
..git branch -m old new
.git branch -d branch

.cd dir
git init
touch Readme.md
git add Readme.md
nano README.md
git commit -am ""
repeat git commit -am ""
git status
git push
git log
git log --oneline
git log --oneline --graph
git log --oneline --author="name"
git log --author="n" --before/after="yyyy-mm-dd"
.git stash
git stash pop
.git checkout hash
.git switch master
git checkout -b newbranch
changes
git commit -am ""
git checkout master
some changes & commit
.git merge newbranch
conflict commit
.other change commit
copy hash
.git checkout master
git cheery-pick id

git clone url
git clone -b branch url

git checkout local
git rebase origin
git push origin local --force


mkdir TagDemo
cd TagDemo
git init
echo>test.txt
git add test.txt
git commit -m""
git tag V1.0.0
git tag
git show V2.0.0
git diff V1.0.0 V3.0.0
git checkout ""

git branch
git log --oneline
git show commit_id
git log -n 1 commit_id

git log --author="john" --since="" --until=""

git log -n 5
git log -n 5 --oneline

git rewrt abc123
git rewrt abc123...def456

git log -n 5
git log -n 5 --oneline

git revert abc123
git revert abc123...def456

