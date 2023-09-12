
Step-1: First download ActiveMQ Artemis ZIP from link:- https://activemq.apache.org/components/artemis/download/

Step-2: Create artemis broker as
        - Go to ...\apache-artemis-2.30.0-bin\apache-artemis-2.30.0\bin folder and open cmd.
        - ...\apache-artemis-2.30.0-bin\apache-artemis-2.30.0\bin> artemis create <BrokerName> [Syntax]
          ...\apache-artemis-2.30.0-bin\apache-artemis-2.30.0\bin> artemis create learningMq
       
 O/P:-

Warning: JAVA_HOME environment variable is not set.

Creating ActiveMQ Artemis instance at: D:\JavaProject\ACTIVEMQ\apache-artemis-2.30.0-bin\apache-artemis-2.30.0\bin\learningMq

--user:
What is the default username?
admin

--password: is mandatory with this configuration:
What is the default password?


--allow-anonymous | --require-login:
Allow anonymous access?, valid values are Y, N, True, False
Y

Auto tuning journal ...
done! Your system can make 1.2 writes per millisecond, your journal-buffer-timeout will be 832000

You can now start the broker by executing:

   "D:\JavaProject\ACTIVEMQ\apache-artemis-2.30.0-bin\apache-artemis-2.30.0\bin\learningMq\bin\artemis" run

Or you can setup the broker as Windows service and run it in the background:

   "D:\JavaProject\ACTIVEMQ\apache-artemis-2.30.0-bin\apache-artemis-2.30.0\bin\learningMq\bin\artemis-service.exe" install
   "D:\JavaProject\ACTIVEMQ\apache-artemis-2.30.0-bin\apache-artemis-2.30.0\bin\learningMq\bin\artemis-service.exe" start

   To stop the windows service:
      "D:\JavaProject\ACTIVEMQ\apache-artemis-2.30.0-bin\apache-artemis-2.30.0\bin\learningMq\bin\artemis-service.exe" stop

   To uninstall the windows service
      "D:\JavaProject\ACTIVEMQ\apache-artemis-2.30.0-bin\apache-artemis-2.30.0\bin\learningMq\bin\artemis-service.exe" uninstall



Step-3: To start apache artemis (ActiveMQ), go to Broker created folder(learningMq)-> bin folder
        like \apache-artemis-2.30.0-bin\apache-artemis-2.30.0\bin\learningMq\bin 
        Then type artemis run there as:  \apache-artemis-2.30.0-bin\apache-artemis-2.30.0\bin\learningMq\bin> artemis run

Step-4: To view artemis console, http://localhost:8161/console/

        To login use username: admin and password: admin

Step-5: Then after run Producer application to send msg to active MQ and Finally run Consumer Application to consume msg

Note: youtube link as below

https://www.youtube.com/watch?v=S7TJUQ3pNko
https://www.youtube.com/watch?v=9fG5SEaGGEU
https://www.youtube.com/watch?v=exT-cswm248&list=TLPQMTIwOTIwMjOqgVngXRcKnQ&index=4
https://www.youtube.com/watch?v=CunlYbnN3k4
