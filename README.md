# Installation

* Download the repository
* Update backup_db_config.php with 
** Your database information
** Desired backup locatoin
** How many days you would like to keep old backups (default: 7)
* Either manually run the script or add it to your crontab
** php /path/to/script/db_backup.php

# Acknowledgements  

## Originally created by Dagon Design (www.dagondesign.com).

* MySQL Backup Script v2.1 - May 3, 2007
* For more documentation and new versions, please visit: http://www.dagondesign.com/articles/automatic-mysql-backup-script/
* Much credit goes to Oliver Mueller (oliver@teqneers.de) for contributing additional features, fixes, and testing.

## Updated by Matt McManus (matt@ablegray.com, http://mattmcman.us) - Aug 18th, 2010

* Moved logs to it's own folder
* Added support for log rotation. Set the CLEANUP_AFTER variable to how many days of backup you want to keep
* Removed support for emailing backups. Why would anyone do this?
* Added server hostnames to the log
* Logs can now be emailed everytime to job is run
