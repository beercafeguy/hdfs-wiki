### HDFS Wiki : Important HDFS commands

##### Get help about HDFS commands<br>
`hadoop fs -help <command name>` <br>
`hadoop fs -help get`
##### Checking block level details of HDFS files
`hdfs fsck <hdfs location> -files -blocks -locations` <br> 
`hdfs fsck /user/hive/warehouse/mydb.db/air_traffic_data -files -blocks -locations` <br>



