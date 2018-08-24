# apache-struts2 CVE-2017-5638, CVE-2017-9791
Demo Application and Exploit

Sample Apache Struts2 App 

Struts2-showcase: https://mvnrepository.com/artifact/org.apache.struts/struts2-showcase/2.3.12

Exploit Reference: https://github.com/rapid7/metasploit-framework/issues/8064


---------------------------------

## Extending for CVE-2017-9791 (notes from hook);

resource;
http://pentestit.com/apache-struts2-showcase-remote-code-execution-s2-048/

bit of confusion when I found the original exploit_S2-048.py in the source upon first commit, but still publishing this as it reintroduces windows' platform check in the payload.

thanks to piesecurity for providing the Dockerfile for setting up the lab

## PoC now available for CVE-2018-11776;
https://github.com/hook-s3c/CVE-2018-11776-Python-PoC
