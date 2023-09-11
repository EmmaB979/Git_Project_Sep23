# Git and GitHub Course (11-12/Sep 2023)

Git repository: Single collection of documents where you want to track documents. One project and all the commits you made, creating the different versions. Offline, but online when linking to GitHub. 

GitHub: Online collection of all the different projects Gits, repositories for which you want version control. 

## Initializing a Git

`$ git init`

Creates git folder inside current working directory. Everything below the folder of .git repository will be looked at by the git. (If you do, both you and Git are confused)

`$ git commit -m "meaningful message"`

Committing an update, including a message on why this commit is necessary/useful. (Don't include the filename, already tracked)

- Make clear what changed

- How did you change it

- **What** changed

- Why changed

- Limitations (Is it functioning)

- Effects due to the change

### Conceptualizing progress areas

1. Developing area: folder where I develop my project. Local in your computer

2. Staging Area: Intermediate space to transfer from the developing area to local repository

3. Local repository: the repository (hidden .git folder) where you keep your snapshots, also stored locally. 

#### Developing area

In the computer itself, the folder where the git was created.

#### Staging area

Computer itself. Personal space before committing and starting the gitroutine. Creating a snapshot.

Do by `$ git add filename`

#### Local repository = .git

Contains timeline/tracking of changes

See folder using ls -la

Do by` $ git commit`






