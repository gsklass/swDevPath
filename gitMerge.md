Consider [this stackoveflow](https://stackoverflow.com/questions/5601931/what-is-the-best-and-safest-way-to-merge-a-git-branch-into-master)  
Use this form (where 'test' is the name of the working (or development branch)
```
git checkout test
git pull origin master
git checkout master
git merge test answer
```
