# GIT CHEAT SHEET - Chas Academy
## Configure user information for ALL local repositories

### Sets the name you want attached to your commit transactions
```BASH
$ git config -- global user.name "[name]"
```

### Sets the email you want attached to your commit transactions
```BASH
$ git config --global user.email "[email address]"
```

### Enables helpful colorization of command line output
```BASH
$ git config --global color.ui auto
```

## MAKE CHANGES

### Lists all new or modified files to be commited
$ git status

### Snapshots the file in preparation for versioning
$ git add [file]

### Unstages the file, but preserve its contents
$ git reset [file]

### Shows file differences not yet staged
$ git diff

### Shows file differences between staging and the last file version
$ git diff --staged

### Records file snapshots permanently in verison history

$ git commit -m "[descriptive message]"