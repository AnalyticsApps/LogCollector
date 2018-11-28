# LogCollector
Script used to collect the BigSQL Logs

## Usage

<br>

[root@habigsqlv51 opt]# ./logCollector.sh
 PMR No# : TS123456

 Date (yyyy-mm-dd) issue happened : 2018-08-20

 Component : BigSQL

Description of the issue ("ctrl+d" when done) :
Node went down frequently
This is a production issue
queries fails when node going down

Location where the logs need to be collected (Default Path - \tmp) :

Services running in your Cluster

1)  HDFS
2)  Yarn
3)  MapReduce2
4)  Zookeeper
5)  Hive
6)  Hbase
7)  BigSQL

Enter the service no# for collecting the logs. If you have multiple service logs to be collected, provide the service no# delimited by comma : 7,5

Enter the full host names of the nodes. If you need to collect the logs from multiple nodes, provide the hostname delimited by comma : habigsqlv51.fyre.ibm.com,habigsqlv52.fyre.ibm.com

Collecting Logs from path : /var/ibm/bigsql/logs from Node: habigsqlv51.fyre.ibm.com and path /tmp/TS123456/habigsqlv51.fyre.ibm.com/var/ibm/bigsql/logs

Collecting Logs from path : /var/ibm/bigsql/diag/DIAG0000 from Node: habigsqlv51.fyre.ibm.com and path /tmp/TS123456/habigsqlv51.fyre.ibm.com/var/ibm/bigsql/diag/DIAG0000

Collecting Logs from path : /var/log/hive from Node: habigsqlv51.fyre.ibm.com and path /tmp/TS123456/habigsqlv51.fyre.ibm.com/var/log/hive

Collecting Logs from path : /var/log/webhcat from Node: habigsqlv51.fyre.ibm.com and path /tmp/TS123456/habigsqlv51.fyre.ibm.com/var/log/webhcat

Collecting Logs from path : /var/ibm/bigsql/logs from Node: habigsqlv52.fyre.ibm.com and path /tmp/TS123456/habigsqlv52.fyre.ibm.com/var/ibm/bigsql/logs

Collecting Logs from path : /var/ibm/bigsql/diag/DIAG0000 from Node: habigsqlv52.fyre.ibm.com and path /tmp/TS123456/habigsqlv52.fyre.ibm.com/var/ibm/bigsql/diag/DIAG0000

Collecting Logs from path : /var/log/hive from Node: habigsqlv52.fyre.ibm.com and path /tmp/TS123456/habigsqlv52.fyre.ibm.com/var/log/hive

Collecting Logs from path : /var/log/webhcat from Node: habigsqlv52.fyre.ibm.com and path /tmp/TS123456/habigsqlv52.fyre.ibm.com/var/log/webhcat

habigsqlv51.fyre.ibm.com.tar.gz                                                                                                                            100% 3737KB   3.7MB/s   00:00
habigsqlv52.fyre.ibm.com.tar.gz                                                                                                                            100% 7348KB   7.2MB/s   00:00

Packaging PMRStamping data...


!!!!!!!!!!!!! Execution completed.!!!!!!!!!!!!
!!!!!!!!!!!!! Please check in /tmp/TS123456.tar.gz !!!!!!!!!!!!


[root@habigsqlv51 opt]# 
[root@habigsqlv51 opt]#