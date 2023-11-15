# Multithreaded web server by Romain DUHR based on the course by Xavier REDON and Thomas VANTROYS

## Project Description

The project's objective is to create a multithreaded web server called 'sioux.' The server will allow clients to receive a web page. Clients will be able to respond to a vote, and the vote responses will be recorded in a CSV file

## Compilation linux

To compile the project:
```
make
```

To launch the server:
```
cd Sioux
sudo ./sioux
```
or if you want to use a port other than 80
```
cd Sioux
sudo ./sioux [-p | --port PORTNUMBER]
```
