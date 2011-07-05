## Installation

    git clone git://github.com/fnichol/mysql_backup.git /opt/mysql_backup
    export PATH="$PATH:/opt/mysql_backup/bin"

## Usage

    mkdir -p /var/backups/mysql
    mysql_backup --destination /var/backups/mysql app1_prod app1_dev
