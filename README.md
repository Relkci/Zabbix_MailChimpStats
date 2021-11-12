# Zabbix_MailChimpStats
Zabbix MailChimp Account Status Template

# Installation
- Import template
- Create host, add agent interface
- Assign template
- Set inherited macros (API Key, Mailchimp DC Server)

# Features
- Gets all domains
- Gets all lists, counts member statuses of lists, subscribe/unsubscribe metrics, abuse-reports
- Gets all lists' camapaigns, counts emails sent
- Trigger on non-auth domains
- Trigger on invalid API auth
- 12 root items

# LLD Discovery
- Domains (4 items per domain, 2 triggers)
- Lists (28 items per list, 7 graphs)

