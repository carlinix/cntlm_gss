# CNTLM_GSS an unnofficial port to CNTLM.

Fast NTLM authentication proxy with tunneling.

Cntlm is an NTLM / NTLMv2 authenticating HTTP/1.1 proxy. It caches auth'd connections for reuse, offers TCP/IP tunneling (port forwarding) thru parent proxy and much much more. It's in C, very fast and resource-efficient. 

This fork is based on the original CNTLM code (http://cntlm.sf.net/), however it includes extra patches as *kerberos* authentication and fixes on the http stack.


