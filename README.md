# Load-Balancer
This is a simulation of load balancer using round robin algorithm. There are three servers all doing same tasks and a balancer to schedule the task to the servers. Client sends two random number as message to load balancer which schedules the task to one of the server and the server outputs the sum of the two numbers. The connection between two process is done by using sockets and threads.

##Installing the project
Run the following command in the installation directory.
```sh
make
```
This will build the files.
To simulate the project run the following commands, each in different terminals and in the same order.
```sh
make
```
```sh
make
```
```sh
make
```
