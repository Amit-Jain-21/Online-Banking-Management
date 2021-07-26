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


enter the record num  you want to read  enter -1 to quit  :  1
Name 1        : amit
Password 1    : amit123
Name 2        : rahul
Password 2    : rahul123
Account no.   : 90090000
Balance       : 2390.000000
Record no.    : 1
enter the record num  you want to read  enter -1 to quit  :  2
Name 1        : rohan
Password 1    : rohan123
Name 2        : -
Password 2    : -
Account no.   : 90090001
Balance       : 2000.000000
Record no.    : 2
enter the record num  you want to read  enter -1 to quit  :  3
Name 1        : vikas
Password 1    : vikas123
Name 2        : -
Password 2    : -
Account no.   : 90090014
Balance       : 0.000000
Record no.    : 15
enter the record num  you want to read  enter -1 to quit  :  4
Name 1        : gourav
Password 1    : gourav123
Name 2        : gouri
Password 2    : gouri123
Account no.   : 90090002
Balance       : 3303.000000
Record no.    : 3
enter the record num  you want to read  enter -1 to quit  :  5
Name 1        : nivesh
Password 1    : nivesh123
Name 2        : animesh
Password 2    : animesh123
Account no.   : 90090004
Balance       : 0.000000
Record no.    : 5
enter the record num  you want to read  enter -1 to quit  :  6
Name 1        : geeta
Password 1    : geeta123
Name 2        : -
Password 2    : -
Account no.   : 90090005
Balance       : 0.000000
Record no.    : 6
enter the record num  you want to read  enter -1 to quit  :  7
Name 1        : ram
Password 1    : ram123
Name 2        : -
Password 2    : -
Account no.   : 90090006
Balance       : 0.000000
Record no.    : 7
enter the record num  you want to read  enter -1 to quit  :  8
Name 1        : sahil
Password 1    : sahil123
Name 2        : -
Password 2    : -
Account no.   : 90090007
Balance       : 5020.000000
Record no.    : 8
enter the record num  you want to read  enter -1 to quit  :  9
Name 1        : surbhi
Password 1    : surbhi123
Name 2        : shruti
Password 2    : shr12i123
Account no.   : 90090008
Balance       : 0.000000
Record no.    : 9
enter the record num  you want to read  enter -1 to quit  :  10
Name 1        : anand
Password 1    : anand123
Name 2        : indu
Password 2    : indu123
Account no.   : 90090009
Balance       : 36450.000000
Record no.    : 10
enter the record num  you want to read  enter -1 to quit  :  11
Name 1        : dhruv
Password 1    : dhruv123
Name 2        : -
Password 2    : -
Account no.   : 90090010
Balance       : 0.000000
Record no.    : 11
enter the record num  you want to read  enter -1 to quit  :  12
Name 1        : divi
Password 1    : divi123
Name 2        : priya
Password 2    : priya123
Account no.   : 90090011
Balance       : 250.000000
Record no.    : 12
enter the record num  you want to read  enter -1 to quit  :  13
Name 1        : ashutosh
Password 1    : ashutosh123
Name 2        : -
Password 2    : -
Account no.   : 90090012
Balance       : 10000.000000
Record no.    : 13
enter the record num  you want to read  enter -1 to quit  :  14
Name 1        : rohit
Password 1    : rohit123
Name 2        : -
Password 2    : -
Account no.   : 90090013
Balance       : 2350.000000
Record no.    : 14
enter the record num  you want to read  enter -1 to quit  :  15
Name 1        : chetan
Password 1    : chetan1122
Name 2        : -
Password 2    : -
Account no.   : 90090016
Balance       : 3700.250000
Record no.    : 17

