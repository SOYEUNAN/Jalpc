---
layout: post
title:  "DB JAVA Connection (DB 커넥션) 정보"
date:   2018-05-21
desc: "Quick test on writing code snippets in a blog post"
keywords: "DB,JAVA,Connection,db connection,db정보,oracle connection, Hian"
categories: [Database]
tags: [Jalpc,Jekyll]
icon: icon-html
---
         



* Oracle (오라클) *
Class.forName("oracle.jdbc.driver.OracleDriver");
Conn = DriverManager.getConnection("jdbc:oracle:thin:@localhost:1521:DB NAME", "ID", "PASS"); 

* PostgreSQL (포스트그래스에스큐엘) *
Class.forName("org.postgresql.Driver");
Conn = DriverManager.getConnection("jdbc:postgresql://localhost:1521/DB NAME", "ID", "PASS"); 

* Mssql (엠에스에스큐엘) *
Class.forName("com.microsoft.jdbc.sqlserver.SQLServerDriver"); 
Conn = DriverManager.getConnection("jdbc:microsoft:sqlserver://localhost:1433;DatabaseName=DB NAME", "ID", "PASS"); 

* Mssql (2005 버전 이상) (엠에스에스큐엘) *
Class.forName("com.microsoft.sqlserver.jdbc.SQLServerDriver"); 
Conn = DriverManager.getConnection("jdbc:sqlserver://localhost:1433;DatabaseName=DB NAME", "ID", "PASS"); 

* Maria (마리아) *
Class.forName("org.mariadb.jdbc.Driver"); 
Conn = DriverManager.getConnection("jdbc:mariadb://localhost:3306/DB NAME", "ID", "PASS"); 

* Mysql (마이에스큐엘) *
Class.forName("com.mysql.jdbc.Driver"); 
Conn = DriverManager.getConnection("jdbc:mysql://localhost:3306/DB NAME", "ID", "PASS"); 

* Sybase (사이베이스) *
Class.forName("com.sybase.jdbc2.jdbc.SybDriver"); 
Conn = DriverManager.getConnection("jdbc:sybase:Tds:localhost:4100/DB NAME", "ID", "PASS"); 

* Informix (인포믹스) * 
Class.forName("com.informix.jdbc.IfxDriver"); 
Conn = DriverManager.getConnection("jdbc:informix-sqli://localhost:1567/DB NAME;user=ID;password=PASS"); 

* IBM db2 (디비2) * 
Class.forName("com.ibm.db2.jcc.DB2Driver"); 
Conn = DriverManager.getConnection("jdbc:db2://localhost:50000/DB NAME", "ID", "PASS"); 

* Altibase (알티베이스) * 
Class.forName("Altibase.jdbc.driver.AltibaseDriver"); 
Conn = DriverManager.getConnection("jdbc:Altibase://localhost:20300/DB NAME", "ID", "PASS"); 

* Tibero (티베로) * 
Class.forName("com.tmax.tibero.jdbc.TbDriver"); 
Conn = DriverManager.getConnection("jdbc:tibero:thin:@localhost:8629:DB NAME", "ID", "PASS"); 

* Cubrid (큐브리드) * 
Class.forName("cubrid.jdbc.driver.CUBRIDDriver"); 
Conn = DriverManager.getConnection("jdbc:cubrid:localhost:1521:DB NAME:::", "ID", "PASS"); 

* MDB (엠디비) *
Class.forName("sun.jdbc.odbc.JdbcOdbcDriver"); 
Conn = DriverManager.getConnection("jdbc:odbc:DB NAME", "ID", "PASS"); 

