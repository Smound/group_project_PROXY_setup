# Proxy server setup (Agile course - Group 3)

## How to

1. Clone this repo and `cd` into it
2. `vagrant up`
3. `vagrant ssh`, and then in the VM:
4. `sudoedi /etc/squid/conf.d/debian.conf`
5. Uncomment the last line  (`http_access allow localnet`)
6. `systemctl reload-or-restart squid.service`

Now you have a working proxy server running on port 3128.
