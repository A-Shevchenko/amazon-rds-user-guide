# Options for the Microsoft SQL Server database engine<a name="Appendix.SQLServer.Options"></a>

In this section, you can find descriptions for options that are available for Amazon RDS instances running the Microsoft SQL Server DB engine\. To enable these options, you add them to an option group, and then associate the option group with your DB instance\. For more information, see [Working with option groups](USER_WorkingWithOptionGroups.md)\. 

If you're looking for optional features that aren't added through RDS option groups \(such as SSL, Microsoft Windows Authentication, and Amazon S3 integration\), see [Additional features for Microsoft SQL Server on Amazon RDS](User.SQLServer.AdditionalFeatures.md)\.

Amazon RDS supports the following options for Microsoft SQL Server DB instances\. 


****  

| Option | Option ID | Engine editions | 
| --- | --- | --- | 
|  [Native backup and restore](Appendix.SQLServer.Options.BackupRestore.md)  |  `SQLSERVER_BACKUP_RESTORE`  |  SQL Server Enterprise Edition SQL Server Standard Edition SQL Server Web Edition SQL Server Express Edition  | 
|  [Transparent Data Encryption](Appendix.SQLServer.Options.TDE.md)  |  `TRANSPARENT_DATA_ENCRYPTION` \(RDS console\) `TDE` \(AWS CLI and RDS API\)  |  SQL Server 2012–2019 Enterprise Edition SQL Server 2019 Standard Edition | 
|  [SQL Server Audit](Appendix.SQLServer.Options.Audit.md)  |  `SQLSERVER_AUDIT`  |  In RDS, starting with SQL Server 2012, all editions of SQL Server support server\-level audits, and Enterprise Edition also supports database\-level audits\. Starting with SQL Server SQL Server 2016 \(13\.x\) SP1, all editions support both server\-level and database\-level audits\. For more information, see [SQL Server Audit \(database engine\)](https://docs.microsoft.com/sql/relational-databases/security/auditing/sql-server-audit-database-engine?view=sql-server-2017) in the SQL Server documentation\. | 
|  [SQL Server Analysis Services](Appendix.SQLServer.Options.SSAS.md)  |  `SSAS`  |  SQL Server Enterprise Edition SQL Server Standard Edition  | 
|  [SQL Server Integration Services](Appendix.SQLServer.Options.SSIS.md)  |  `SSIS`  |  SQL Server Enterprise Edition SQL Server Standard Edition  | 
|  [SQL Server Reporting Services](Appendix.SQLServer.Options.SSRS.md)  |  `SSRS`  |  SQL Server Enterprise Edition SQL Server Standard Edition  | 
|  [Microsoft Distributed Transaction Coordinator](Appendix.SQLServer.Options.MSDTC.md)  |  `MSDTC`  |  In RDS, starting with SQL Server 2012, all editions of SQL Server support distributed transactions\.  | 