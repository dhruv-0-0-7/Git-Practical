# Git Practicals

### (1) Pull and Merge Difference

- Pull Request: 

Pull Request or (Merge Request) is a feature provided by Git Hosting platform such as (Github, Gitlab, etc...) to Merge changes on Remote Repository. PR is generated basically so that any higher authority or owner of Repository or even we can verify the changes before we confirm the merge.

- Pulling a Branch from Remote Repository:

In order to keep our Local Repository in-sync with Remote Repository we perform Pulling operation using `git pull` command in Git, to pull changes from Remote Repository into the Local Repository. `git pull` is a Network Operation and It will **fetch** hashes of changes and **merge** them with the equivalent branch.

- Merging Branches:

Merging is as the name suggests, an operation performed to merge/combine changes of two branches. we use `git merge` command to perform this operation.

- Creating Pull Request and Merging two branches.

Create branch and commit some changes locally on the new Branch

```bash
git branch practical1
git switch practical1

# Made some changes and staging all changes
git add .

# Create a commit
git commit -m "Concept explanation for Practical1"

# Pushing new changes on github/practical1
git push github practical1
```