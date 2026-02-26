Security policy
===============

This security policy applies to all my repositories.

If you find a [security vulnerability](https://www.cve.org/ResourcesSupport/Glossary#glossaryVulnerability), **do not send it in a GitHub Issue, Pull Request or Discussions**. Instead, use one of the following methods you trust to *privately* send a vulnerability report:

- The "Report a vulnerability" button at "h<span></span>ttps://github.com/studyingegret/[project name]/security" or "h<span></span>ttps://github.com/studyingegret/[project name]/security/advisories"
- My email a3times7@outlook.com

If possible, encrypt your vulnerability report and its attachments with my [public key](https://github.com/studyingegret/.github/blob/main/studyingegret_public_key.asc) (fingerprint: `616B 6582 EBBD 9033 1485 8A74 ABD2 0217 5534 598E`). This requires software like GnuPG (and basic knowledge of public key encryption to feel safe about it). Alternative store for the public key: [pastebin](https://pastebin.com/m6HzQmPa)

Your report should include:
- *Environments you have verified the vulnerability in:* Windows 7/Linux/macOS/...; Python version; C compiler version; Which version(s) of the project (specific to a range of commmit hash if possible); ...
- *A proof-of-concept:* Minimal instructions/code that exploits the vulnerability (screen recordings and screenshots will be helpful)
- *A CVSS vector and calculated severity*
- *Impact:* Who is impacted; What damage can be done
- *Current mitigations for users:* How can users using affected versions protect themselves against the vulnerability if they use the software (including if they cannot protect themselves)
- *Recommended fixes (if possible):* How you suggest to fix the vulnerability

A report not containing all of the above *can* be sent but may be less efficient and require replying to my further questions.

Please mark AI-generated parts of the report (including text that is mostly AI-generated and only lightly edited/reordered/trimmed by yourself).*

Expect a response within 14 days. Please note that I may not have the time to fix the vulnerability (apologies!!!) but will try my best effort. If you do not recieve a response in that time, feel free to ping me in the repo via an issue. **Do not disclose any details about the vulnerability other than its calculated severity score**, unless I agree a fix has no hope of being released within 90 days and allow its disclosure. (If you send via email, check that the address is correct.)

\* If you want the highest security, it's better not to ask any AI, except local models, to avoid AI companies using the chat history on their servers

Vulnerabilities in fork repos
-----------------------------
If the repository you are reporting the vulnerability for is a fork, you may also want to check if the same vulnerability is present on the original (forked-from) repo, and submit a report there.

I may forward the vulnerability to the original repo and await their fix if I deem myself to not have the required knowledge.
