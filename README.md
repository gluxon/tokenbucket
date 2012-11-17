Token Bucket
============

What is this?
-------------
This is an implementation (or port) of the Token Bucket Algorithm in PHP. It is a copy of the Python implementation from [ActiveState Code](http://code.activestate.com/recipes/511490-implementation-of-the-token-bucket-algorithm/), which is license in PSF

What is the Token Bucket Algorithm?
-----------------------------------
From: [Wikipedia](http://en.wikipedia.org/wiki/Token_bucket#The_token_bucket_algorithm)

>The token bucket is an algorithm used in packet switched computer networks and telecommunications networks to check that data transmissions conform to defined limits on bandwidth and burstiness (a measure of the unevenness or variations in the traffic flow).

>The token bucket algorithm is based on an analogy of a fixed capacity bucket into which tokens, normally representing a unit of bytes or a single packet of predetermined size, are added at a fixed rate. When a packet is to be checked for conformance to the defined limits, the bucket is inspected to see if it contains sufficient tokens at that time. If so, the appropriate number of tokens, e.g. equivalent to the length of the packet in bytes, are removed ("cashed in"), and the packet is passed, e.g., for transmission. If there are insufficient tokens in the bucket the packet does not conform and the contents of the bucket are not changed.

License
-------
Under the same code terms as the original, this is licensed PSF.

[http://docs.python.org/2/license.html](http://docs.python.org/2/license.html)
[http://en.wikipedia.org/wiki/Python_Software_Foundation_License](http://en.wikipedia.org/wiki/Python_Software_Foundation_License)
