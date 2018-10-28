---
layout: security.hbs
title: Security
---

# Security

## Reporting a Bug in Node.js

All security bugs in Node.js are taken seriously and should be reported via [HackerOne](https://hackerone.com/nodejs)
or by emailing [security@nodejs.org](mailto:security@nodejs.org). This will be delivered to a subset of the core team
who handle security issues.

Your report will be acknowledged within 24 hours, and you’ll receive a more detailed response to your report within 48
hours indicating the next steps in handling your submission.

After the initial reply to your report, the security team will endeavor to keep you informed of the progress being made
towards a fix and full announcement, and may ask for additional information or guidance surrounding the reported issue.
These updates will be sent at least every five days; in practice, this is more likely to be every 24-48 hours.

### Node.js Bug Bounty Program

The Node.js project engages in an official bug bounty program for security researchers and responsible public disclosures.

The program is managed through the HackerOne platform at [https://hackerone.com/nodejs](https://hackerone.com/nodejs) with further details.

## Reporting a Bug in a third party module

Security bugs in third party modules should be reported to their respective maintainers and should also be coordinated
through the [Node Ecosystem Security Team](https://hackerone.com/nodejs-ecosystem) or by emailing 
[security-ecosystem@nodejs.org](mailto:security-ecosystem@nodejs.org).

Details regarding this process can be found in the [Security Working Group repository](https://github.com/nodejs/security-wg/blob/master/processes/third_party_vuln_process.md).

Thank you for improving the security of Node.js and its ecosystem. Your efforts and responsible disclosure are greatly
appreciated and will be acknowledged.

## Disclosure Policy

Here is the security disclosure policy for Node.js

- The security report is received and is assigned a primary handler. This person will coordinate the fix and release
process. The problem is confirmed and a list of all affected versions is determined. Code is audited to find any
potential similar problems. Fixes are prepared for all releases which are still under maintenance. These fixes are not
committed to the public repository but rather held locally pending the announcement.

- A suggested embargo date for this vulnerability is chosen and a CVE (Common Vulnerabilities and Exposures (CVE®))
is requested for the vulnerability.

- On the embargo date, the Node.js security mailing list is sent a copy of the announcement. The changes are pushed to
the public repository and new builds are deployed to nodejs.org. Within 6 hours of the mailing list being notified, a
copy of the advisory will be published on the Node.js blog.

- Typically the embargo date will be set 72 hours from the time the CVE is issued. However, this may vary depending on
the severity of the bug or difficulty in applying a fix.

- This process can take some time, especially when coordination is required with maintainers of other projects. Every
effort will be made to handle the bug in as timely a manner as possible; however, it’s important that we follow the
release process above to ensure that the disclosure is handled in a consistent manner.


## Receiving Security Updates

Security notifications will be distributed via the following methods.

- [https://groups.google.com/group/nodejs-sec](https://groups.google.com/group/nodejs-sec)
- [https://nodejs.org/en/blog](https://nodejs.org/en/blog)

## Comments on this Policy

If you have suggestions on how this process could be improved please submit a [pull request](https://github.com/nodejs/nodejs.org)
or [file an issue](https://github.com/nodejs/security-wg/issues/new) to discuss.