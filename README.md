# bigbank

## PHP 7.2 on CentOS 7 ##
```
yum update -y
yum install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
yum install -y http://rpms.remirepo.net/enterprise/remi-release-7.rpm
yum install -y yum-utils git
yum-config-manager --enable remi-php72
yum install -y php php-mcrypt php-cli php-gd php-curl php-mysql php-ldap php-zip php-fileinfo
systemctl start httpd.service
```

## Bigbank ##
```
cd /var/www/html
git clone https://github.com/cmadera/bigbank.git
git clone https://github.com/cmadera/monitor.git
cp monitor/monitor.php .
mv bigbank/home/ .
mv bigbank/index.php .
rm -rf bigbank/
```
