# smb-ldap-commands
useful SMB, LDAP commands to manage users and groups

## Add and user in the LDAP database

-a: create a samba and UNIX account
-P: invoke smbldap-passwd, to change the password
`smbldap-useradd -a -P <user>`
