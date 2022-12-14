# Recap

## Markdown
- Rezept
  - Listen
  - Bilder

# Version Control with `git`
## Lokal mit `git` Arbeiten

Um ein Repository mit `git` zu verwalten, wird das folgenden genutzt:
```bash
git init . 
# dieses Kommando stellt das aktuelle Verzeichnis `.` unter git-Verwaltung

#Die Haupkonfigurationsdatei befindet sich dann unter:
.git/config

```

- Working Tree
- Staging Area
- Commit
- Repository
  - local
  - remote

- Branch

## `git` Anwendungsfälle (engl. 'use cases')

```bash
# Anlegen eines Repos im aktuellen Verzeichnis
git init . 

# aktueller Status des Repos:
git status

# Datei "FILE" zu 'staging area' Hinzufügen
git add FILE

# "Committen" der Dateien in der 'staging area'
git commit -m "MESSAGE"

# Versionsgeschichte:
git log

# Springen zwischen Versionen (commits)
git checkout COMMIT_HASH

```

## Introduction
- Version Control Systems (VCS)

## Initializing
- The `git` program
- Starting a repository with `git init`
- The `.git` folder

## Basic workflow
- Checking the status with `git status`
- Staging files with `git add`
- Using the `.` shortcut to add all files
- Creating a commit with `git commit`
- Viewing the history with `git log`
- Quick commits with `git commit -am <message>`

https://github.com/DigitalCareerInstitute/BDL-versioning-workflow/

---

## GitHub Integration
- mit SSH
- Ziel: Rezepte `pushen`

---

## Github
- The Github website
- Connecting to GitHub with SSH
- Creating a repository on GH (w. readme)
- GitHub Publishing

https://github.com/DigitalCareerInstitute/BDL-publishing-github/


markdown:? https://github.com/DigitalCareerInstitute/BDL-publishing-authoring

## Locals and Remotes
- Local repository vs. Remote repository
- Creating a repository on GH (no readme)
- Checking a repository's remotes: `git remote -v`
- Adding a remote: `git remote add <name> <url>`
- Pushing a branch for the first time: 
  `git push -u <remote name> <branch name>`

https://github.com/DigitalCareerInstitute/BDL-publishing-changes
https://github.com/DigitalCareerInstitute/BDL-publishing-remotes
