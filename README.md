[![Go](https://github.com/herlianto-github/Layered-Architecture/actions/workflows/go.yml/badge.svg)](https://github.com/herlianto-github/Layered-Architecture/actions/workflows/go.yml)

# Layered Architecture

## Description

An awesome Layered Architecture template to jumpstart your RESTful API projects!

## Table of Content

1. [About The Project](#description)
2. [Folder Structure](#structuring)
3. [How To Use](HOW_TO_USE.md)
4. [Contacts](#contacts)

### Dependencies

- [Git](https://git-scm.com)
- [Golang](https://go.dev)
- [Visual Studio Code](https://code.visualstudio.com)

## Structuring

  ```sh
    .
    ├── configs                
    │     └──config.go           # Configs files
    ├── delivery                 # Endpoints handlers or controllers
    │     ├──common
    │     │   ├── global.go           # Constant variable
    │     │   └── http_responses.go   # Default http code, status, message
    │     ├──controllers
    │     │   └── users
    │     │     ├── formatter_req.go    # Default request format for spesific controllers
    │     │     ├── formatter_res.go    # Default response format for spesific controllers
    │     │     ├── users_test.go       # Unit tests for spesific controllers
    │     │     └── users.go            # Spesific controller
    │     ├──helpers
    │     │   └── helper.go           # Helper Function
    │     └──routes  
    │         └── routes.go           # Endpoints list
    ├── entities                
    │     └── users.go          # database model
    ├── repository              
    │     ├── interface.go      # Repository Interface for controllers
    │     ├── users_test.go     # Unit test for spesific repository
    │     └── users.go          # Spesific Repository
    ├── utils                 
    │     └── driver.go         # Database driver
    ├── .env                    # Individual working environment variables
    ├── .gitignore              # Which files to ignore when committing
    ├── go.mod                  
    ├── go.sum                  
    ├── main.go                 # Main Program
    └── README.md    
  ```

## Help

- **Configs**<br/>Contain database and http configuration
- **Delivery (API)**<br/>API http handlers or controllers
- **Entities**<br/>Contain database model
- **Repository** <br/> Contain implementation entities database anq query with ORM.
- **Utils**<br/>Contain database driver (mySQL)

## Contacts

[Herlianto](https://github.com/herlianto-github)

## Version History

- 0.0.1
  - Initial Release

## Acknowledgments

- [Layered Architecture](https://www.oreilly.com/library/view/software-architecture-patterns/9781491971437/ch01.html)
