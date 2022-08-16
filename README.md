## Start Machine Learning project.

### Software and account Requirement.

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

Creating Conda environment
```
conda create -p venv python == 3.7 -y
```

Activating the virtual environment 
```
conda activate venv/
```  
OR
```
conda activate venv
```

```
pip install -r requirements.txt
```

To add files to git
```
git add <file_name>
```

OR
```
git add .  (It will add all the files in the current directory)
```


> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the status of git
```
git status
```

To check all the versions maintained by git
```
git log
```

To create version/commmit all changes by git
```
git commit -m "custom message"
```

To send changes/version to github
```
git push origin main
```

To check remote url
```
git remote -v
```

