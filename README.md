# sql-command
welcome to SQL DBA
  commands 
------------------------
create database name                 ------------------------>>>creating db
select  *from sys.sysaltfiles          --------------------------->>> To shows all details for instance
select *from sys.databases          -------------------->>>
select  *from sys.sysdatabase      ------------------->>>
select *from sys.master_files       ------------------->>>

sp_helpfile                                  ------------------->>>
sp_helpdb                                    ----------------------->>> it shows all db details and size details
sp_help 'dbname'                        -------->>> it shows perticular db name details
sp_readerrorlog                           --------->>>>> it will shows error log details
select @@version                       ------->>> 

 
select SERVERPROPERTY('productversion') ------------>>>>>
select SERVERPROPERTY('productlevel')   ------------------>>>>

------------------------------------------------------------------------------------------------------

sp_who  ------------>>>
sp_who2 ----------->>>


daily responceiblities
---------------------------
1.check for shift handover
2.check for task continty supprot needed
3.perform the ticket queue 
4.verify the health check critical servers
5.perform any changes requesting during your shift
6.in an off-shere onsite model attanding the status calls

    Health check
--------------------
1.instance running are not
2.agent running are not
3.Reading error/agent logs
4.HA sycronization /failure checks
5.disc space checks
6.DBA settings
7.data bace settings
8. event viewer
9.sql server settings
10.high availablities error/agent logs
11.storges
12.checking backups
sp_who2 active -------->>>


sp_whoisactive                  ------>>>     sp_who is active procedure download -------go from goggle
sp_who idnumber         ------------>>>
sp_who2 idnumber       ------------>>>
