## Open GIT Bash
- Creating directory <br>
```
mkdir (name)
```


- Changing directory
```
cd (name)
```


- Intialising the repository on your system
```
git init
```
<br>

## Open VSC
- Open file -> Find directory in PC/Disk > Users
- Make any file (add extension `.py`, `.`)
- Open terminal, open drop down menu and select GIT Bash
<img width="209" alt="image" src="https://github.com/Kairos-T/Github-NullsecxOverflow/assets/80029462/1373e1bb-1ed0-4ed6-9c48-be500bd9095e">
<br>

## Git commands

- Viewing status of repository (repo)
```
Git status
```
<img width="367" alt="image" src="https://github.com/Kairos-T/Github-NullsecxOverflow/assets/80029462/329c8972-3920-4c57-98dd-8bb65c063ffd"> <br>
- Add files to staging
```
git add (file) # Staging specific file to be commit 
git add . # Staging all files to be commit
```

- Committing files to GitHub:
```
Git config --global user.name "" (Use this the first time only -- ever)
Git config --global user.email ""
Git commit -m (message) or Git commit --message (message)
```

File statuses: 
```
A: Added
M: Modified
D: Deleted
```
<img width="89" alt="image" src="https://github.com/Kairos-T/Github-NullsecxOverflow/assets/80029462/b6f9e7d7-a295-4088-bf4d-671d797249e7">
<img width="128" alt="image" src="https://github.com/Kairos-T/Github-NullsecxOverflow/assets/80029462/e2ab6674-7bb7-4a5e-b7d0-928e6ff4acb7">

<br>

## Restoring previous version
- Modify a file first, then use `git add (file name)`
```
git restore --stage (file name)
git status
git retore (file)
git status (nothing to commit now)
```
<br>


## .gitignore
- Create a file named '.gitignore'
- Files/Info you dont want the public to see (E.g. VSC Configs, API keys)


<img width="102" alt="image" src="https://github.com/Kairos-T/Github-NullsecxOverflow/assets/80029462/24442a15-78b8-4c30-9676-b4e09677869b">
<img width="369" alt="image" src="https://github.com/Kairos-T/Github-NullsecxOverflow/assets/80029462/1ea3426a-c8d1-449d-8408-3a265922cf40">
<br>


## Deleting files
 ```
 git rm (file name)
 -> rm (file name)
 ```
 - You can still restore the file
 ```
 git restore --staged (file name)
 git restore (file name)
 ```
 <img width="613" alt="image" src="https://github.com/Kairos-T/Github-NullsecxOverflow/assets/80029462/c1aa3464-29f5-47a4-a865-a05fba3acbcc">

 <br>
 
## Renaming files
```
git mv (old file name) (new file name)
```

