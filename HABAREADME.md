
How to call imapcopy.py
-----------------------

Argument order is:`
 Source SourceUSER+PASS
 Dest   DestUSER+PASS
 Sourcebox1
 Destbox1
 Sourcebox2
 Destbox2`

imap-proxy-for-imaplib calls imtest

Example
-------

``` bash

python3 imapcopy.py -c \
 $PWD'/imap-proxy-for-imaplib jaja.besserwisser.org' DUMMYuser:DUMMYpass \
 webmail.kth.se:993 'ug.kth.se/haba/csc-pdc-haba-expug:HEMLIGT' \
 INBOX.apple \
 INBOX/apple4
 
```
(must be absolute path to proxy)


Command line options added
--------------------------

* --datesub [ yearnumber | ALL] 

called with yearnumber all messages will end up in subfolder FOLDER.yearnumber. With "ALL" it will sort all messages into their appropriate year numbered sub folders


 
