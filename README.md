# beanstalkd-init.d
shell script for beanstalkd run under linux by services start beanstalkd

# usage
copy `beanstalkd` to /etc/init.d/beanstalkd and gives an execute permission by command:
sudo cp beanstalkd /etc/init.d/beanstalkd
chmod +x /etc/init.d/beanstalkd

# run service:
sudo service beanstalkd start

# stop service:
sudo service beanstalkd stop

# restart service:
sudo service beanstalkd restart

# notice:
if your beanstalkd file are not been put at /usr/local/beanstalkd/bin/beanstalkd, plz make a link to your runable file first.
you can find your exec file by running a command:
which beanstalkd
or
locate beanstalkd

normaly it could be set ad /usr/bin or /usr/local/bin, carefuly find out it first.

thx
