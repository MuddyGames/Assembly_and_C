# Assembly and C Module Practicals

Create a private repository and share individual practical sub-directories in spreadsheet as advised.

URLs should be formatted as per the following example 

`https://github.com/MuddyGames/Assembly_and_C/tree/main/PRACTICAL_01`


# Steps to create Repository

Github should be used to store each practical. Practical 01 will be stored in sub-directory PRACTICAL_01. Practicals 01 to N will be stored in week directory format e.g week 03 is stored in **PRACTICAL_03**. 

## Create Private Repository

Sign into GitHub or create a new account. After completing sign-in process create a private repository. Set repository access to Private as show in image below.

![Create Repo](https://github.com/MuddyGames/Assembly_and_C/blob/main/images/create_repo.png)
On creation of the repository a page similar to the one shown below will be displayed.

If you are already familiar with GitHub follow the instructions as shown, if not continue to the next steps.

![Repo Created](https://github.com/MuddyGames/Assembly_and_C/blob/main/images/repo_created.png)
## Start GitBash

Start **GitBash** or install [GitBash](https://git-scm.com/downloads) if it is not already installed on your computer. Navigate to the C drive on your system and create a `projects` directory.

The following are common commands within GitBash Terminal.

| Command   | Function                                              |
| --------- | ----------------------------------------------------- |
| **ls**    | Lists a directory’s content                           |
| **pwd**   | Shows the current working directory’s path            |
| **cd**    | Changes the working directory                         |
| **mkdir** | Creates a new directory                               |
| **rm**    | Deletes a file                                        |
| **cp**    | Copies files and directories, including their content |
| **mv**    | Moves or renames files and directories                |
| **touch** | Creates a new empty file                              |
| **file**  | Checks a file’s type                                  |

![Create Directory](https://github.com/MuddyGames/Assembly_and_C/blob/main/images/create_projects_dir.png)
## Clone Repository

Change directory to `projects` directory and clone repository. Use the git clone command with the url shown when repository was created.

![Clone Repo](https://github.com/MuddyGames/Assembly_and_C/blob/main/images/clone_repo.png)
![Clone Repo Login](https://github.com/MuddyGames/Assembly_and_C/blob/main/images/clone_repo_login.png)
![Clone Repo Login](https://github.com/MuddyGames/Assembly_and_C/blob/main/images/clone_repo_confirmed.png)
## Make Practical Directory 

When in directory `Assembly_and_C` use the following command to create a sub-directory `PRACTICAL_01`.
```
mkdir PRACTICAL_01
```
Check that the directory is created properly by listing the directory contents using the `ls` command.

![Check directory contents](https://github.com/MuddyGames/Assembly_and_C/blob/main/images/ls_command.png)

## Complete Practical Files

Complete each step of the practical creating and saving files as specified. Save these files in the PRACTICAL_## directory. Example below.

![Practical files](https://github.com/MuddyGames/Assembly_and_C/blob/main/images/complete_practical_files.png)
## Commit Files to GitHub

While in the root of your GitHub project complete an `add`, `git commit` and `git push` as shown below.

```
git add .
git commit -am "Practical 01"
git push
```

![Git Add](https://github.com/MuddyGames/Assembly_and_C/blob/main/images/git_add.png)
![Git Push](https://github.com/MuddyGames/Assembly_and_C/blob/main/images/git_push.png)
## Update a Spreadsheet
