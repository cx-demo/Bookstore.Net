# Bookstore.Net
* Author:   Pedric Kng  
* Updated:  29 Sept 2018

This project is downloaded from Checkmarx knowledge center [[2]], and the repository includes several branches to illustrate incremental scanning with Checkmarx CxSAST.

***
## Git repository branch
- [Master](tree/master)
Original version

- [Fix_1](tree/Fix_1)
Version with some XSS vulnerabilities resolved

- [Fix_2](tree/Fix_2)
Version with XSS and SQLi vulnerabilities resolved

## Pre-requsites
-	CxSAST 8.9: port 80
-	Java 1.8
-	Chrome browser

## Lab Objectives
1.	Create first project interfacing with GIT SCM using source pulling
2.	Execute incremental scan with a GIT branch
3.	Compare scans
4.	Experience incremental scan fail due to exceeding threshold.



## References
CxSAST Quick Start [[1]]  
BookStore_NET [[2]]  

[1]:https://checkmarx.atlassian.net/wiki/spaces/KC/pages/1170279316/CxSAST+Quick+Start "CxSAST Quick Start"
[2]:http://download.checkmarx.com/CXPS/SourceSamples/BookStore_NET.zip "Bookstore.Net"
