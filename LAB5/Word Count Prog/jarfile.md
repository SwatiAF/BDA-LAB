hadoop fs -mkdir /rgs
hadoop@bmscecse-HP-Elite-Tower-600-G9-Desktop-PC:~$ hadoop fs -copyFromLocal Desktop/sample167.txt /rgs/test.txt
hadoop@bmscecse-HP-Elite-Tower-600-G9-Desktop-PC:~$ hadoop jar /home/hduser/Desktop/Jwordcount.jar WCDriver input output
JAR does not exist or is not a normal file: /home/hduser/Desktop/Jwordcount.jar
hadoop@bmscecse-HP-Elite-Tower-600-G9-Desktop-PC:~$ hadoop jar /home/hduser/Desktop/WordCount.jar WCDriver input output
JAR does not exist or is not a normal file: /home/hduser/Desktop/WordCount.jar
