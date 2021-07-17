# dantiburl
@tomnomnom's anti-burl with some added functionality. No really, It's mostly his work. Thank him.

Inspired by TomNomNom's antiburl. 
This takes URLs on stdin, checks their response status code against a supplied code (or list of codes) and outputs matches. 

# installation
go get -u github.com/raverrr/dantiburl

# Usage:

cat urls.txt | dantiburl


# Options

-c   Concurrent jobs (default 50)

-q   Quiet mode. output only URLs

-s   Status code to filter for. Can be set multiple times. (Default: <= 300 and >= 500)

![alt text](https://i.imgur.com/3K3h6cY.png)
![alt text](https://i.imgur.com/5cHnZ4h.png)
![alt text](https://i.imgur.com/iRphJb5.png)


