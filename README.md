# dantiburl
@tomnomnom's anti-burl with some added functionality

Inspired by TomNomNom's antiburl, This takes URLs on stdin and checks their response status code. 

<b>Usage:</b>
cat urls.txt | dantiburl

<b>Options</B>
-c   Concurrent jobs (default 50)
-q   Quiet mode. output only URLs
-s   Status code to filter for. Can be set multiple times. (Default: <= 300 and >= 500)

