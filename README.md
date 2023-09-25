# tcpip 

The goal of this project is to implement the ubiqutous TCP protocol. In particular, this project is attempting to follow RFC 793 - https://datatracker.ietf.org/doc/html/rfc793 
which describes the original protocol, with the goal of being able to set up and tear down a connection with a "real" TCP stack at the other end (netcat in particular) 

This project attempts to do this by writing it in using a user-space networking interface (see https://www.kernel.org/doc/Documentation/networking/tuntap.txt and the Rust bindigs at https://docs.rs/tun-tap/latest/tun_tap/) 
