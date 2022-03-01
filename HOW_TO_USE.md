# How To Use

- Clone this repository

    ```sh
    $ git clone https://github.com/herlianto-github/Layered-Architecture 
    > Cloning into 'Layered-Architecture'...
    > remote: Enumerating objects: 43, done.
    > remote: Counting objects: 100% (43/43), done.
    > remote: Compressing objects: 100% (26/26), done.
    > remote: Total 43 (delta 4), reused 14 (delta 1), pack-reused 0
    > Receiving objects: 100% (43/43), 7.37 KiB | 942.00 KiB/s, done.
    > Resolving deltas: 100% (4/4), done.  
    ```

- Change Project-name

    ```sh
    mv Layered-Architecture/ project-name    
    ```

    ```sh
    cd project-name 
    ```

    ```sh
    code .
    ```

  - mv: To rename a directory Layered-Architecture to 'project-name'.
  - cd: command used to change the current working directory 'project-name'.
  - code . : Launching [vscode](https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line) from the command line

- Initialize git

    ```sh
    rm -rf .git    
    ```

    ```sh
    git init
    ```

  - rm -rf: Command is used to delete files and directories on Linux and other Unix-like operating systems.
  - git init: Command is an incredibly easy way to create new version-controlled projects.

- First commit and push

    ```sh
    git status 
    ```

    ```sh
    git add .    
    ```

    ```sh
    git commit -m "first commit"
    ```

    ```sh
    git branch -M main
    ```

    ```sh
    git remote add origin https://github.com/username/project-origin.git
    ```

    ```sh
    git push -u origin main    
    ```

  - git status: Command is used to display the state of the repository and staging area.
  - git add: Command adds a change in the working directory to the staging area.
  - git commit: Command captures a snapshot of the project's currently staged changes.
  - git branch -M: Command lets you rename branches.
  - git: Command let you add new remote repository.
  - git push: Command is used to upload local repository content to a remote repository.

## Executing program

- How to run the program

    ```go
    go run main.go    
    ```

    go run: Command compiles and runs a main package comprised of the .go files specified on the command line.
