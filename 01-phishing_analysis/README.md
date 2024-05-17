# Phising

I will analyze the following email files to find out who sent them and the purpose.

- email_1.eml
- email_2.eml
- email_3.eml
- email_4.eml
- email_5.eml

I will use the following programs for the WINDOWS operating system to see the RAW content of *.EML files:

- Total commander
- notepad
- SysTools EML Viewer Tool

### SysTools EML Viewer Tool

This program displays all the details of an email file and is very good for advanced analysis. It is free and can be downloaded from:

```
https://www.systoolsgroup.com/eml-viewer.html
```

I load the 5 *.EML files, the details can be seen in the following image

![image-1 SysTools EML Viewer Tool ](assets\1.jpg)

### email_1.eml

From : service[@]paypal[.]be

return path : service[@]paypal[.]be

to: "John Doe" <becode[@]phishing-me[.]be>

subject: Reçu pour votre paiement à Spotify AB

date sent: 20/03/2023 15:57:04

sender IP:  66.211.170.87


https://www.whois.com/whois/66.211.170.87

```
#
# ARIN WHOIS data and services are subject to the Terms of Use
# available at: https://www.arin.net/resources/registry/whois/tou/
#
# If you see inaccuracies in the results, please report at
# https://www.arin.net/resources/registry/whois/inaccuracy_reporting/
#
# Copyright 1997-2024, American Registry for Internet Numbers, Ltd.
#


NetRange:       66.211.168.0 - 66.211.171.255
CIDR:           66.211.168.0/22
NetName:        PAYPAL-SITE
NetHandle:      NET-66-211-168-0-1
Parent:         NET66 (NET-66-0-0-0-0)
NetType:        Direct Allocation
OriginAS:       AS17012
Organization:   PayPal, Inc. (PAYPAL)
RegDate:        2006-01-25
Updated:        2021-12-14
Ref:            https://rdap.arin.net/registry/ip/66.211.168.0


OrgName:        PayPal, Inc.
OrgId:          PAYPAL
Address:        2211 N. First St.
City:           San Jose
StateProv:      CA
PostalCode:     95131
Country:        US
RegDate:        2001-08-17
Updated:        2019-04-10
Ref:            https://rdap.arin.net/registry/entity/PAYPAL


OrgAbuseHandle: NETWO8902-ARIN
OrgAbuseName:   Network Abuse
OrgAbusePhone:  +1-480-967-5100 
OrgAbuseEmail:  email@paypal.com
OrgAbuseRef:    https://rdap.arin.net/registry/entity/NETWO8902-ARIN

OrgTechHandle: PAYPA-ARIN
OrgTechName:   PayPal Network
OrgTechPhone:  +1-408-967-5100 
OrgTechEmail:  email@paypal.com
OrgTechRef:    https://rdap.arin.net/registry/entity/PAYPA-ARIN

RNOCHandle: PAYPA1-ARIN
RNOCName:   PayPal
RNOCPhone:  +1-480-967-5100 
RNOCEmail:  email@paypal.com
RNOCRef:    https://rdap.arin.net/registry/entity/PAYPA1-ARIN

RTechHandle: PAYPA1-ARIN
RTechName:   PayPal
RTechPhone:  +1-480-967-5100 
RTechEmail:  email@paypal.com
RTechRef:    https://rdap.arin.net/registry/entity/PAYPA1-ARIN

RAbuseHandle: NETWO8902-ARIN
RAbuseName:   Network Abuse
RAbusePhone:  +1-480-967-5100 
RAbuseEmail:  email@paypal.com
RAbuseRef:    https://rdap.arin.net/registry/entity/NETWO8902-ARIN


#
# ARIN WHOIS data and services are subject to the Terms of Use
# available at: https://www.arin.net/resources/registry/whois/tou/
#
# If you see inaccuracies in the results, please report at
# https://www.arin.net/resources/registry/whois/inaccuracy_reporting/
#
# Copyright 1997-2024, American Registry for Internet Numbers, Ltd.
#

```

After analyzing this file, I came to the conclusion that it is sent by paypal.com. All the details, including the IP address, show that it is a clean email.




### email_2.eml

### email_3.eml

### email_4.eml

### email_5.eml