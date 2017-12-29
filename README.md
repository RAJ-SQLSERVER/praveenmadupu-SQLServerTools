# SQLServerTools
This repo is the home of various SQL-Server-Tools for MS SQL-Server

- [MailJobTimeLine_DE.sql](../master/MailJobTimeLine_DE.sql) - This SQL (german, theres also a not actual english version [MailJobTimeLine.sql](../master/MailJobTimeLine.sql)) sends an email with all jobs displayed in a graphical timeline:
[Exampletimeline](https://thomas-s-b.github.io/Timline_Example.html)
![TimelinePicture](https://github.com/Thomas-S-B/SQLServerTools/blob/master/Images/Timeline_sql.jpg) 

- [GetExecutionPlans.sql](../master/GetExecutionPlans.sql) - Find executionplans
- [GetProcedureMetrics.sql](../master/GetProcedureMetrics.sql) - Get proceduremetrics
- [GetErrorLog.sql](../master/GetErrorLog.sql) - Get/Read errorlog
- [GetIndexFragmentation.sql](../master/GetIndexFragmentation.sql) - Get index fragmentaion
- [GetExecutionAndInvokecount.sql](../master/GetExecutionAndInvokecount.sql) - Get executionplans and count of invoke
- [FREEPROCCACHE.sql](../master/FREEPROCCACHE.sql) - Delete executionplan of specific object, see also [GetExecutionAndInvokecount.sql](../master/GetExecutionAndInvokecount.sql) to get the planhandle
- [GetConnections.sql](../master/GetConnections.sql) - Get current connections
- [FindTriggers.sql](../master/FindTriggers.sql) - Find triggers
- [Top10WorstProcedures.sql](../master/Top10WorstProcedures.sql) - The TOP 10 of the worst procedures
- [SelectFlatFiles.sql](../master/SelectFlatFiles.sql) - Run selects against flatfiles from a filesystem
- [ChangeOptionsInDatabases.sql](../master/ChangeOptionsInDatabases.sql) - Executes an SQL on all or selected Databases
- [CleanupHistories.sql](../master/CleanupHistories.sql) - Cleans up histories
- [OpenTransactions.sql](../master/OpenTransactions.sql) - Shows all current transactions
