#Workshop 11 Instruction

### Maven commands
1. mvnw
2. mvnw compile
3. mvnw package
4. mvnw clean package
5. mvnw clean
6. mvnw clean package spring-boot:run
7. mvnw spring-boot:run

## Git command
1. git init
2. git remote add origin (insert url)
3. git add *
4. git status
5. git commit -m "insert a message"
6. git push -u origin master
7. git pull
8. git checkout -b develop master
9. git add * (add to develop branch)
10. git commit -m "add readme file"
11. git push -u origin develop (push to remote git develop branch)
12. git checkout master
13. git merge develop (merge changes done in develop branch into master branch)
14. git push -u origin master

//make changes in master, and need to synchronize this change to develop branch
// assume changes has already been checked into master branch
git checkout develop

git merge master (merge changes done in master branch into develop branch)

git push -u origin develop
