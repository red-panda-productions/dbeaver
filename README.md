[![Build Status](https://api.travis-ci.com/dbeaver/dbeaver.svg?branch=devel)](https://app.travis-ci.com/github/dbeaver/dbeaver)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/fa0bb9cf5a904c7d87424f8f6351ba92)](https://www.codacy.com/gh/dbeaver/dbeaver/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=dbeaver/dbeaver&amp;utm_campaign=Badge_Grade)
[![Apache 2.0](https://img.shields.io/github/license/cronn-de/jira-sync.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Java CI](https://github.com/dbeaver/dbeaver/workflows/Java%20CI/badge.svg)](https://github.com/dbeaver/dbeaver/actions?query=workflow%3A%22Java+CI%22)
<!--[![paypal](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=KFGAGZ24YZE3C)-->


<img src="https://github.com/dbeaver/dbeaver/wiki/images/dbeaver-icon-64x64.png" align="right"/>

# DBeaver

Free multi-platform database tool for developers, SQL programmers, database administrators and analysts.  
Supports any database which has JDBC driver (which basically means - ANY database). 

* Has a lot of <a href="https://github.com/dbeaver/dbeaver/wiki">features</a> including metadata editor, SQL editor, rich data editor, ERD, data export/import/migration, SQL execution plans, etc.
* Based on <a href="https://wiki.eclipse.org/Rich_Client_Platform">Eclipse</a> platform.
* Uses plugins architecture and provides additional functionality for the following databases: MySQL/MariaDB, PostgreSQL, Greenplum, Oracle, DB2 LUW, Exasol, SQL Server, Sybase/SAP ASE, SQLite, Firebird, H2, HSQLDB, Derby, Teradata, Vertica, Netezza, Informix, etc.

<a href="https://dbeaver.io/product/dbeaver-ss-mock.png"><img src="https://dbeaver.io/product/dbeaver-ss-mock.png" width="400"/></a>
<a href="https://dbeaver.io/product/dbeaver-ss-erd.png"><img src="https://dbeaver.io/product/dbeaver-ss-erd.png" width="400"/></a>
<a href="https://dbeaver.io/product/dbeaver-ss-classic-new.png"><img src="https://dbeaver.io/product/dbeaver-ss-classic-new.png" width="400"/></a>
<a href="https://dbeaver.io/product/dbeaver-ss-dark-new.png"><img src="https://dbeaver.io/product/dbeaver-ss-dark-new.png" width="400"/></a>

## Download

You can download prebuilt binaries from <a href="https://github.com/red-panda-productions/dbeaver/releases">GitHub releases</a>.  
You can also download from this github page.  

## Running

Just run an installer (or unzip an archive) and run `dbeaver`.  

Note: DBeaver needs Java to run. <a href="https://adoptopenjdk.net/" target="_blank">Open JDK 11</a> is advised to be installed seperatly from the project.
You can change default JDK version by replacing directory `jre` in dbeaver installation folder.

## Documentation

* <a href="https://github.com/dbeaver/dbeaver/wiki">WIKI</a>

## Building

#### Prerequisites:

 1. Java (JDK) 11 or later (<a href="https://adoptopenjdk.net/" target="_blank">AdoptOpenJDK 11</a> is our default Java at the moment).
 2. <a href="https://maven.apache.org/" target="_blank">Apache Maven 3.6+</a>
 3. Internet access
 4. Git client (for example git bash)

#### Build

```sh
git clone https://github.com/RedPandaProductions/dbeaver.git dbeaver
cd dbeaver
mvn package
```
Binaries are in `product/community/target/products`
 
#### Source code
 To be able to work with the source code, we would suggest following this <a href="https://docs.google.com/document/d/1Op-ZdLpdNP08QFloQKyorNbVbRiunzYMqF_xWCWkbuQ/edit?usp=sharing">guide</a>

## Notes

This is not the official DBeaver version, If you would like to improve DBeaver version without the current code changes (see also <a href="https://github.com/red-panda-productions/dbeaver/releases">Release Notes</a>) We would suggest visiting the official <a href ="https://github.com/dbeaver/dbeaver/">DBeaver github</a>.

