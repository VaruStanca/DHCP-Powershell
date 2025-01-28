#set-up a new DHCP scope named it VLAN1
<pre><code>  Add-DhcpServerv4Scope -name "VLAN1" -StartRange 192.168.1.1 -EndRange 192.168.1.254 -SubnetMask 255.255.255.0 -State Active
</code></pre>
