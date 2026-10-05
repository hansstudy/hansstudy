<p align="center">
  <a href="https://hans.study"><img src="assets/banner.svg" alt="Hans Study. Independent network and security consultant. Ontario, Canada." width="100%"></a>
</p>

# Hans Study, CISSP

I'm an independent network and security consultant based in Ontario, Canada, working with clients across Canada and the United States. The work is boutique: enterprise networks, OT and ICS, Windows and network hardening, and the infrastructure underneath them. Hardening and tuning are the specialty. CMMC readiness for defense suppliers is part of it too, built on NIST SP 800-171 work I've been doing since 2019, and so is the CPCSC writing and open tooling further down this page.

Nothing is sold here except the advice. There's no hardware or software resale, and no commission tied to whatever gets specified.

I wrote The Study Guide series, including the free *Study Guide to CPCSC Readiness* (CC BY-ND 4.0, DOI [10.5281/zenodo.23145960](https://doi.org/10.5281/zenodo.23145960)).

<p>
  <a href="https://hans.study"><img alt="Website hans.study" src="https://img.shields.io/badge/Website-hans.study-df7a1e?style=flat-square&labelColor=161614"></a>
  <a href="mailto:contact@hans.study"><img alt="Email contact@hans.study" src="https://img.shields.io/badge/Email-contact%40hans.study-df7a1e?style=flat-square&labelColor=161614"></a>
  <a href="https://orcid.org/0009-0000-5322-5033"><img alt="ORCID 0009-0000-5322-5033" src="https://img.shields.io/badge/ORCID-0009--0000--5322--5033-df7a1e?style=flat-square&labelColor=161614"></a>
  <a href="https://linkedin.com/in/hans-study"><img alt="LinkedIn hans-study" src="https://img.shields.io/badge/LinkedIn-hans--study-df7a1e?style=flat-square&labelColor=161614"></a>
  <a href="https://youtube.com/@studybyt3s"><img alt="YouTube @studybyt3s" src="https://img.shields.io/badge/YouTube-%40studybyt3s-df7a1e?style=flat-square&labelColor=161614"></a>
  <a href="https://x.com/studybyt3s"><img alt="X @studybyt3s" src="https://img.shields.io/badge/X-%40studybyt3s-df7a1e?style=flat-square&labelColor=161614"></a>
  <a href="https://www.amazon.com/author/hans-study"><img alt="Amazon Author" src="https://img.shields.io/badge/Amazon-Author%20page-df7a1e?style=flat-square&labelColor=161614"></a>
</p>

## Background

I started out fixing computers for friends and family, then installing small business networks and CCTV systems, and by 2010 it was independent network and security work full time. The 15+ years since have been spent across public sector, defense, public safety, and critical infrastructure environments, where the stakes are high and the margin for error is small.

Day to day that means Microsoft Windows (server and workstation), Cisco, and Aruba. Axis, Bosch, Milestone, Avigilon, C-CURE, Fortinet, Palo Alto, Juniper, and Alcatel-Lucent OmniSwitch come in when they're the right fit for the deployment. Genetec Security Center is a long-running niche; there's a Genetec baseline in the hardening scripts and a health audit for it on the site.

I've also taught Cisco CCNA, networking, information security, and Windows Server and Workstation at the post-secondary level. Hundreds of students went through those courses.

## Repositories

These are the tools I use on engagements, and each one has a page on hans.study that explains how it works.

- [CPCSC](https://github.com/hansstudy/CPCSC). The CPCSC and ITSP.10.171 hub, with all 98 controls in plain language, a Level 1 checklist, read-only Windows audit scripts, and templates. Scripts are MIT, docs and data are CC BY 4.0.
- [windows-hardening-scripts](https://github.com/hansstudy/windows-hardening-scripts). Standalone PowerShell baselines for DISA STIG, CIS L1, CCCS/NSA/CISA, CMMC/CPCSC readiness, Genetec Security Center, and kiosks. Source-available under the Hans Study licence.
- [PortProof](https://github.com/hansstudy/portproof). Proves a declared list of firewall paths is open before a cutover or a vendor commissioning. It probes each source, target, and port once, returns a pass/fail matrix, writes HTML, CSV, and JSON reports, and exits non-zero when a required path fails. Apache-2.0.
- [cisco-switch-config](https://github.com/hansstudy/cisco-switch-config). A Claude skill that audits Cisco IOS and IOS-XE switch running-configs offline against 121 checks and generates hardened baselines. Credentials are masked, and each finding carries a paste-ready fix cited to DISA STIG, NSA, CISA, or Cisco guidance. Apache-2.0.

The browser tools stay on the site at [hans.study/tools](https://hans.study/tools/), and they don't need a signup. That's where you'll find the policy builder, the switch configuration generator, the Windows configuration utility, the subnet and conductor calculators, and the Genetec health audit.

Each repository's own LICENSE governs it. The S monogram and the Hans Study wordmark are not covered by any code licence.

## What I work on

- Network architecture and hardening on Cisco, Aruba, Juniper, and ALE OmniSwitch
- Microsoft Windows hardening for server and workstation, including Active Directory and Defender
- Canadian Program for Cyber Security Certification (CPCSC), ITSP.10.171, and ITSG-33
- CMMC, NIST SP 800-171, and ISO 27001 readiness
- OT and ICS security
- IT and physical security convergence
- CCTV, access control, and Genetec Security Center, when an engagement needs them
- Structured cabling and installation quality
- Mentorship, time permitting, for practitioners and integrators who want to own their stack

## Books

The Study Guide series is written for the people who do the work. Each title is a field reference, laid out in the order you'd use it on site.

- *The Study Guide to CPCSC Readiness: A Field Reference for Canadian Defense Suppliers*. Canada's new defense cyber certification, from the first contract clause to the Level 2 assessor, with all 98 requirements read in plain language. Free PDF under CC BY-ND 4.0. Read it on the site at [hans.study/cpcsc_book](https://hans.study/cpcsc_book/), or get it from [Zenodo v1.3.2](https://zenodo.org/records/23171055) · DOI [10.5281/zenodo.23145960](https://doi.org/10.5281/zenodo.23145960) · [Internet Archive](https://archive.org/details/the-study-guide-to-cpcsc-readiness-hans-study) · [Wikidata Q141648473](https://www.wikidata.org/wiki/Q141648473)
- *The Study Guide to Network and System Hardening: A Field Reference for Systems and Security Integrators*. Windows, Cisco, Aruba, and Genetec, for the hardening work that decides whether a deployment is defensible. Paperback and Kindle on [Amazon](https://a.co/d/06TeQhgd).
- *The Study Guide to CCTV and Access Control Systems: A Field Reference for Working Integrators and Security Technicians*. For the people who plan, install, commission, and service CCTV and access control. Paperback and Kindle on [Amazon](https://a.co/d/0g6e3Hbp).

My Amazon author page is [amazon.com/author/hans-study](https://www.amazon.com/author/hans-study). Review copies, errata, bulk orders, and translation rights go to book@hans.study.

## Podcast

StudyByt3s is my podcast on the work that sits between IT, physical security, and OT, run as a conversation rather than a tips-and-tricks show. Episodes are at [hans.study/studybyt3s](https://hans.study/studybyt3s/), or search "StudyByt3s" on Apple Podcasts, Spotify, and YouTube.

## Contact and links

Project work and general questions go to contact@hans.study. Press, podcast, and speaking enquiries go to media@hans.study, and the credit line for press is Independent Network and Security Consultant, hans.study.

- Website: [hans.study](https://hans.study)
- ORCID: [0009-0000-5322-5033](https://orcid.org/0009-0000-5322-5033)
- Wikidata: [Q141043781](https://www.wikidata.org/wiki/Q141043781)
- LinkedIn: [linkedin.com/in/hans-study](https://linkedin.com/in/hans-study)
- X: [x.com/studybyt3s](https://x.com/studybyt3s)
- YouTube: [youtube.com/@studybyt3s](https://youtube.com/@studybyt3s)
- Instagram: [instagram.com/studybyt3s](https://instagram.com/studybyt3s)
- GitHub: [github.com/hansstudy](https://github.com/hansstudy)
- Books: [hans.study/books](https://hans.study/books/)
- Amazon author page: [amazon.com/author/hans-study](https://www.amazon.com/author/hans-study)
