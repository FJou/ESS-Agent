# ESS-Agent
Agent builder source code for monitoring ESS system

Description:

IBM Elastic Storage Server (ESS) is a modern implementation of software-defined storage, combining IBM Spectrum Scale software with IBM POWER8® processor-based I/O-intensive servers and dual-ported storage enclosures. This package includes a monitoring agent to monitor IBM ESS.  It was developed and tested with ESS versions 5.0.4 and 6.0.0, but the agent should work with other versions of ESS.  

The agent runs shell scripts with curl quires to pull performance data from the ESS management node.  The agent provides detailed statistics of ESS performance at node, pool, and disk levels.  It also monitors NFS and SMB operations where applicable.  

This solution is unsupported.  However, if you need assistance, send an email to Frank Jou at yfrankjou@ibm.com. 
