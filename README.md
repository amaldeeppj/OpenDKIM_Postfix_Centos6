# OpenDKIM_Postfix_Centos6
Script to configure DKIM for domains with OpenDKIM on a Centos6 postfix server

Reference https://tweenpath.net/install-integrate-dkim-opendkim-postfix-centos-6/

The script will generate DKIM for the domains provided in the list and will configure in the server if not added before. 
The script will not configure OpenDKIM or add the DKIM record to the DNS server. 
Please check the reference for configuring OpenDKIM on CentOS6 Postfix server and add it to the DNS server. 

Try https://github.com/amaldeeppj/Check_MX_NS to get a list of domains using MX and NS as the current server. 
