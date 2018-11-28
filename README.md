# LogCollector
Script used to collect the BigSQL Logs

## Usage

Run the Log collector script (./logCollector.sh)


<br>

Sample Output:

[root@testnode51 opt]# ./logCollector.sh
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

Enter the full host names of the nodes. If you need to collect the logs from multiple nodes, provide the hostname delimited by comma : testnode51.fyre.ibm.com,testnode52.fyre.ibm.com

Collecting Logs from path : /var/ibm/bigsql/logs from Node: testnode51.fyre.ibm.com and path /tmp/TS123456/testnode51.fyre.ibm.com/var/ibm/bigsql/logs

Collecting Logs from path : /var/ibm/bigsql/diag/DIAG0000 from Node: testnode51.fyre.ibm.com and path /tmp/TS123456/testnode51.fyre.ibm.com/var/ibm/bigsql/diag/DIAG0000

Collecting Logs from path : /var/log/hive from Node: testnode51.fyre.ibm.com and path /tmp/TS123456/testnode51.fyre.ibm.com/var/log/hive

Collecting Logs from path : /var/log/webhcat from Node: testnode51.fyre.ibm.com and path /tmp/TS123456/testnode51.fyre.ibm.com/var/log/webhcat

Collecting Logs from path : /var/ibm/bigsql/logs from Node: testnode52.fyre.ibm.com and path /tmp/TS123456/testnode52.fyre.ibm.com/var/ibm/bigsql/logs

Collecting Logs from path : /var/ibm/bigsql/diag/DIAG0000 from Node: testnode52.fyre.ibm.com and path /tmp/TS123456/testnode52.fyre.ibm.com/var/ibm/bigsql/diag/DIAG0000

Collecting Logs from path : /var/log/hive from Node: testnode52.fyre.ibm.com and path /tmp/TS123456/testnode52.fyre.ibm.com/var/log/hive

Collecting Logs from path : /var/log/webhcat from Node: testnode52.fyre.ibm.com and path /tmp/TS123456/testnode52.fyre.ibm.com/var/log/webhcat

testnode51.fyre.ibm.com.tar.gz                                                                                                                            100% 3737KB   3.7MB/s   00:00
testnode52.ibm.com.tar.gz                                                                                                                            100% 7348KB   7.2MB/s   00:00

Packaging PMRStamping data...


!!!!!!!!!!!!! Execution completed.!!!!!!!!!!!!
!!!!!!!!!!!!! Please check in /tmp/TS123456.tar.gz !!!!!!!!!!!!


[root@testnode51 opt]# 
[root@testnode51 opt]#

<br>       
        
        
## Author

**Nisanth Simon** - [NisanthSimon@LinkedIn]


[NisanthSimon@LinkedIn]: https://au.linkedin.com/in/nisanth-simon-03b2149
 