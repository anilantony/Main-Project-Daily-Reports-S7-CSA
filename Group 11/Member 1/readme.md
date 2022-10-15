# Group 11 Weekly Report

## 14-10-2022

- **What is Git ?**
> Git is a distributed version-control system for tracking changes in source code during software development .It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed,data integrity,and support for distributed, non-linear workflows.


- **What is GitHub?**
> GitHub, Inc. is a United States-based global company that provides hosting for software development version control using Git. In 2018, it became a subsidiary of Microsoft for US$7.5 billion. It offers the distributed version control and source code management (SCM) functionality of Git, plus its own features


### Offical documentations of Git & GitHub

> - [Git](http://git-scm.com)

> - [GitHub](http://github.com)



## Day 2


- **How to start with git ?** 

- Installing git own your local machine,
    - For Windows users visit : [Git](http://git-scm.com) and download the new version of git. Installing procudures are same when you installing a software setup in windows machine 
    - For Linux Users, open up your terminal window (` Ctrl + Alt + T `) and type the following commands line by line
        - For `Debian based OS ( Ubuntu,Kubuntu,Lubuntu,Debian,Kali linux, etc)`

            ```
            $ sudo apt-get update
            $ sudo apt-get install git
            ```
        - For `RPM based systems (Red Hat Entreprise Linux, openSUSE, Fedora, CentOS, Arch Linux)`
            ```
            $sudo dnf install git-all
            ```

    To check whether git is installed or not

    ```
    $ git --version 
     [it'll show your version of git]
    ```
    
- **First things first - Config Git with Username and User Email**
            
    > In Linux terminal or Windows Command prompt enter the following commands with your details
        
        
        $ git config --global user.name "YourNameGoesHere"
        $ git config --global user.email "YourEmailGoesHere"
        
 
