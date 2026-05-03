
SOC ANALYST 2 week schedule
focused 2-week schedule to prepare for a SOC Analyst (Tier 1) job interview. This plan assumes you have basic IT knowledge and focuses only on what you need to pass the interview and technical screening.

Daily commitment: 4–6 hours
Goal: Pass SOC interview (theory + basic hands-on)
2-week schedule** to prepare you for a SOC Analyst job, assuming you have basic IT knowledge and can dedicate 4–6 hours daily.

**Week 1: Foundations & Core Tools**  
Start by solidifying your networking and operating system fundamentals.
On Days 1–2, review TCP/IP, OSI model, DNS, HTTP/HTTPS, and common ports (22, 80, 443, 3389). Use flashcards or quick YouTube refreshers.
Master Network & Log Basics**  
Start by reviewing **ports and protocols** (HTTP=80, HTTPS=443, DNS=53, SSH=22, RDP=3389). Then learn to read a **log entry** – identify timestamp, source IP, destination IP, action (allowed/denied). Practice on free resources like "LOG ANALYSIS BASICS" on YouTube. By day 2, you should be able to look at a firewall log and tell if a connection was successful or blocked.

On Days 3–4, dive into Windows Event Logs (focus on Event IDs 4624, 4625, 4672, 4688) and Linux system logs in `/var/log` (auth.log, syslog). Practice using `grep`, `awk`, and `tail` to filter logs. 
Understand the Attack Lifecycle**  
Memorize the **MITRE ATT&CK** tactics (at least the first six: Recon, Resource Development, Initial Access, Execution, Persistence, Privilege Escalation). Then learn the **Cyber Kill Chain** (7 steps from Recon to Actions on Objectives). For each alert you see later, practice mapping it to both frameworks. This is what interviewers love.

On Days 5–6, set up a free SIEM — either Splunk Free or Wazuh on a virtual machine. Learn to ingest sample logs (you can download free PCAPs or use generated Windows logs) and write basic search queries. 
Get Hands-On with a SIEM**  
Install **Splunk Free** or create a free **Elastic Cloud** trial. Upload a sample log file (download any .csv log from GitHub). Run 5 basic searches: `index=*` , `source IP = x.x.x.x` , `status=404` , `error*` , `failed password`. Create one simple **dashboard** showing top source IPs. Screenshot it for your portfolio.

On Day 7, review the MITRE ATT&CK framework — specifically the Initial Access, Execution, and Persistence tactics — and map three common attacks (phishing, malicious macro, scheduled task) to relevant techniques.
Review & Simulate an Alert Triage**  
Spend 3 hours on **TryHackMe** room called "SOC Level 1" – specifically the alert triage simulation. Then for 1 hour, search YouTube for "SOC analyst interview questions" and record yourself answering: *"Walk me through how you would investigate a suspicious login alert."* Your answer must include: check user account, source IP geolocation, time of login, previous logins from that IP, and then escalate or close.



**Week 2: Hands-On Practice & Interview Readiness**  
Start Week 2 with simulated SOC platforms.
On Day 8–9, work through TryHackMe’s “SOC Level 1” path or LetsDefend’s free tier — focus on alert triage, false positive identification, and escalation procedures.
Learn Incident Response Steps**  
Memorize the **6 phases of IR** (Preparation, Identification, Containment, Eradication, Recovery, Lessons Learned). Then practice writing a **1-paragraph incident report** for a fake phishing email – include: what happened, when, which user, what you did (isolated endpoint), and final status (contained). SOC managers love clear, short reports

On Day 10, practice writing incident reports: take an alert (e.g., “suspicious PowerShell execution”) and document what you saw, why it matters, and what next step you’d take. 
Practice False Positive vs True Positive**  
Go to **LetsDefend** (free tier) and triage 5 real alerts. For each, decide: is it a **false positive** (benign activity triggering an alert) or a **true positive** (real malicious activity)? Write one sentence justifying each decision. Example: *"Alert: multiple failed logins. False positive because user admitted caps lock was on."*


On Day 11–12, review 20 common interview questions — such as 
“What is the difference between a false positive and false negative?”
“Explain the cyber kill chain,”
“How would you handle an alert with no clear malicious indicator?” — and practice answering aloud. 
Master the "Tell Me About Yourself" Answer**  
Write a 60-second script: "I am an aspiring SOC analyst with hands-on experience in [Splunk/Elastic]. I recently completed [TryHackMe/letsdefend] labs where I triaged alerts and mapped them to MITRE ATT&CK. I am looking for a Tier 1 role where I can monitor, detect, and escalate threats while growing my incident response skills." Practice until it sounds natural, not robotic.
 Prepare for Shift Work & Soft Skill Questions**  
Anticipate these two questions:
- *"Are you comfortable with night shifts and weekends?"* Answer: "Yes, I understand SOCs operate 24/7 and I am fully available for rotating shifts."
- *"How do you handle repetitive tasks without losing focus?"* Answer: "I use checklists and take short breaks to reset my attention. I also treat every alert as a potential real threat."

On Day 13, build a one-page “SOC cheat sheet” with key ports, log locations, common Event IDs, and MITRE tactics to review. 
 Full Mock Interview**  
Find a friend or use ChatGPT voice mode to interview you for 30 minutes. Include: salary expectations (you will say "flexible"), a log analysis question, a phishing triage scenario, and a false positive identification. After the mock, write down 3 things you struggled with and re-study only those.


On Day 14, do a mock interview (use a friend or record yourself) and finalize your resume — highlight your home lab, any certifications in progress (Security+ or CySA+), and specific tools you’ve used (Splunk, Wazuh, TryHackMe). By the end of two weeks, you will have practical hands-on experience and the confidence to discuss real SOC scenarios.
Final Portfolio & Application Day**  
Create a simple 1-page Google Doc or PDF titled **"SOC Lab Portfolio"** – include 3 screenshots:
1. Your Splunk dashboard showing searches.
2. One alert you triaged with your decision (true/false positive).
3. Your 1-paragraph incident report.
Upload this to Google Drive and add the link to your resume or cover letter. Then apply to 5 entry-level SOC jobs (titles: "SOC Analyst Tier 1", "Security Analyst", "Junior Cybersecurity Analyst").

By the end of day 14, you will not master everything – but you will have **hands-on proof** (your portfolio), **triage experience** (from LetsDefend), and the ability to **speak like a junior analyst** in interviews. That is enough to get hired at many SOCs.

Final Portfolio & Application Day**  
Create a simple 1-page Google Doc or PDF titled **"SOC Lab Portfolio"** – include 3 screenshots:
1. Your Splunk dashboard showing searches.
2. One alert you triaged with your decision (true/false positive).
3. Your 1-paragraph incident report.
Upload this to Google Drive and add the link to your resume or cover letter. Then apply to 5 entry-level SOC jobs (titles: "SOC Analyst Tier 1", "Security Analyst", "Junior Cybersecurity Analyst").

