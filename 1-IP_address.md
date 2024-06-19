# IP Addresses

An IP address (Internet Protocol address) is a unique numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. 

### Uses of IP Addresses

- **Routing**: IP addresses enable data packets to be forwarded across networks to reach their destination.

- **Device Identification**: Unique IP addresses allow devices to be identified on a network.

- **Location Tracking**: IP addresses can be used to determine the geographical location of a device.
- Ranges from `0.0.0.0`  to `255.255.255`


### IP Address Structure

An IP address consists of two parts:

- **Network ID**: Identifies the specific network where the device is located.
- **Host ID**: Identifies a specific device within that network.

The division between the Network ID and Host ID varies depending on the subnet mask used.

![](https://static.javatpoint.com/androidpages/images/ip-address-format-and-table.png)

## Types of IP Addresses

### IPv4 vs. IPv6

- **IPv4**:  
    - Introduced in 1981, it uses 32 bits to represent an IP address, allowing for approximately 4.3 billion unique addresses. 
    - The format for IPv4 is `xxx.xxx.xxx.xxx`, where each `x` can be a value from 0 to 255.

    - `bit ` --->  "binary digit," is the smallest unit of data in computing. It represents a binary value, either 0 or 1, 
  
- **IPv6**: 
    - Developed to deal with the long-anticipated shortage of IPv4 addresses. - It uses 128 bits, allowing for a vastly larger number of unique addresses (`2^128`). The format is `xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx`.

## IP Address Classes
### Class A

- **Range**: 1.0.0.0 - 126.255.255.255
- **Subnet Mask**: 255.0.0.0
- **Use**: Suitable for organizations needing a large number of hosts.


### Class B

- **Range**: 128.0.0.0 - 191.255.255.255
- **Subnet Mask**: 255.255.0.0
- **Use**: Medium-sized networks.


### Class C

- **Range**: 192.0.0.0 - 223.255.255.255
- **Subnet Mask**: 255.255.255.0
- **Use**: Small networks.

### Class D

- **Range**: 224.0.0.0 - 239.255.255.255
- **Use**: Multicasting (group communication).
- **Note**: No subnet mask.

### Class E

- **Range**: 240.0.0.0 - 255.255.255.255
- **Use**: Reserved for future use, research, and experimentation.
- **Note**: No subnet mask.

<u>Ip range 127 .0.0.0 - 127.255.255.255 is called LOOP BACK ADDRESS means the machine can talk itself ex : `localhost` </u>

![](https://www.practicalnetworking.net/wp-content/uploads/2019/11/ip-address-classes.png)

## Public vs Private IP Addresses

- Private IP addresses are used inside private networks and are not routable on the public Internet. 
- They allow devices within a private network to communicate with each other efficiently. 

There are three ranges of IPv4 addresses designated for private use:

- **10.0.0.0 - 10.255.255.255**
- **172.16.0.0 - 172.31.255.255**
- **192.168.0.0 - 192.168.255.255**

These ranges are defined by Classless Inter-Domain Routing (CIDR) blocks.

![](https://academy.avast.com/hs-fs/hubfs/New_Avast_Academy/Public%20vs.%20local%20IP%20addresses%20(Academy)/Public-vs-Private-IP-Addresses-01-EN.png?width=1111&name=Public-vs-Private-IP-Addresses-01-EN.png)



## CIDR Notation

CIDR notation simplifies the representation of IP addresses and their associated routing prefix. The notation is expressed as `IP address/prefix length`. For example, `192.168.1.1/24` indicates that the first 24 bits of the IP address are the network portion.

<img src="https://images.ctfassets.net/aoyx73g9h2pg/5dAlax6oR8HC5Lj1i7sw3t/0d295db4ca562e04ea05ea1b29ab32b1/What-is-Proper-CIDR-Notation-Diagram.jpg" alt="Alt Text 1" style="width:45%;margin-right:5%;"> <img src="https://ipv4.global/wp-content/uploads/ipv4/2022/06/CIDR_Chart-1.png" alt="Alt Text 2" style="width:45%;">

![](https://miro.medium.com/v2/resize:fit:1400/1*CsYdOdujY5254ZH_I_1okQ.png)



