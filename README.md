Place these scripts in `/etc/sysconfig/network-scripts` on your
RedHat/CentOS/Fedora system.

Sample configuration for setting up a `veth` pair:

    DEVICE=veth0
    DEVICETYPE=veth
    VETH_PEER=veth1
    BRIDGE=br0
    ONBOOT=yes
    NM_CONTROLLED=no

- `VETH_PEER` Set it to anything you want the pair to be name after

 
License
=======

veth-network-scripts
Copyright (C) 2016

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
