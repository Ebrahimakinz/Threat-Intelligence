<h1>Cybersecurity Incident Management</h1>

## Threat Intelligence & Adversary Profiling

### Project Context:

The goal of this deliverable was to simulate a mission-critical task performed by Threat Intelligence Analysts and Incident Response teams: the systematic deconstruction of a sophisticated, real-world adversary. By profiling the behaviours, motivations, and technical methodologies of APT29 (Cozy Bear), this report provides the foundational intelligence required to build proactive and resilient organizational defences. <br />
This deliverable showcases my proficiency in converting open-source intelligence (OSINT) into a structured defensive strategy. By bridging the gap between who the actor is and how they operate, I provide leadership with the 'why' behind necessary security investments.

<br />
<p align="center">
 Technical Snapshot: APT29 Tactical Mapping
<br/>
<img src="https://imgur.com/rhc8UJR.png" height="80%" width="80%" alt="Tactics"/>
<br />

### Threat Actor Overview – APT29:
The Russian Foreign Intelligence Service (SVR) is believed to support APT29, a sophisticated and elusive threat group that operates under several aliases, including Cozy Bear, The Dukes, Midnight Blizzard, and Nobelium. APT29 is an intelligence-gathering, nation-state-sponsored actor. By obtaining sensitive information from foreign governments, organizations, and individuals, their operations seek to further Russian geopolitical interests. 

Although they have been active since at least 2008, they rose to prominence in 2014 after allegedly carrying out a string of targeted attacks on prominent locations, such as the Democratic National Committee, the US White House, and the Department of State.

To support Russia’s strategic goals on the international scene, APT29 engage in espionage to gather intelligence on defense, economic, and foreign policy issues. They concentrate on gaining long-term, covert access to target networks for ongoing intelligence collection. 

They are frequently confused with Fancy Bear (also known as APT28), another well-known Russian hacking group. Threat intelligence reports, on the other hand, have continuously pointed out significant variations in their tactics, techniques, and procedures (TTPs), pointing to different operational goals and approaches.


#### Target Profile &MITRE ATT&CK Mapping:
APT29’s operations have been observed globally to exhibits preference for organizations involved in foreign policy and international and entities engaged in research and development that can provide strategic insights into geopolitical developments.

They frequently target research institutes, think tanks, and government networks in North America, Asia, Europe, and NATO member nations. The actor searches for sensitive data kept in these organizations' networks and for different people engaged in defence and geopolitical research. 

Over the years, the team has shown incredible perseverance, flexibility, and technical skill while being at the vanguard of significant cyber incidents. Their campaigns, which frequently aim to steal sensitive data, have targeted a wide range of organizations, including critical infrastructure, private companies, and government agencies.

APT29 employs a range of tactics and techniques as defined in the MITRE ATT&CK framework. Below are three tactics with associated techniques and real-world applications:

</p>

<h2>Tools and Utilities Used</h2>

- <b>Open-Source Intelligence (OSINT) gathering, MITRE ATT&CK Matrix </b> 

<h2>APT29 Attack Mapping Samples</h2>
<p align="center">
Initial Access: <br/>
<img src="https://imgur.com/568hVfU.png" height="80%" width="80%" alt="Mitre Att&ck"/>
<br />
<br />
Execution: <br/>
<img src="https://imgur.com/DUiKb2k.png" height="80%" width="80%" alt="Mitre Att&ck"/>
<br />
<br />
Command and Control (C2): <br/>
<img src="https://imgur.com/5kQpMuC.png" height="80%" width="80%" alt="Mitre Att&ck"/>
<br />
<br />
Case Study: SolarWinds Supply Chain Attack: <br/>
<img src="https://imgur.com/fontuCt.png" height="80%" width="80%" alt="Mitre Att&ck"/>
<br />
<br />
References: <br/>
<img src="https://imgur.com/pdLGK3I.png" height="80%" width="80%" alt="Mitre Att&ck"/>
<br />
<br />
</p>

<b>Comparative Analysis table showing strategic nuance behind how a APT29 adapts their methods to different target environments.</b>
<p align="center">
Comparative Analysis: SolarWinds vs. Operation Nightingale
<br/>
<img src="https://imgur.com/3IbVUN6.png" height="80%" width="80%" alt="Comparative Table"/>
<br />
<br />
</p>

### Strategic Insights, Reflections and Future Outlook

Reflecting on the analysis of APT29 and the dual case studies of SolarWinds and Operation Nightingale, several key insights emerged regarding the evolution of modern cyber governance and threat intelligence.


- While SolarWinds demonstrated APT29’s ability to conduct a patient, highly technical supply chain attack, Operation Nightingale highlighted their agility in exploiting global crises. Both campaigns share a common DNA: the sophisticated use of trusted channels—whether software updates or reputable cloud providers, to bypass the perimeter.<br />
- The SolarWinds compromise proved that traditional perimeter defences (firewalls and EDR) are insufficient if the "trusted" software already inside the network is compromised. Future GRC frameworks must prioritize Software Bill of Materials (SBOM) and rigorous third-party vendor assessments to ensure the integrity of the entire digital supply chain.<br />
- As seen in Operation Nightingale, APT29’s use of Google Drive and Microsoft OneDrive for C2 traffic highlights a critical defensive gap. We must move toward Zero Trust Architecture (ZTA). Trust should never be granted based on a domain's reputation alone; instead, continuous monitoring of behavior within those trusted cloud channels is essential. <br />
- Despite the high technical sophistication of nation-state actors, they still frequently rely on simple human error (Spear phishing in Nightingale). Security controls must be frictionless. If security protocols are too cumbersome, users will find workarounds, inadvertently creating the "back doors" that actors like APT29 exploit. Investing in a strong Security Culture is as important as the technical stack.<br />
- The rapid adaptation of APT29 during the COVID-19 pandemic shows that threat actors pivot faster than most annual policy review cycles. Organizations must transition to Agile Governance. Policies regarding AI, cloud access, and remote work must be "living documents" that are updated quarterly based on the latest Threat Intelligence (TI) feeds.<br />

This research underscores that defending against a nation-state adversary is not a 'one-and-done' technical fix. It requires a holistic, intelligence-led strategy that integrates technical rigor with organizational agility and a deep understanding of the human element. By mapping these threats to the MITRE ATT&CK framework, we can transform abstract fears into actionable, prioritized defensive roadmaps.


