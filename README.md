# Online-Banking-Management
Online Banking Management using System Programming in Linux and C

MT2020128   Amit Jain
SS Mini project 

# TO COMPILE SERVER AND CLIENT RUN THESE COMMANDS ON TERMINAL

$ gcc Aserver.c -o server

$ gcc Aclient.c -o client




# TO RUN SERVER

$ ./server



# TO RUN CLIENT IN DIFFERENT TERMINAL

$ ./client



## Client will ask for id and password 

1. For admin login 
	
		ID   : admin
		Pass : asdfg


2. For user login 

	Either you can create your own user through admin and log in with those credentials
	or 
	I created some user accounts you can use their credentials.
	(These id pass are writen at the end of this README file)


3. Whenever you will perform any transaction a transaction id will be generated.
	
	You can view any transaction using the transaction id or by name of user
	by running the following commands on a terminal,
	
	$ gcc tHistory.c
	$ ./a.out
	
	
4. You can see all records of all existing users sequentially by running the following
	
	$ gcc readrecords.c
	$ ./a.out








  ###   ID AND PASSWORDS OF ALREADY EXISTING ACCOUNTS   ###     

	Name 1        : amit
	Password 1    : amit123
	Name 2        : rahul
	Password 2    : rahul123
	Account no.   : 90090000
	Balance       : 2390.000000


	Name 1        : rohan
	Password 1    : rohan123
	Name 2        : -
	Password 2    : -
	Account no.   : 90090001
	Balance       : 2000.000000
	
	Name 1        : sahil
	Password 1    : sahil123
	Name 2        : -
	Password 2    : -
	Account no.   : 90090007
	Balance       : 5020.000000
	
	Name 1        : ashutosh
	Password 1    : ashutosh123
	Name 2        : -
	Password 2    : -
	Account no.   : 90090012
	Balance       : 10000.000000




