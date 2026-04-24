# Traffic-monitoring-SDN-
# Traffic Monitoring and Statistics Collector (SDN)

## Project Overview

This project demonstrates traffic monitoring in a Software Defined Network using Mininet and Open vSwitch.

## Objective

To collect and display flow statistics such as packet count and byte count.

## Tools Used

* Mininet
* Open vSwitch
* Ubuntu

## Steps to Execute

1. Start Mininet:
   sudo mn --topo single,3

2. Generate traffic:
   mininet> h1 ping h2

3. Stop ping:
   Ctrl + C

4. Get statistics:
   sudo ovs-ofctl dump-flows s1

## Output

Example:
n_packets=86, n_bytes=7688

## Conclusion

Traffic statistics were successfully monitored using Open vSwitch.
