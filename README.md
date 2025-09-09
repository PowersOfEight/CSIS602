# Introduction to Software Engineering
## CSIS 602
### I know, I know.... this is literally our job title...

### The Tree Structure 
So as of right meow, I've organized the class materials into this tree structure:
```bash

poe@PowersOfEight: ~/CSIS602 $ tree .                                                                                                                                               master 
.
├── csci-602-spring-boot-template-PowersOfEight
│   ├── CONTRIBUTING.md
│   ├── images
│   │   └── datasource_settings.png
│   ├── LICENSE.md
│   ├── mvnw
│   ├── mvnw.cmd
│   ├── pom.xml
│   ├── README.md
│   └── src
│       ├── main
│       │   ├── java
│       │   │   └── edu
│       │   │       └── citadel
│       │   │           ├── api
│       │   │           │   ├── AccountEndpoints.java
│       │   │           │   ├── request
│       │   │           │   │   └── AccountRequestBody.java
│       │   │           │   └── StatusEndpoints.java
│       │   │           ├── config
│       │   │           │   └── ApplicationConfig.java
│       │   │           ├── dal
│       │   │           │   ├── AccountRepository.java
│       │   │           │   └── model
│       │   │           │       └── Account.java
│       │   │           └── main
│       │   │               └── RestApiApplication.java
│       │   └── resources
│       │       ├── application-ghci.yaml
│       │       ├── application-test.yaml
│       │       ├── application.yaml
│       │       ├── banner.txt
│       │       └── db
│       │           └── migration
│       │               └── V1__create_accounts_table.sql
│       └── test
│           └── java
│               └── edu
│                   └── citadel
│                       └── main
│                           └── RestApiApplicationTests.java
├── README.md
└── Weeks
    └── 1
        └── class-notes.md

24 directories, 22 files

```


As you can see, we've got the weeks with `class-notes`, and we'll put in todos to organize/track our progress.

## Submodule(s)

Assignments will be cloned as submodules of this repository for my notes.  Here's an example of an additional submodule for this repo 
done on the first week of class:

```bash

poe@PowersOfEight: ~/CSIS602 $ git submodule add --  git@github.com:CitadelCS/csci-602-spring-boot-template-PowersOfEight.git                                                       master 
Cloning into '/home/poe/CSIS602/csci-602-spring-boot-template-PowersOfEight'...
remote: Enumerating objects: 57, done.
remote: Counting objects: 100% (57/57), done.
remote: Compressing objects: 100% (43/43), done.
remote: Total 57 (delta 5), reused 42 (delta 2), pack-reused 0 (from 0)
Receiving objects: 100% (57/57), 54.13 KiB | 1.50 MiB/s, done.
Resolving deltas: 100% (5/5), done.

```

