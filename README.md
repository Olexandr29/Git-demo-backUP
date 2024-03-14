git remote is a very useful option because
if you lose your git remote repo (origin, not local) 
for example repo from GitHub or GitLab, or Bitbucket
You can create a repo on any storage platform as GitHub or GitLab, or Bitbucket
and copy all data (push) from your local repo to
new repo on remote 
in this case all my local commits will be move to 
the remote repo
for it I use next command

git remote add origin (and sha-1 from new repo)
for example
git remote add origin git@github.com:Olexandr29/Git-demo-backUP.git