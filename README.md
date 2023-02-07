<h1>H3 Attaaack </h3>

<h2>x) Read and summarize</h2>

<h3>ATT&CK Framework</h3>

- Model for studying activities that a threat actor is cabale of doing to infiltrate and oparate inside an enterprise environment.

- The framework provides a common taxonomy for the cybersecurity community to describe adversary behaviors. It's useful for people researching both the defensive side and the offensive side.

- The framework can be expanded to tailor to users needs.

<h3>Tactics, techniques, sub-techniques, and procedures</h3>

the 14 tactics that are used to encompass different sets of techniques:

- Reconnaissance - Gathering as much information as possible about the victim(s) of the adversary's operations

- Resource Development - Evaluating the resources employed by the adversy

- Initial Access - Assessing how the threat actor gets their first step into the victim's environment

- Execution - Threat actor runs malicious code inside the victim's environment to do harm

- Persistence - The ability for the threat actor to keep operating eventhough actions have been taken against them (reboots etc)

- Privilege Escalation - First access can happen through an unprivileged account and the access level needs to be changed in order to continue

- Defense Evasion - Actions taken to stay undetected in the victim's environment

- Credential Access - Stealing legitimate user credentials in order to gain access, create more account, disguise malicious activity etc.

- Lateral Movement - Discovering how network(s) and system(s) are configured to pivot systems in order to reach end target

- Collection - Gathering information from victim's environment in order to exfiltrate it later

- Command and Control - All techniques involving the threat actor communicating with the systems under its control

- Exfiltration - Exfiltrating information while trying to remain undetected (includes for example encryption)

- Impact - All attempts to prevent the victim from accessing his/her system

All of these tactics are made up of many techniques and sub-techniques.

The procedure is the specific way in which a threat actor implements a specific technique or sub-technique. One procedure can cover multiple techniques and sub-techniques.

<h3>The ATT&CK Matrix</h3>

- A representation of all of the tactics, their techniques and sub-techniques

- Aids in identifying the behaviours that are the sources of interest

<h3>The ATT&CK Navigator</h3>

- A tool for visualizing a threat actor's modus operandi, the behavior of a specific tool, or to generate a security exercise.

- Allows for creating and combining multiple layers in order to study the relation between tools or threat actor.

<h3>Mapping with ATT&CK</h3>

- Formbook is an infostealer that is cabable of retrieving authorization and login credentials from a web data form before the information reaches a secure server, bypassing HTTPS encryption.

- Formbook is a form-grabbing software, cabable of being effective even if the victim for example auto-fills or copy and pastes the information.

Based on this information Formbook can be organized into the following ATT&CK tactics:

1. Steal authorization and login credentials: Credential Access
2. Keylog information even if victims use a virtual keyboard, auto-fill, or if they copy and paste: Collection
3. Take screenshots: Collection

<h4>Information about exercise</h4>

- Based on a paper that has been presented at Virus Bulletin 2018: Inside Formbook Infostealer by the malware researcher Gabriela Nicolao.

<h2>Source</h2>

https://learning.oreilly.com/library/view/practical-threat-intelligence/9781838556372/B13376_04_Final_SK_ePub.xhtml#_idParaDest-74

https://www.virusbulletin.com/uploads/pdf/magazine/2018/VB2018-Nicolao.pdf

<h2>Mitre Att&ck</h2>

- Mitre Att&ck is a globally used knowledge repository of adversary tactics and techniques used in cyber attacks. The framework provides knowledge of adversary tactics, methods, and procedures (TTPs). These can be utilized for example in improving a company's threat intelligence.

<h3> Tactic </h3>

A tactic describes the main goal of the attack and what the attacker hopes to achieve. As an example, the tactic "Initial Access" describes how the attacker first gains an access to the target system, environment etc. 

<h3> Technique </h3>

A technique is a specialiced way or strategy that an attacker uses to attain their malicious goal. Technique basically describes in more detail how the attacker is going to execute their tactic. "Phishing" is a very common technique used to deceive the victim into revealing sensitive information or installing malware.

<h3> Sub-technique </h3>

A sub-technique is derived from it's parent technique, in that it explains how the attack is carried out. It basically further defines the technique used. "Spearphishing Link" is an example of a sub-technique of "Phishing".  It employs the use of links to download malware contained in email, instead of attaching malicious files to the email itself.

<h3> Procedure </h3>

Procedure is the real world attack carried out to reach the malicious goal. "AADInternals" is an example of a procidure, it's a  PowerShell-based framework for administering, enumerating, and exploiting Azure Active Directory.

<h2> Sources </h2>


Phishing: https://attack.mitre.org/techniques/T1566/
Spearphishing Link: https://attack.mitre.org/techniques/T1566/002/
https://attack.mitre.org/

ADDInternals: https://attack.mitre.org/software/S0677/

<h2> WebGoat A3 </h2>

 will be added soon... having some technical difficulties.


