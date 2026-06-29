# Year 1 (52-Week) Curriculum — Zharnyx Academy

> Version: 1.0  
> Last updated: 2026-06-29  
> Status: Canonical first-year curriculum for Zharnyx Academy

This document is the single, canonical outline for the first year at Zharnyx Academy.

It is written for learners who are comfortable using a computer and the internet but may have **no prior IT or security background**. The year is designed to move from basic computing and networking skills into practical cybersecurity work that can support real teams in the field.

- **Weeks 1–13:** IT and computing foundations (operating systems, networking, scripting, system administration).
- **Weeks 14–52:** Security-focused practice with a steady increase in complexity, including monitoring, testing, cloud security, and investigation.

## How to use this document

- **One theme per week:** Each week has a single focus and 2–3 bullets describing hands-on activities.
- **Lab-first:** Every bullet is meant to become at least one lab or guided session. Instructors can split or combine bullets based on cohort pace.
- **No branching:** All learners complete the same Year‑1 path. Specialisation can happen after this year.
- **Versioning:** When you create detailed labs or lesson plans, reference this file and its version so updates can be tracked.

---

## Weeks 1–13: Computing Foundations

### Week 1: Understanding Computers and the Web
- Explore the main parts of a computer (CPU, memory, storage) using a simple system information tool.
- Practice basic file operations (create, copy, move, delete) and folder organisation on your own machine.
- Map how a web page loads by following each step from browser address bar to the page appearing.

### Week 2: Working Comfortably with an Operating System
- Install and explore a beginner-friendly Linux distribution in a virtual machine.
- Compare basic tasks (creating folders, installing software) across Windows and Linux.
- Practice changing system settings safely (time, language, network) and revert changes when needed.

### Week 3: Command Line Basics
- Open a command-line terminal and navigate the file system using only commands.
- Create, view, and edit text files from the command line.
- Use built-in help for commands to understand options and flags.

### Week 4: Files, Processes, and System Monitoring
- List running processes and identify which programs they belong to.
- Observe CPU, memory, and disk usage while starting and closing applications.
- Search for files by name, size, or content using system tools.

### Week 5: Networking Basics — Getting Online
- Draw and label your home or campus network, including routers, switches, and devices.
- Use simple commands to check your IP address, test connectivity, and look up domain names.
- Trace how data travels from your computer to a public website using built-in tools.

### Week 6: Networking Basics — Ports and Protocols
- List open network connections on your machine and tie them back to running applications.
- Capture or observe basic network traffic and identify common protocols (such as web and name lookup traffic).
- Block and allow simple connections (for example, using a basic firewall or system setting) and watch the effect.

### Week 7: Scripting Fundamentals with a Friendly Language
- Write small scripts to automate simple tasks (renaming files, counting lines in a text file).
- Accept user input in a script and display different outputs based on that input.
- Read and reuse community examples by modifying them for your own tasks.

### Week 8: Working with Data and Logs
- Parse a structured text file (such as CSV or JSON) using a script and extract selected fields.
- Filter large log files with command-line tools to find events of interest.
- Create simple summary reports (counts, minimum/maximum values) from raw data.

### Week 9: User Accounts and Permissions
- Create local user accounts and groups on a lab machine.
- Experiment with file and folder permissions, then confirm access with different users.
- Configure and test password policies (length, complexity, expiry) in a safe environment.

### Week 10: Installing and Managing Software
- Install, update, and remove software using both graphical tools and package managers.
- Configure a basic service (such as a web server or database) to start and stop cleanly.
- Review software configuration files and change simple settings with comments.

### Week 11: Basics of System Administration
- Plan and perform a simple backup and restore of important files.
- Schedule a recurring task (such as log cleanup or file backup) and verify that it runs.
- Document system details (installed software, accounts, network settings) in a simple inventory.

### Week 12: Troubleshooting Everyday Problems
- Reproduce common issues (no internet, slow system, application not starting) and walk through a step-by-step fix.
- Use logs and system messages to trace what happened before and after an error.
- Develop and practice a basic troubleshooting checklist for your own machine.

### Week 13: Putting Foundations Together
- Build a small lab environment (one or two virtual machines) that you can break and fix safely.
- Simulate a simple problem across systems (such as a service not reachable) and resolve it end to end.
- Review and reflect on the tools and commands you now know, creating a personal quick-reference sheet.

---

## Weeks 14–52: Security Practice and Operations

### Week 14: What is Security in Practice?
- Compare secure vs. insecure setups on a test system and list the differences.
- Identify basic security goals (protecting data, keeping services available) using real-world examples.
- Review a few short case studies of security incidents and discuss what went wrong.

### Week 15: Understanding and Managing Accounts Safely
- Review user accounts and groups on a lab system and remove or disable unneeded ones.
- Strengthen sign-in settings (password rules, lockout rules) and test them from a learner account.
- Set up and use a password manager for storing and generating strong credentials.

### Week 16: Securing Files and Folders
- Classify files on a lab machine by sensitivity (public, internal, private) and adjust permissions accordingly.
- Enable basic disk or folder protection features and confirm who can read or write data.
- Practice safely sharing a file over the network while limiting who can access it.

### Week 17: System Hardening Basics
- Create a hardening checklist for a fresh operating system install.
- Apply basic security settings (turning off unused services, tightening remote access) on a lab machine.
- Compare before-and-after states of the system and document the changes.

### Week 18: Reading Operating System Logs
- Locate key system log files and learn what each one records.
- Use filtering tools to search logs for sign-in events, errors, and warnings.
- Build a simple timeline of events on a system using log entries.

### Week 19: Network Traffic Observation
- Capture network traffic in a controlled lab and identify which applications generate which flows.
- Filter captured traffic by address, port, and protocol to answer basic questions.
- Spot unusual or suspicious patterns (unexpected destinations, uncommon ports) in sample data.

### Week 20: Secure Network Configuration
- Map inbound and outbound network rules on a lab firewall or host-based filter.
- Adjust rules to allow expected traffic and block clearly unnecessary or risky connections.
- Test connectivity before and after rule changes to ensure you do not break essential services.

### Week 21: Web Basics and Common Weaknesses
- Set up a simple web application in a lab environment.
- Explore how forms, cookies, and sessions work using browser tools.
- Try harmless inputs that show how poor input handling can lead to security issues.

### Week 22: Safe Scanning and Service Discovery
- Scan a small lab network to discover active hosts and open ports.
- Match discovered services to the software actually running on each host.
- Document which services should be exposed and which should be limited or removed.

### Week 23: Checking System Configuration Against a Baseline
- Define a basic security baseline for a lab server (required services, users, and settings).
- Compare an existing server to this baseline and list any gaps.
- Fix selected gaps and re-check to confirm alignment with the baseline.

### Week 24: Working with Centralised Logs
- Forward logs from multiple systems into a single logging tool.
- Build saved searches or views for common events (sign-ins, service failures, configuration changes).
- Create a simple daily log review routine and record what you found.

### Week 25: Monitoring Alerts and First Response
- Configure basic alerts in a logging or monitoring tool for obvious problem patterns.
- Trigger a harmless test event and follow the alert from trigger to resolution.
- Create a simple runbook describing how to handle a recurring type of alert.

### Week 26: Secure Handling of End-User Devices
- Review common security settings on laptops or desktops (updates, disk protection, screen locks).
- Simulate bringing a new device into a controlled environment and applying baseline security settings.
- Practice responding when a device is lost or suspected to be misused (changing passwords, revoking access).

### Week 27: Email and Web Safety in Practice
- Examine real or simulated phishing emails and highlight warning signs.
- Configure and test basic email security options (spam filtering, safe link handling) in a lab.
- Practice safe behaviour for downloading files and using browser extensions.

### Week 28: Identifying and Managing Software Vulnerabilities
- Look up known issues for software installed in your lab environment.
- Match example vulnerability descriptions to the affected components in your systems.
- Plan and apply updates or configuration changes to reduce risk from these issues.

### Week 29: Patch and Update Management Workflows
- Build an inventory of software and versions across lab machines.
- Design a simple update schedule and test it on non-critical systems first.
- Record before-and-after version information to prove that updates were applied.

### Week 30: Introduction to Application Security Testing
- Map out the main functions of a simple web or desktop application in your lab.
- Design basic test cases to check how the application behaves with unexpected input.
- Run tests and document any unusual or unsafe behaviour you observe.

### Week 31: Exploring Network-Level Testing
- Use safe tools to probe which network ports and services are exposed from a lab system.
- Correlate scan findings with firewall and routing configurations.
- Recommend changes that would reduce unnecessary exposure without blocking required access.

### Week 32: Testing Authentication and Session Handling
- Walk through the full sign-in and sign-out flow of a lab application.
- Test how the application behaves when sessions are left idle, reused, or forced to expire.
- Document weaknesses or confusing behaviours that could create security issues.

### Week 33: Data Protection in Transit and at Rest
- Inspect how a sample website or service protects data while it is being sent across the network.
- Compare behaviour when encryption is correctly configured vs. when it is missing or misconfigured.
- Enable basic encryption features for stored data in a lab system and confirm access controls.

### Week 34: Introduction to Cloud Environments
- Create a small cloud-based lab environment with compute, storage, and networking components.
- Explore the management console or interface to understand how resources are organised.
- Tag and group resources so they can be tracked and managed as a unit.

### Week 35: Identity and Access in Cloud Platforms
- Create cloud identities (users, groups, roles) and assign them least-privilege access to lab resources.
- Test what each identity can and cannot do, adjusting permissions where needed.
- Review access logs to see which identities performed which actions.

### Week 36: Network Design and Segmentation in the Cloud
- Design a simple cloud network layout separating public-facing and internal resources.
- Implement basic network controls (such as security groups or access lists) and test connectivity.
- Review which resources are reachable from the internet and tighten exposure where possible.

### Week 37: Securing Cloud Storage and Databases
- Configure access controls for cloud storage so that only intended identities can read or write data.
- Test protections for sensitive data, including preventing public access when not needed.
- Review storage and database audit logs to see how data is being used.

### Week 38: Monitoring and Logging in Cloud Environments
- Enable logging and monitoring features for key cloud resources.
- Build a simple dashboard or saved views showing resource health and security-relevant events.
- Investigate a simulated issue (such as an unusual sign-in) using cloud logs.

### Week 39: Automated Provisioning and Configuration Safety
- Use basic scripts or templates to create and configure cloud resources consistently.
- Compare manually configured resources with scripted ones to spot drift.
- Add simple safety checks to your automation to prevent risky settings.

### Week 40: Secure Deployment of a Small Application
- Deploy a small application stack (compute, storage, network) in the cloud using your earlier templates.
- Apply hardening steps to each layer before exposing it to the internet.
- Run a basic security review of the deployed environment and record findings.

### Week 41: Collecting and Preserving Evidence
- Prepare a checklist for capturing information from a system when something suspicious is reported.
- Practice collecting copies of key logs and system details without changing them.
- Store collected data in a structured way so it can be used later in an investigation.

### Week 42: Analysing System Images and Files
- Take a safe copy or snapshot of a lab system for later review.
- Examine files, installed software, and configuration in the copied image.
- Compare normal vs. altered systems to spot changes that may be linked to an incident.

### Week 43: Email, Document, and Link Investigations
- Analyse suspicious emails, documents, or links in a controlled environment.
- Extract and review technical details (headers, links, attachments) to understand what they try to do.
- Classify findings (harmless, suspicious, likely harmful) and record reasoning.

### Week 44: Network and Log Forensics
- Use historical network captures and logs to trace how a simulated incident unfolded.
- Correlate events across systems based on time, addresses, and user identifiers.
- Build a simple visual timeline or diagram showing the key steps of the incident.

### Week 45: Endpoint Investigation and Containment
- Investigate a lab endpoint that shows signs of suspicious behaviour.
- Identify unusual processes, files, or connections on the system.
- Plan and rehearse clean containment steps that reduce risk without causing extra damage.

### Week 46: Coordinated Incident Handling Exercises
- Work through a guided scenario where multiple systems show related suspicious activity.
- Assign simple roles within a small team (observer, communicator, investigator) and practice coordination.
- Produce a short incident summary describing what happened and what was done.

### Week 47: Reviewing and Improving Security Controls
- Review past lab incidents and exercises to identify patterns and recurring weaknesses.
- Recommend changes to configurations, processes, or training that would have reduced impact.
- Prioritise improvements and track them in a simple action list.

### Week 48: Integrating Testing, Monitoring, and Investigation
- Design a small end-to-end exercise where you introduce a controlled issue, detect it, and respond.
- Use logs, monitoring tools, and targeted tests together to confirm what is happening.
- Reflect on how different security activities support each other in practice.

### Week 49: Working with Realistic Playbooks
- Take existing or sample response playbooks and adapt them to your lab environment.
- Run through at least one playbook step by step, checking where information or tools are missing.
- Suggest updates to make the playbook clearer and more useful for new team members.

### Week 50: Operating in a Small Security Team
- Simulate a week in the life of a small security function, assigning daily tasks to each learner.
- Rotate responsibilities such as log review, basic testing, and investigation follow-up.
- Hold a short daily review to discuss findings, challenges, and handovers.

### Week 51: Capstone Project — Building and Defending a Mini Environment
- Design and build a small, realistic environment (on-premise, cloud, or mixed) with multiple systems.
- Apply security controls from earlier weeks to protect the environment.
- Invite controlled tests and monitoring to see how the environment holds up and where it needs improvement.

### Week 52: Reflection, Portfolio, and Next Steps
- Review your Year‑1 journey and list the concrete tasks you can now perform in real environments.
- Organise lab notes, screenshots, and findings into a simple portfolio that demonstrates your skills.
- Plan your next learning steps and potential specialisation areas based on what you enjoyed and where you were strongest.
