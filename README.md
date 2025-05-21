2nd:

mvn archetype:generate -DgroupId=com.mrit -DartifactId=HelloWorld -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
code .
dir
cd

mvn compile
mvn test
mvn packages
mvn clean install
mvn clean

mvn exec:java -Dexec.mainClass="com.mrit.App"


1St:


git config --global user.email "your_email@example.com"
git config --global user.name "your_username"
git config --list

git init
git remote add origin "link"

git add .
git status 


git commit -m "Initial commit with notes file"
git push origin main

Branches:
git branch feature_update
git checkout feature_update
git branch
echo " ">>filename.txt
git add filename.txt
git commit -m " "
git checkout main
git branch
git merge feature_update
git push origin main
