# **ELASTIC IP IN AWS**

### If you want to keep the same public IP for your EC2 instance, even after it being stopped, then the elastic IP is the right choice
Elastic ips can be found at **Network & Security** section. Once you get into it, you need to **allocate** an elastic ip address from Amazon's
pool of IPv4 addresses.
Once the elastic IPv4 is created, you will be owning it, until you pay for its "rental". Each elastic ip address need to be assigned to a specific
instance/network interface. As long as you created, you should assign it to an instance/network interface, because you are charged as soon as the ip is created

___
# **PLACEMENT GROUPS IN AWS**
