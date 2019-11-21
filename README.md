# WordPress Backup script

## DESCRIPTION

Selectively backup WordPress host depending on option flag used.

## SYNOPSYS

`wp-backup --host <remote host> <flag(s)>`

## FLAGS:

**--help**,				Print this help message

**--full**,		**-f**	All of WordPress (minus uploads, cache and other wp-content directories), including database

**--database**,	**-d**	Database

**--plugins**,	**-p**	Plugins

**--themes**,	**-t**	Themes

**--uploads**,	**-u**	Uploads

**--host**,		**-h**	Remote host to backup from. Must both exist in ~/.wpcli/config.yml as an alias && ~/.ssh/config as a Host

**--directory**,	**-d**	Local directory to create back up files onto. If not set, will default to home directory.


![wp-backup](https://github.com/ecotechie/wp-backup/raw/master/Demo-wp-backup.gif "Backing up database and plugins directory")
