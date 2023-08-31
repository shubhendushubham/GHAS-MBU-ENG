# GHAS-MBU-ENG

This is markdown file for Github Advanced Security Hands-on Demo 

Date :- 31-08-2023 
Presenter: Shubhendu

*Prerequisites*:
   - GiHub Actions & Workflow
   - GitHub Enterprise Cloud/ Enterprise Server Account 
   - Personal/ Organisation authentication techniques 

## Objective:
    - Github Advance Security Definition 
    - Purpose of Specific GHAS Features
    - Roles involved in securiy workflow
    - The Best practice recognisation, for identifying & responding to security vulberabilities

## Define : GitHub Advanced Security 

Suite of tools and features that gives the ability to identify security vulnerabilities in

: Supply Chain 
: Code
: Environments

1. Supply Chain: 

- Integration with 3rd party tools or open source libraries/software.
- componets which are not produced by organistion itself aka Dependencies are more vulnerable, we need to **actively review each one of them** 

eg: Log4j Year 2021

**GitHub Supply chain Mangement**

- GitHub provides automated features that flags vulnerable dependencies
- Alert to the specific Team member mentioning potential dangers 
- Helps in Vulnerability mitigation 
- Automate the process that monitors and secures project dependencies and searches for vulnerabilities 

Demo : Security Overview 

![Alt text](image.png)

Features:
 
 * Central location to monitor the state of project dependencies
 * Allows to identify problematic repository
 * Help to understand criticality of depndencies 
 * View, Fileter and sort automated security features from the security alerts generated for organisation/ specific team.


Code scan
 ![Alt text](image-1.png)   
code scan setup 2
 ![Alt text](image-2.png)

 3
 ![Alt text](image-3.png)

 Scan Result 

 ![Alt text](image-4.png)