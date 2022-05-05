# GitLearning
Repo to learn git

# Commands: 

### Init a repository
```bash

git init

```

### Adds untracked files
```bash

git add .

```

### Discard changes on directory

```bash

git restore <file_name>

``` 

### Removes tracked files 

```bash

git reset

```

### Removes untracked files
```bash

git clean -n (list of files to delete)

git clean -nd (works for directories)

git clean -idf (interactive deleting)

```


### Commit changes
```bash

git commit -m <message>

```

### Add remote repository
```bash

git remote add <remote_branch_name> <repo_url>

```

### Push your changes to remote repository

```bash

git push <remote_branch_name> <your_branch_name>

```

### To pull from remote remote repository *e.g. GitHub*
```bash

git pull <repo_url>

```