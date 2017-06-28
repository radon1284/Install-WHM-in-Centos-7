# Install-WHM-in-Centos-7

Before installing cPanel you must have Perl installed on your server as cPanel is written in Perl. To install Perl on your system, login as root user and run the following command.

```
$ yum -y install perl
```
Now you will need to set the hostname for your server. A hostname is a FQDN or Fully Qualified Domain Name which will be used to identify your server. For example consider vps.mydomain.com - this is a FQDN which you can use as your hostname. To change your hostname run the following command

```
$ hostname vps.mydomain.com
```

You can replace vps.mydomain.com with your hostname. You must own the domain of which your are setting up the hostname.
Next, you will need to change your current directory to /home directory, run the following command to do this.

```
$ cd /home
```

Download the installation script from cPanel website by executing the following command -
```
$ curl -o latest -L https://securedownloads.cpanel.net/latest
```

Now run the installation script by executing the following command -

```
$ sh latest
```
