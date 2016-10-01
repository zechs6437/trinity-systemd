# trinity-systemd

## Installation
* Modify any paths that need to be changed for your build paths
* Modify the `User=` variable as well
* Copy/Move these files into `/etc/systemd/system`
* Enable the services using `systemctl enable worldserver` and `systemctl enable authserver`
* To start the servers, reboot or use `systemctl start worldserver` and `systemctl start authserver`

## Server Management
* Use `screen -r worldserver` or `screen -r authserver` to manage the worldserver and authserver respectively

## Notes
* You must have `screen` installed on your Linux box to be able to use these services. Installing `screen` on Debian is as easy as doing `apt-get install screen`

## Credits
[velinath](https://github.com/velinath)


> Forked/mirrored from [https://github.com/velinath/trinity-systemd](https://github.com/velinath/trinity-systemd)
