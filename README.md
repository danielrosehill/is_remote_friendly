# is_remote_friendly

[![CSV Data](https://img.shields.io/badge/Data-CSV-blue)](remote_restrictions.csv)
[![JSON Data](https://img.shields.io/badge/Data-JSON-blue)](remote_restrictions.json)

## Table of Contents

- [Remote-friendly, with caveats](#remote-friendly-with-caveats)
  - [Candidate geography restrictions](#candidate-geography-restrictions)
  - [Time-Zone Specific](#time-zone-specific)
  - [Misc Requirements](#misc-requirements)
- [Objective](#objective)

# Remote-friendly, with caveats

This repository aims to provide a detailed taxonomy of remote-friendliness caveats that companies often impose on remote positions.

Here are some of the more common restrictions. The restriction for remote employees to be in the office > 0 days per week is not included among them as those companies are **hybrid**.

## Candidate geography restrictions

### US-Only

By far the most common restriction facing international candidates for remote positions is a US only requirement. This requirement excludes all non-US-based candidates from being able to access these positions.

### EU-only

For bureaucratic reasons, another common requirement is that remote applicants need to be located in a European Union (EU) member state.

### Our Country Only

For lack of a better word, a less common, but still frequently encountered restriction is that the company will only hire candidates which are based in its own country. This restriction may be imposed particularly to avoid the bureaucratic complications of hiring international employees (rather than contractors). 

### Specific State/Province Only (US)

Companies may restrict remote positions to candidates residing in a specific state or province, potentially due to tax or legal reasons.

### Whitelist

Companies may specify that remote candidates must be located in one of several approved countries.

### Blacklist

Companies may exclude candidates from certain countries, although this is less common.

## Time-Zone Specific 

Working remotely when you are in a significantly different time zone than the company can be very challenging and therefore a commonly encountered restriction is that companies will only hire candidates which are within a certain timezone offset relative to that of their main office. 

This may be expressed as:

### Time zone specific

For convenience, companies will commonly state that the candidates need to be located in a specific time zone (e.g. EST, PST). 

### Offset specific

In other cases, rather than list all the individual time zones on the same offset against GMT companies will sometimes specify the offset in hours. 

For example: "open to international candidates who are located within 3 hours difference of GMT."

## Misc Requirements

### Internet Speed Requirements

Some companies may require remote employees to have a minimum internet speed to ensure productivity and effective communication.

### Background Check Requirements

Certain roles, especially those involving sensitive data, may necessitate background checks for remote employees, regardless of location.

### Data Security Restrictions

Companies might impose restrictions on the type of devices or networks that remote employees can use to access company data, to minimize security risks.

### On-site Visit Requirements

Some companies might require occasional on-site visits for team meetings, training, or other purposes, even for fully remote roles.

### Equipment Provisioning Restrictions

Clarify whether the company provides equipment (laptops, monitors, etc.) or if the remote employee is expected to use their own.

---

## Objective

My objective in creating this repository was to come up with a simple data taxonomy for personal use stratifying companies' according to their level of remote friendliness.