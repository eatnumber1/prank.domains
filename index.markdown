---
layout: default
---
## What

{{ site.title }} is an [OpenDNS] style open DNS resolver which hijacks
[NXDOMAIN] responses instead returning prank websites.

You can play pranks on your friends by setting their DNS server to
{{ site.title }}. Then whenever they try to go to a domain that doesn't exist,
they'll instead arrive at a suitable prank website.

## Where

The websites currently served by {{ site.title }} are:

 * [Leekspin]
 * [Chicken on a Raft][ChickenOnARaft]
 * [Zombo Com][ZomboCom]

Also see the [NSFW version][spin.wang]!

## How

Just configure your friend's DNS server to the following addresses:

|---------------+--------------------|
|      IPv4     |        IPv6        |
|:-------------:|:------------------:|
| 50.116.13.220 | 2600:3c01::31:d00e |
| 129.21.49.55  |                    |
|---------------+--------------------|

For convenience, the domain `ns.{{ site.domain }}` points at these addresses.

## Contribute

I'm [@eatnumber1] and I'd love to hear what you think, especially if you have
suggestions for additional suitable prank websites to add to the rotation.

[OpenDNS]: http://opendns.com
[Leekspin]: http://leekspin.com
[ChickenOnARaft]: http://chickenonaraft.com
[spin.wang]: http://spin.wang
[@eatnumber1]: http://rus.har.mn
[NXDOMAIN]: http://www.dnsknowledge.com/whatis/nxdomain-non-existent-domain-2/
[ZomboCom]: http://zombo.com
