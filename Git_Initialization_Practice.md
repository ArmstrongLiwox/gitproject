# gitproject

## Initializing a repository and making commits

Git is a Distributed version control system, which is an improvement of the former SVN.

> Initializing a Git repository
```
mkdir DevOps
```
```
cd DevOps
```
```
git init
```
![git init](https://github.com/ArmstrongLiwox/gitproject/assets/143335106/ae2c9cfe-ae6d-416e-90d7-5e93eade23e4)

## Make your first commit
> Commit is to save changes made to a file.
```
touch index.txt
```
```
git add
```
```
git commit -m "initial commit"
```
![git add commit](https://github.com/ArmstrongLiwox/gitproject/assets/143335106/0bb1d01f-5e46-40a6-bf00-be648481a460)

## Working with branches
> make your first git branch
```
git checkout -b mynewbranch
```
> listing your branches
```
git branch
```
>change into an old branch
```
git checkout master
```
![git checkout](https://github.com/ArmstrongLiwox/gitproject/assets/143335106/1ee36357-083d-4a9b-af11-9b3ef7955e51)

>merge a branch into another branch
```
git merge mynewbranch
```
>delete a git branch
```
git branch -d mynewbranch
```
![delete branch](https://github.com/ArmstrongLiwox/gitproject/assets/143335106/f52659ca-8289-4f60-a826-6704938704d7)
