# WordPress Plugin PoCs

WordPress Plugin PoCs based on 1-Day WordPress Plugin Vulnerability



## :warning: Legal Disclaimer - Use At Your Own Risk :warning:

This project is made for EDUCATIONAL and ETHICAL TESTING purposes ONLY. Using of source code in this repository for attacking targets without prior mutual consent is ILLEGAL. 

I take **NO** responsibility and/or liability for how you choose to use any of information including source code in this repository. By accessing and using any of files in this repository, you AGREE TO USE AT YOUR OWN RISK. Once again, ALL files available here are for EDUCATIONAL and ETHICAL TESTING purposes ONLY.

## List of PoCs

> All PoCs are written in Python 3.6.8

- [WP GDPR Compliance 1.4.2](./PoCs/gdpr-compliance)
  - Vulnerability Type: Remote Code Execution
  - Vulnerable Version: WP GDPR Compliance 1.4.2 or Lower
  - Dependency: [Mailhog](https://github.com/mailhog/MailHog)
  - References:
    - [WordPress WP GDPR Compliance Plugin Privilege Escalation (Rapid7/Metasploit)](https://www.rapid7.com/db/modules/auxiliary/admin/http/wp_gdpr_compliance_privesc)
    - [CVE-2018-19207 (CVE Details)](https://www.cvedetails.com/cve/cve-2018-19207)
- [Audio Record 1.0](./PoCs/audio-record/exploit.py)
  - Vulnerability Type: Arbitrary File Upload
  - Vulnerable Version: Audio Record 1.0 or Lower
  - References
    - [WordPress Plugin Audio Record 1.0 - Arbitrary File Upload (ExploitDB)](https://www.exploit-db.com/exploits/46055)

- [WeChat Broadcast 1.2.0](./PoCs/wechat-broadcast)
  - Vulnerability Type: Local File Inclusion
  - Vulnerable Version: WeChat Broadcast 1.2.0 or Lower
  - References
    - [CVE-2018-16283 (CVE Details)](https://www.cvedetails.com/cve/CVE-2018-16283/)
    - [WordPress Plugin Wechat Broadcast 1.2.0 - Local File Inclusion (ExploitDB)](https://www.exploit-db.com/exploits/45438)