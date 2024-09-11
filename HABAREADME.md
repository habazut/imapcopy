
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
 './imap-proxy-for-imaplib jaja.besserwisser.org' DUMMYuser:DUMMYpass \
 webmail.kth.se:993 'ug.kth.se/haba/csc-pdc-haba-expug:HEMLIGT' \
 INBOX.apple \
 INBOX/apple4
 
```
 
