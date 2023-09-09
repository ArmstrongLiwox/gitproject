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

## collaboration and remote repositories
>create github account
>pushing your local git repository to your remote github repository
```
git remote add origin https://github.com/ArmstrongLiwox/gitproject.git
```
```
git push origin master
```
![git push](https://github.com/ArmstrongLiwox/gitproject/assets/143335106/2fc0df6f-7f1a-4620-a1dc-3479cf362184)

## Cloning git remote repository
>cloning is to copy the remote repository unto our computer
```
git clone https://github.com/ArmstrongLiwox/gitproject
```
![git clone](https://github.com/ArmstrongLiwox/gitproject/assets/143335106/11008588-49f2-4f3c-b04b-889d86651c77)
```
git commit -m "added the markdown practice"
```
![final commit](https://github.com/ArmstrongLiwox/gitproject/assets/143335106/17c53883-edea-4c34-ae4b-4386a9150305)

## Branch management and tagging
>my markdown practice file is saved at [markdown_practice.md](https://github.com/ArmstrongLiwox/gitproject/blob/master/markdown_practice.md)

![final commit](https://github.com/ArmstrongLiwox/gitproject/assets/143335106/6c84ee8a-adc3-4d63-8b26-67ae858a7943)

### Thank You
