# Start xampp <br>
$ sudo /opt/lampp/xampp start
# Restart xampp <br>
$ sudo /opt/lampp/xampp restart

# To start Apache 2 on Ubuntu Linux LTS 16.04 LTS or the latest systemd based Ubuntu Linux, type:
$ sudo systemctl start apache2.service

# To stop Apache 2 on Ubuntu Linux LTS 16.04 LTS or the latest systemd based Ubuntu Linux, type:
$ sudo systemctl stop apache2.service

# To restart Apache 2 on Ubuntu Linux LTS 16.04 LTS or the latest systemd based Ubuntu Linux, type:
$ sudo systemctl restart apache2.service

# To status of start/restart/stop operation, enter:
$ journalctl -u apache2

# To find out whether Apache 2 running or not, enter:
$ sudo systemctl status apache2.service
