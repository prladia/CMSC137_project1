# CMSC137
####Primzen Rowena Ladia
#####2012-19618
#####CMSC 137 CD-2L

#####To run project 1
Check if jdk is installed through the terminal. Type `javac`. If error occurs, type the following on the terminal
```
sudo apt-get update
```
```
sudo apt-get install default-jdk
```
If your permission is being asked, type `Y`. Wait for installation to finish.
After installation, go to directory project1; compile UDPServer.java
~~~
cd project1
javac UDPServer.java
~~~
Open another terminal (let's call the first one terminal A and the second terminal B).
Go to directory project1 on terminal b; compile UDPClient.java on
~~~
cd project1
javac UDPClient.java
~~~
On terminal A, run UDPServer
```
java UDPServer
```
On terminal B, run UDPClient
```
java UDPClient
```
Done.
