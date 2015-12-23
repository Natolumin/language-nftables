#Language-NFTables#

An atom language support package for the nftables configuration syntax

#TODO#

* Many identifiers are still missing

#Known Bugs#

* Most of the section-type definitions don't match properly when on only one line eg:
```nft
add set filter blackhole6 { type ipv6_addr; elements={::1/128}};
```
