![image](https://user-images.githubusercontent.com/115451707/196919992-edcfea8b-e3f6-4f35-9398-43be66b5622d.png)
# Big Data Hadoop sample code

HDFS is the primary or major component of the Hadoop ecosystem which is responsible for storing large data sets of structured or unstructured data across various nodes and thereby maintaining the metadata in the form of log files. 
To use the HDFS commands, first you need to start the Hadoop services using the following command:

#### sbin/start-all.sh

### To check the Hadoop services are up and running use the following command:

#### jps


### General Shell Commands
 - LOCAL FILE SYSTEM
```
ls
mkdir
```
 - Check HBase status
 ```
 status
 ```
 - Check HBase version
 ```
 version
 ```
 - Check HBase user
 ```
 whoami
 ```
- Create a new table
```
create 'table1', 'tablerow', 'tablecol'
```
- Insert values into the table
```
put 'table1', 'tablerow', 'tablecol', 10
put 'table1', 'tablerow', 'tablecol', 15
```
- Drop table
```
disable 'table1'
drop 'table1'
```
