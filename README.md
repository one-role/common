# Common role

Role used for all machines in the new infrastructure.

This role does:

- Set a login `issue` file
- Add local users
- Install packages for all machines
- Install Python pips for all machines
- Deploy the `/etc/hosts` file
- Deploy the `/etc/resolv.conf` file
- Create the users skeleton directory
- Configure SELinux setting
