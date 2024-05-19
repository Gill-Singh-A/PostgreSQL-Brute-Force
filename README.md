# PostgreSQL Brute Force
A Python Program that uses psycopg2 module to brute force PostgreSQL Server 
## Requirements
Language Used = Python3<br />
Modules/Packages used:
* psycopg2
* datetime
* optparse
* colorama
* multiprocessing
* time
<!-- -->
Install the dependencies:
```bash
pip install -r requirements.txt
```
## Arguments
* '-s', "--server" : Target PostgreSQL Server
* '-p', "--port" : Port of Target PostgreSQL Server (Default=5432)
* '-u', "--users" : Target Users (seperated by ',') or File containing List of Users
* '-P', "--password" : Passwords (seperated by ',') or File containing List of Passwords
* '-c', "--credentials" : Name of File containing Credentials in format ({user}:{password})
* '-w', "--write" : CSV File to Dump Successful Logins (default=current data and time)