# Bandwidth Limit Enforcement for SCIONLab
## Abstract
This bachelor thesis project discusses the design, implementation and evaluation of an automated mechanism that enforces an upper bandwidth limit for the SCIONLab network infrastructure.  
The upper bandwidth limits are enforced on SCIONLab’s Attachment Points and hold for both ingress as well as egress traffic between the
AP and the user-AS.  
The backbone of this automated mechanism is implemented in Python, using the TC utility of the iproute2 utility package.  
The effectiveness of the implementation is evaluated using iPerf3, an open-source network performance measurement tool.

## Contributors
Author: Manuel Meinen  
Advisors: Prof. Dr. Adrian Perrig, Matthias Frei

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details

## About SCION/SCIONLab
To learn more about SCIONLab visit:   
https://www.scionlab.org  
To learn more about SCION visit:  
https://www.scion-architecture.net
