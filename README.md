<p align=center>
  <ins>Overview of Concepts</ins>
</p>

Domain Name System
  *  resolves human-readable address (i.e., www.example.com) to Internet Protocol (IP) addresses which computers use to identify each other
      *  A records point hostnames to IPv4 addresses
      *  AAAA records point hostnames to IPv6 addresses
      *  PTR records point IP addresses to hostnames; reverse lookup
      *  X records establish server(s) responsible for handling email messaging for domains
      *  CNAME records establish aliases, or canonical names, for domains wanting to resolve to different hostnames bound to the same IP address
      * TXT records store information bound to a domain, also used to establish email authentication via SPF and DKIM
      *  Authoritative DNS servers hold master records of domains for which it is responsible
      *  Non-authoritative DNS servers hold read-only copies of master domain records, caching records from authoritative DNS servers and forwarding DNS queries on behalf of clients
  
Access Control Lists
  *  network control measures that utilize parameters (IP addresses, port numbers) to grant or deny access to system devices, files, and resources
  *  used to establish least privilege, users being granted access only to resources necessary for completion of their role tasks
      *  file system ACLs establish permissions within an operating system for users to access files
      *  network system ACLs establish permissions for users to access networks or subnetworks, similar to a firewall
      *  standard ACLs deny or grant access via source IP addresses, usually placed closer to destination systems/resources
      *  extended ACLs deny or grant access via a more granular statement of source and destination IP addresses and port numbers, usually placed closer to source system/resource
  
<p align=center>
  <ins>Banking Network Topology</ins>
</p>
<p align=center>
  <img src="https://github.com/Fehral/networkprojectv6/blob/main/networkprojectv6topology.png?raw=true">
</p>

###### Configuration files and address mapping for each device will be uploaded within the repository.
