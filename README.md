## Oracle Database 12.1.0.2 with ASM on NFS for Puppet >= 4.4

The reference implementation of https://github.com/biemond/biemond-oradb
optimized for linux, solaris

ASM is based on NFS

### Software ( 12.1.0.2 )
- http://www.oracle.com/technetwork/database/enterprise-edition/downloads/database12c-linux-download-2240591.html
- https://updates.oracle.com/download/6880880.html

### Vagrant
Update the vagrant /software share to your local binaries folder

Startup the box
- vagrant up dbasm

Login
- vagrant ssh dbasm

### Accounts
- root password vagrant
- vagrant password vagrant, has sudo rights
- grid password oracle
- oracle password oracle

