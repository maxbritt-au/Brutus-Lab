# Brutus-Lab

## Objective
[Brief Objective - Remove this afterwards]

Investigate the provided forensic artefacts from the HackTheBox Brutus DFIR challenge to identify suspicious authentication activity and an attacker’s interactive session. Produce an evidence-backed timeline from auth.log and wtmp, demonstrate basic forensic parsing, and make containment and remediation recommendations aligned to NIST CSF functions (Detect, Respond).

### Skills Learned
[Bullet Points - Remove this afterwards]

- Practical log acquistion, verification and parsing of Linux artefacts (auth.log, wtmp).
- Correlation of authentication events to interactive sessions to produce an incident timeline.
- Use of WSL and forensic tools (7zip, last, Python parser) to access and interpret binary artefacts.
- Basic DFIR workflow.

### Tools Used
[Bullet Points - Remove this afterwards]

- WSL (Ubuntu) - Linux environment
- 7zip - To extract zipped files
- last (from util-linux) — to parse wtmp into human-readable sessions.
- python3 and supplied utmp.py — to parse wtmp where last was insufficient.

## Steps
drag & drop screenshots here or use imgur and reference them using imgsrc

Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Lab Landing Page*
<img width="3839" height="2399" alt="image" src="https://github.com/user-attachments/assets/7cdff857-a6a3-473b-bc1c-3cf45e74ba39" />

*Ref 2: utmp.py doc*
<img width="3839" height="2399" alt="image" src="https://github.com/user-attachments/assets/d3f2586c-bf77-4212-98b4-201584d919fe" />

*Ref 3: Auth.log doc showing ip address of attacker*
<img width="3839" height="2399" alt="image" src="https://github.com/user-attachments/assets/00b25315-2343-42ca-ac01-4f43b7e5b548" />

*Ref 4: First question answered correctly*
<img width="3839" height="2399" alt="image" src="https://github.com/user-attachments/assets/0af429da-9204-492a-8986-56acd407307f" />

*Ref 5: Auth.log showing name of account*
<img width="3839" height="2399" alt="image" src="https://github.com/user-attachments/assets/14b4de48-528d-447a-a861-1baba2cc1e78" />

*Ref 6: wtmp file showing timestamp for answer 3*
<img width="3839" height="2399" alt="image" src="https://github.com/user-attachments/assets/7ccadec2-c9c2-42e8-a654-4fe82d0ee0a7" />

*Ref 7: Session id correlating with question 2*
<img width="3839" height="2399" alt="image" src="https://github.com/user-attachments/assets/878de45d-f628-411d-986f-bd5db91e3bb6" />

*Ref 8: Creation on cyberjunkie account for question 5*
<img width="3839" height="2396" alt="image" src="https://github.com/user-attachments/assets/af445027-b371-4eaf-901f-9baa56704446" />

*Ref 9: Attacker created new local account (cyberjunkie) to stay in the system*
<img width="3839" height="2399" alt="image" src="https://github.com/user-attachments/assets/34235e2a-d0d3-4bad-87c3-61c6d675da0f" />

*Ref 10: Timestamp session 37 ended for question 7*
<img width="3839" height="2399" alt="image" src="https://github.com/user-attachments/assets/31575f23-7242-4fb7-886c-a2df488b094a" />

*Ref 11: Command used to download script for question 8*
<img width="3836" height="2399" alt="image" src="https://github.com/user-attachments/assets/7485e4f8-2c06-42df-b84d-f4a490b3dbbc" />

*Ref 12: Completion of Lab*
<img width="3837" height="2385" alt="image" src="https://github.com/user-attachments/assets/4d57bd61-1c83-45c6-b377-a540fe93ac8d" />






