## Getting Started 🤗

- Fork this repo (button on top)
- Clone on your local machine

```
git clone https://github.com/Red-0111/cyber-bully-detector

```
- Navigate to project directory.
```
cd cyber-bully-detector
```

- Create a new branch

```markdown
git checkout -b my-new-branch
```
- Add your contribution
```
git add .
```
- Commit your changes.

```markdown
git commit -m "Relevant message"

```
- Then push 
```
git push origin my-new-branch
```
- Create a new pull request from your forked repository


## Avoid Conflicts (Syncing your fork)

An easy way to avoid conflicts is to add an 'upstream' for your git repo, as other PR's may be merged while you're working on your branch/fork.   

```terminal
git remote add upstream https://github.com/Red-0111/cyber-bully-detector
```

You can verify that the new remote has been added by typing
```terminal
git remote -v
```

To pull any new changes from your parent repo simply run
```terminal
git merge upstream/master
```

This will give you any eventual conflicts and allow you to easily solve them in your repo. It's a good idea to use it frequently in between your own commits to make sure that your repo is up to date with its parent.

For more information on syncing forks [read this article from Github](https://help.github.com/articles/syncing-a-fork/).
