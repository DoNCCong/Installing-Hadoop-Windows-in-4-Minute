# Installing Hadoop Windows in 4 Minute
Link Dowload: 
(I create a video, you must watch it to understant)
# 1. Extracting the file rar in C Drive(Important!).

# 2. Copy the path "C:\Hadoop_Window\hadoop-3.3.6\bin" in path variable

# 3. Type the command:

hadoop version
hadoop namenode -format -clusterId XXXXXXXXX (You must copy the value to replace XXXXXXXXX)
hadoop datanode -format -clusterId XXXXXXXXX (You must copy the value to replace XXXXXXXXX)

# 4. Open the "sbin" folder:

start-all.cmd
stop-all.cmd

![Video_Youtube](https://youtu.be/DMu42Bk5i0k)
