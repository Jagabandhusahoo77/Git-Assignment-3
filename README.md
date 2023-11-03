
# Devops Git Assignment Project

 Create a Git working directory, with the following branches:

● Develop

● F1

● f2

2. In the master branch, commit main.txt file

3. Put develop.txt in develop branch, f1.txt and f2.txt in f1 and 
f2 respectively

4. Push all these branches to GitHub

5. On local delete f2 branch

6. Delete the same branch on GitHub as well
# **1. Create a Git working directory, with the following branches:**

mkdir my-git-repo
cd my-git-repo
git init

# Create the develop, f1, and f2 branches
git checkout -b develop
git checkout -b f1
git checkout -b f2

# **2. In the master branch, commit main.txt file:**

git checkout master
echo "Main content" > main.txt
git add main.txt
git commit -m "Added main.txt file"

# **3. Put develop.txt in develop branch, f1.txt and f2.txt in f1 and f2 respectively:**

git checkout develop
echo "Develop content" > develop.txt
git add develop.txt
git commit -m "Added develop.txt file"

git checkout f1
echo "F1 content" > f1.txt
git add f1.txt
git commit -m "Added f1.txt file"

git checkout f2
echo "F2 content" > f2.txt
git add f2.txt
git commit -m "Added f2.txt file"

# **4. Push all these branches to GitHub:**

git push origin master develop f1 f2

# **5. On local delete f2 branch:**

git branch -d f2

# **6. Delete the same branch on GitHub as well:**

git push origin --delete f2

Once you have completed these steps, you will have pushed all three branches to GitHub, and then deleted the f2 branch from both your local repository and GitHub.# Git-Assignment-3
