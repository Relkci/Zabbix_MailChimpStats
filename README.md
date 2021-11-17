# Zabbix_MailChimpStats
Zabbix MailChimp Account Status Template using Mailchimp API v3 and Zabbix LLD discovery

# Installation
- Import template
- Create host, add agent interface
- Assign template
- Set inherited macros (API Key, Mailchimp DC Server)

# Features
- Gets all domains
- Gets all lists, counts member statuses of lists, subscribe/unsubscribe metrics, abuse-reports
- Gets all lists'campaignss, counts emails sent
- Trigger on non-auth domains
- Trigger on invalid API auth
- 12 root items

# LLD Discovery
- Domains (4 items per domain, 2 triggers)
- Lists (28 items per list, 7 graphs)

# Screenshots

Basic Triggers
![](images/screenshot1.png)

Dashboard - Main Information - Unique Totals (7 days)
![](images/screenshot2.png)
 
Dashboard - Main Information - Campaign Totals (7 days)
![](images/screnshot3.png)

Dashboard - Detail Information - Campaign Members Protoype (7 days)
![](images/screenshot5.png)

Dashboard - Detail Information - Campaign Change Since Last Send (7 days)
![](images/screenshot4.png)

Custom Dashboard (not in template) - Abuse Complaints
![](images/screenshot6.png)

Custom Dashboard (not template) - Members
![](images/screenshot7.png)

# Updates

## November 17 2021
- Added screenshots

# Known Issues
- Does not capture transactional email information
