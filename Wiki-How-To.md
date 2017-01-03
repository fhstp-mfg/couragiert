#Wiki & How-To

###Here all necessary informations can be collected for deploying the website or maintain it.

**Duplicator**
The following paths should be excluded from the creation of the archive .zip and installer.php
`
/home/.sites/78/site4235691/web/_dev/wp-content/backupwordpress-7d8e8ee058-backups;
/home/.sites/78/site4235691/web/_dev/wp-content/backups;
/home/.sites/78/site4235691/web/_dev/wp-content/backup-db;
/home/.sites/78/site4235691/web/_dev/wp-content/cache;
`

Also always uncomment the .htaccess file in the wp-snapshots folder after building the archive, in order to make the download of the files possible.
