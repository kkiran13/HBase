# HBase
Stock Analyzer using HBase on Hadoop

Data set used is from NASDAQ containing daily information of stocks over a period of 3 years. 
Task is to find the earning potential of stocks from this data set. 
Stock Volatility is computed for the purpose to forecast the stocks. 
Implemented NoSQL HBase on Hadoop framework to accomplish this task by running on a multiple node HPC.

Can be run locally on Eclipse too by installing Hadoop on the system and passing the input parameters to the Main.java class. 
3 parameters are passed to the Main.Java class: number of nodes(Integer), Input file path, Output file path

Example: 1, /home/inputpath, /home/outputpath

Use jar file to run locally:
Command:$HADOOP_HOME/bin/hadoop jar hbasevol.jar Main.java 1 input_dir output_dir
