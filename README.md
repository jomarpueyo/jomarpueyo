# Jomar Pueyo

Network & Security Specialist at Huntsville ISD in Texas. I build Python and PowerShell tooling that gives a K-12 district enterprise-grade visibility into its Google Workspace (~7,000 staff and students, ~10,000 devices) on a school budget.

Schools face the same threats as any enterprise: phishing, account compromise, OAuth abuse, mass downloads and deprovisioned accounts that come back to life. My job is to catch them early and keep student and staff data safe.

## Featured

### gws-monitor · *private*

A security monitor for Google Workspace that shows the district what is happening across its accounts and data every day.

- **16 detectors** on the Admin SDK Reports API: logins, Drive, Gmail filters, OAuth tokens, admin grants, SAML, calendar, groups, mobile and device fleet, behavior baselines and messaging-domain trust
- **School-calendar-aware baselines** that expect testing weeks and the summer dip, without hiding a real incident
- **Tiered watch lists** (VIP / Tier 1 / Tier 2) with automatic promotion
- **FERPA retention**: 7-year audit log with a tamper-evident hash chain, per-user purge tooling and per-app retention floors
- **~2,000 unit tests**, an offline test harness and a per-detector coverage gate in CI

`Python` `SQLite` `pytest` `GAM` `Reports API`

The source is private because it runs against district data. I'm happy to walk through it in an interview.

### [slowroads-bridge](https://github.com/jomarpueyo/slowroads-bridge)

A side project that lets you ride the driving game *Slow Roads* on a Wahoo KICKR CORE smart trainer. It reads power over Bluetooth FTMS, simulates a road bike at 20 Hz, drives the game through a virtual Xbox controller and sets the trainer's resistance (ERG or road feel). It includes an in-game overlay, ride history with charts, hash-locked dependencies and a written security review.

`Python` `Bluetooth LE` `ViGEmBus` `pytest`

## Other work

Internal to the district:

- **Compromised-account response**: automated containment, blast-radius enumeration, OAuth token revocation and evidence capture
- **Staff off-boarding**: Drive archival, orphaned-file cleanup and access removal, fully audited
- **Chromebook fleet health**: GAM compliance scans with PowerShell dashboards
- **Gmail attachment policy**: enforced in three phases without a wave of help-desk tickets
- **Google Vault viewer**: HTML viewer for Texas Public Information Act requests
- **IncidentIQ → Google Chat**: ticket alerts as Chat cardsV2 messages

## Stack

**Languages:** Python · PowerShell · Bash · SQLite<br>
**Google:** Workspace Admin SDK · GAM · ChromeOS · Vault<br>
**Endpoint & identity:** Active Directory · Cisco Duo · Meraki MDM · KACE<br>
**Service desk:** IncidentIQ

## Certifications

CompTIA CySA+ · Security+ · Network+ · A+<br>
CompTIA CSAP · CSIS · CIOS (active through Dec 2028)

## Contact

[LinkedIn](https://linkedin.com/in/jomarpueyo) · jpueyo.work@gmail.com · Willis, TX
