# ip

> Show/manipulate routing, devices, policy routing and tunnels.
> Some subcommands such as `ip address` have their own usage documentation.
> More information: <https://www.man7.org/linux/man-pages/man8/ip.8.html>.

- List interfaces with detailed info:

`ip a`

- List interfaces with brief network layer info:

`ip -br address`

- List interfaces with brief link layer info:

`ip -br link`

- Display the routing table:

`ip r`

- Show neighbors (ARP table):

`ip n`

- Make an interface up/down:

`ip link set {{interface}} up/down`

- Add/Delete an IP address to an interface:

`ip a add/del {{ip}}/{{mask}} dev {{interface}}`

- Add a default route:

`ip r add default via {{ip}} dev {{interface}}`

- Flush allinterface's ip

`ip a fl dev enp5s0`
