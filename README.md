# JMONK

It's pronunced  "__*j monkey*__"  and it stands for *__J__vm __MON__itoring __K__onsole*.
But it can also stands for *__J__boss __MON__itoring __K__onsole*.

It's your choice.

At the moment there are just some ideas. Every information will be represented as graphs (pie, bar etc...).

## What is all about?
What it should do is provide information about:
* System and JVM environment;
* Threads and Connections AJP/HTTP;
* JVM Memory Heap e non-heap memory;
* Contexts and Sessions;
* Datasources;
* JMS;
* Cluster;

And at the very end... all wrapped in a *mobile-app*... an __Android__ one.

### System and JVM environment
In this section you will find usefull information about RAM installed, RAM for the Heap, CPUs, Java version, OS version, Application Server's name/vendor.

### Threads and AJP/HTTP connections
In this section you will find usefull information about numbers of Threads and numbers of AJP and HTTP connections.

### JVM Memory
In this section you will find usefull information about the *Heap* e *non-heap* memory and *PermGem*.

### Contexts and Sessions
In this section you will find usefull information about the deployed applications.

### Datasources
In this section you will find usefull information about the available Datasources and their current connection's.

### JMS;
In this section you will find usefull information about JMS:
* implementation software (ActiveMQ, HornetQ, RabbitMQ, etc...)
* number of messages on queue/topic and number of delivered ones;
* number of consumer on queue (MDB);
* datasources.

### Cluster
In this section you will find usefull information about current view of all active clusters (JMS cluster or AS-cluster).
