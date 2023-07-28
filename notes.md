# Some notes 
http -> protocol for internet communication
[overview of back-end](https://youtu.be/XBu54nfzxAQ)

### Useful sites
https://jsonlint.com/


### Request and Response
http request (client) -> (server) 
http response (server) -> (client)



### Clients and Server
Client -> User (Front-end) : ex (YOUTUBE APP)
Server -> (Back-end) : ex (YOUTUBE SERVER) -> Images, Comments

computers can act as server and client at the same time

### Fetch API
It's a set of built-in functions and tools that can be used by JS Code to make HTTP REQUEST
We normally have to wait for the fetch part

### Servers
Servers are always on
Any computer can be a server, but the best servers are special made for serving data

### Web Adresses
IPv4 -> Internet Protocol
255.255.255.255
each section can be a number between 0 and 255

IPV6
section1:section2:section3:section4:section5:section6:section7:section8

DNS -> Domain Name System (Translates IP Adress to Domain Name )
amazon.com : IP

### ICANN
Internet Corporation for Assigned Names and Numbers
pretty straight foward, they publish the ip adresses for each owner

### Subdomain
break up the resources used on a domain name without to actually go buy a new domain name
domainname.com
api.domainname.com 

### URI
Uniform Resource Identifier: is a superset of URL 
Meaning: ALL URL's ARE URI's, BUT NOT ALL URI's ARE URL's

### URL 
URL are not prefixed to HTTP
protocol: http:     (mandatory)
username: testuser  
password: testpass
hostname: testdomain.com  (mandatory)
port: 8080
pathname /testpath
search: ?testsearch=testvalue
hash: #testhash

final url:   http://testuser:testpass@testdomain.com:8080/testpath?testsearch=testvalue#testhash

### Ports
Ports are virtual hubs managed by the OS that allow to segment incoming requests of incoming data streams 


