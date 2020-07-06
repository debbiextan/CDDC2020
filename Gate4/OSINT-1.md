**(OSINT-1] Funky Transfer Pact**

Given: hint that it uses FTP

Solution:
1. Obtain subdomain of UnduplicitousCorp  
  https://transparencyreport.google.com/https/certificates
2. Entered FTP server by entering URL: *ftp://unduplicitouscorp.tech/*  

FTP Server Contents: UC_name card 1.pptx, UC_name card 2.pptx, UC_name card 3.pptx, and flag.txt  
Note: FTP servers begin with *ftp://* instead of *https://*
  
3. Flag found in *flag.txt*

Flag: CDDC20{@n0nymous_FTW}
