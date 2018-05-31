# node-red-mongodb-backups-to-email
This flow backs up your mongodb using mongodump, to an archive, and then attempts to email the file 


README in FLOW:

This flow will create a mongodb backup of all your
databases and attempt to email them to an email.

Adjust the CREDENTIALS node to customize 
your outgoing email info etc...

Adjust the Timestamp Iinject node to create incremental backups if you want, or
trigger the flow how you want...

