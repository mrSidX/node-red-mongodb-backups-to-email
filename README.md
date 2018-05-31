# node-red-mongodb-backups-to-email
This flow backs up your mongodb using mongodump, to an archive, and then attempts to email the file 


README in FLOW:

This flow will create a mongodb backup of all your
databases and attempt to email them to an email.

Adjust the CREDENTIALS node to customize 
your outgoing email info etc...

Adjust the Timestamp Iinject node to create incremental backups if you want, or
trigger the flow how you want...

Be sure to update the exec node config directly to update
the archive file location. This doesn't work
when value stored as flow.set and appended to 
exec. So for now, just enter location in exec node.


