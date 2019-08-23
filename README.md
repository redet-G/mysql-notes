# MySQL notes
This is a note for a playlist of videos on MySQL
sql code from the vidoes will be included in this repositery


[Download MySQL](https://www.mysql.com/downloads/) 

## Installation
Intalling MySQL on windows as easy as opening the setup and following the instructions.

once installed
Test the server by firing it up from the command prompt the first time. Go to the location of the mysqld server which is probably C:\mysql\bin, and type: 
```bash
mysqld.exe --console
```
NOTE: If you are on NT, then you will have to use mysqld-nt.exe instead of mysqld.exe 

### Installation on linux
you can install MySQL on ubute with the following command
```bash
sudo apt-get update
sudo apt-get install mysql-server
```
The installer will install mysql and promote you a password for the root user.
root is the ultimatly privilage user of you database.

