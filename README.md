# SDN LoadBalancer
Module for load balancing within an SDN subnet.

Usage Guide:

1. Download floodlight 1.0.
2. Add the loadbalance module as net.floodlightcontroller.loadbalance in src/main/java
3. Append the following line at the end of the file "src/main/resources/META-INF/services/net.floodlightcontroller.core.module.IFloodlightModule" to register the module:
net.floodlightcontroller.serverloadbalance.AdvancedLoadBalancer
4. Add net.floodlightcontroller.serverloadbalance.AdvancedLoadBalancer to floodlight.modules variable in /src/main/resources/floodlightdefault.properties.
