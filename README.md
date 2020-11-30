# Coding-Contest
Write a stand-alone application (in Python3), to set the MAC Address of the netplan file(s) as per the current device interface's MAC address.

Test Environment:
This test has to be run on a Ubuntu 18.04 Virtualbox with
 3 intf: 0000:00:03.0, 0000:00:08.0 and 0000:00:09.0

Currently there is a sample netplan file that can be used for testing purpose. First take a backup of your /etc/netplan/<netplan.yaml> file, before copying this sample file. Your code must be able to handle different types of netplan files, as below:
- Basic netplan with all interfaces
- Multiple netplan files for different interfaces
- With and without metrics configuration in netplan
- Netplan with combination of static and as dhcp interfaces
- Default routes configuration in netplan

Once the netplan file(s) MAC address has been changed, apply the netplan to check if the correct mac address is reflected by the system.

Your code has to be well documented with necessary tests to support your code.

To participate in this coding contest: Clone this repo, create your own branch, after commiting your changes to the branch, raise a Pull Request to the master branch.
PLEASE DO NOT COMMIT YOUR CHANGES TO MASTER BRANCH.

Good Luck! Get Coding!
And most important do not forget to have fun while you code :)
