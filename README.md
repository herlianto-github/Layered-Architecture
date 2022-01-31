# Layered Architecture

## Description

An awesome Layered Architecture template to jumpstart your projects!

## Getting Started

### Dependencies

- [Git](https://git-scm.com)
- [Golang](https://go.dev)
- [Visual Studio Code](https://code.visualstudio.com)

### Installing and initialize this repository

- Clone this repository

    ```console
    git clone https://github.com/herlianto-github/Layered-Architecture
    ```

- Change Project-name

    ```console
    mv Layered-Architecture/ project-name    
    ```
    mv: To rename a directory Layered-Architecture to 'project-name'.

    ```console
    cd project-name 
    ```
    cd: command used to change the current working directory 'project-name'.

- Initialize git

    ```console
    rm -rf .git    
    ```
    rm -rf: Command is used to delete files and directories on Linux and other Unix-like operating systems.

    ```console
    git init
    ```
    git init: Command is an incredibly easy way to create new version-controlled projects.

- Create simple hello world

    ```console
    go mod init project-name
    ```
    Creates a new module, initializing the go.mod file that describes the module. At the start, it will only add the module path and go version in go mod file.

    ```console
    touch main.go    
    ```
    touch: It is used to create a file without any content. The file created using touch command is empty.

    ```console
    echo 'package main 
    
    import "fmt"
    
    func main(){
    
        fmt.Println("Hello World")
    
    }' >> main.go
    ```
    echo: Command that is mostly used in shell scripts and batch files to output status text to the screen or a file.

- First commit and push

    ```console
    git status 
    ```
    git status: Command is used to display the state of the repository and staging area.

    ```console
    git add .    
    ```
    git add: Command adds a change in the working directory to the staging area.

    ```console
    git commit -m "first commit"
    ```
    git commit: Command captures a snapshot of the project's currently staged changes.

    ```console
    git branch -M main
    ```
    git branch -M: Command lets you rename branches.

    ```console
    git remote add origin https://github.com/username/project-origin.git
    ```
    git: Command let you add new remote repository.

    ```console
    git push -u origin main    
    ```
    git push: Command is used to upload local repository content to a remote repository.

### Executing program

- How to run the program

    ```console
    go run main.go    
    ```
    go run: Command compiles and runs a main package comprised of the .go files specified on the command line.

## Help

- **Configs**<br/>Contain database and http configuration
- **Delivery (API)**<br/>API http handlers or controllers
- **Entities**<br/>Contain database model
- **Repository** <br/> Contain implementation entities database anq query with ORM.
- **Utils**<br/>Contain database driver (mySQL)

## Authors

[Herlianto](https://github.com/herlianto-github)

## Version History

- 0.0.1
  - Initial Release

## Acknowledgments

- [Layered Architecture](https://www.oreilly.com/library/view/software-architecture-patterns/9781491971437/ch01.html)
