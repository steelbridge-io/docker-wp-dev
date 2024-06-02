# A Docker Development Environment For WordPress

For wp-cli, here's the alias I use so I don't have to write `docker-compose run --rm wpcli <command>`:

`alias wp="docker-compose run --rm wpcli"`

Add the above to your .bashrc or .bash_profile or .zshrc, maybe .profile. All depends on how you run shell or the system you are running.

I have added the following so this Docker can run on M1 MacBook

` platform: linux/amd64`

Find and comment out if you are not running a Mac on an "ARM" chip.