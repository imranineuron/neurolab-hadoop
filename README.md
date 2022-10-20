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
Cp
Mv
rm

```
 -  LISTING ROOT DIRECTORY
 ```
 hadoop fs -ls /

 ```
 - LISTING DEFAULT TO HOME DIRECTORY
 ```
 hadoop fs -ls
 ```
  ```
 hadoop fs -ls /user/hirwuser150430
 ```
 
 - CREATE A DIRECTORY IN HDFS 
 ```
 hadoop fs -mkdir hadoop-test1
 ```
- COPY FROM LOCAL FS TO HDFS
```
hadoop fs -copyFromLocal  /hirw-starterkit/hdfs/commands/dwp-payments-april10.csv hadoop-test1
```
- COPY TO HDFS TO LOCAL FS
```
hadoop fs -copyToLocal hadoop-test1/dwp-payments-april10.csv .
```
```
hadoop fs -ls hadoop-test1
```

- COPY A FILE FROM ONE FOLDER TO ANOTHER
```
hadoop fs -cp hadoop-test1/dwp-payments-april10.csv hadoop-test2
```
