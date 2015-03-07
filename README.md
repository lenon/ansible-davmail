# davmail-ansible

Suppose that you work for a company that uses Outlook as their email solution.
If you want to sync this email account with another client (like Gmail or
Fastmail), you can do it using POP3. But if the POP3 access is disabled, you're
almost out of luck. Unless if you use something like _DavMail_.

> DavMail is a POP/IMAP/SMTP/Caldav/Carddav/LDAP exchange gateway allowing users
> to use any mail/calendar client (e.g. Thunderbird with Lightning or Apple
> iCal) with an Exchange server.

This repo is an Ansible playbook that installs DavMail on a VPS (in my case a
server running FreeBSD), creating a POP3, SMTP and CalDAV proxy for any
Outlook/Exchange-based solution.
