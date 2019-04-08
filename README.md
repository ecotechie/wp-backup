# WordPress Backup script
  
## DESCRIPTION

Selectively backup WordPress host depending on option flag used.

## SYNOPSYS

`wp-backup --host <remote host> <flag(s)>`

## FLAGS:

**--help**,		**-h**	Print this help message

**--full**,		**-f**	All of WordPress (minus uploads, cache and other wp-content folders), including database

**--database**,	**-d**	Database

**--plugins**,	**-p**	Plugins

**--themes**,	**-t**	Themes

**--uploads**,	**-u**	Uploads

**--host**,		**-s**	Remote host to backup from. Must both exist in ~/.wpcli/config.yml as an alias && ~/.ssh/config as a Host

**--folder**,	**-f**	Local folder to create back up files onto. If not set, will default to home folder.


![wp-backup](https://github.com/ecotechie/wp-backup/raw/master/Demo-wp-backup.gif "Backing up database and plugins folder")
