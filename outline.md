## Introduction

- Scott Intro
- Kyle Intro
- Relationship Intro

## Main Point 1: Targeting - Figuring Out What to Hunt

#### Slide: Intelligence Cycle

- Requirements
- Collection
- Procesessing
- Exploitation
- Analysis
- Dissemination/Lessons Learned

Obvious, but needs to be said.

#### Slide: Data vs Intelligence

- Data is a raw fact
- Intelligence is contextualized, structured data, after being worked through a process

Obvious, but needs to be said.

#### Slide: F3EAD

- Breakdown F3EAD
- Classify Actions
- About combining operations & intelligence

A process that combines IR Operations & Threat Intelligence

#### Slide: Actors vs Malware vs Indicators

- This things get confused a lot: Havex (is it malware or an actor?)

### Key Point 1: Threat Intelligence

- Starting Incidents & Research Priorities...
- Answering the What question...

#### Slide: Feeds
- High Signal to Noise
- The more purpose specific the better
- Don't be afraid to do your own filtering (seriously, do your own filtering)
- Automate or die
- Maltrieve

#### Slide: Honeypots

- Useful for understanding

#### Slide: Honeypots - High Interaction vs Low Interaction

- High Interaction: Dangerous but Highly Useful
- Low Interaction: Safer & Moderately Useful

#### Slide: Honeypots - Software

- Kippo
- Dionaea
- Glastopf
- [Modern Honey Network](https://github.com/threatstream/mhn)

#### Slide: Feeds

- Maltrieve

#### Slide: Vendor Threat Reports & Blogs (Krebsing)
- APT1
- Day to day vendor Posts
- Independent Researchers

#### Slide: Bucket List

- Personal aside:

### Key Point 2: "Vertical Based" Targeting

#### Slide: Logic: Deadpool
#### Slide: Logic: Retailers vs DIB vs Financials
#### Slide: Peers: Not general, this is about asking "What threats are you facing?"
#### Slide: Vendors
- There are organizations that will help you determine who are the threats based on your business.

### Key Point 3: Internal Incidents

#### Slide: Mining your incident management system

#### Slide: Squeaky Wheels

#### Slide: Honeypots & DNS Sinkholes

## Main Point 2: The Hunt - Searching for Your Target (Kyle)

### Key Point 1: OSINT

### Key Point 2: Forensics & RE


### Key Point 3: ?

## Main Point 3: The Kill - Response (Kyle)

### Key Point 1: Internal IR

### Key Point 2: Dissemination

### Key Point 3: Continue the Cycle

## Main Point 4: Hunting Stories

#### Slide: Product Quality
- Concise
- Timely
- Factual
- Actionable

#### Slide: Product - RFIs
- Quick short responses to specific questions

#### Slide: Product - Short Form Products

#### Slide: Product - Long Form Products
- Target Packages

#### Slide: Product - IOCs
- Structured representations of common threat data
- Please no

#### Slide: Product - IOCs - [MITRE: Stix](http://stix.mitre.org)
- "Ugggh... XML"
- Minimum Tooling

#### Slide: Product - IOCs - [Mandiant/FireEye: OpenIOC](http://openioc.org)
- "Ugggh... XML"
- Minimum Tooling

#### Slide: Product - IOCs - Network: Snort Signatures
- A vendor specific format almost everyone supports

#### Slide: Product - IOCs - Host: Yara
- It's not just for malware (Moloch processes it)
- But it is aggressively malware centric

#### Slide: Audience - Internal Sharing
- Shows Value
- Enhances Collaboration & Unexpected Benefits

#### Slide: Audience - Formal Trust Groups
- Mailing Lists
- Sites
  - ThreatConnect

#### Slide: Audience - Informal Trust Groups
- Built on Trust
- Smaller is Better (And don't be afraid to remove people (and if you're worried you can't trust someone after you remove them you never should have added them))

#### Slide: Audience - Full disclosure style


## Conclusion/Review
- Target -> Hunt -> Kill -> Stories -> Repeat

## "Outroduction"

- Sources & Thanks
- Contact Information
- Thanks
- ???

---

## Detailed Outline (Shmoo)

- Places to start
  - "Threat Information" (We'll talk about making it Intelligence)
  - "Vertical Driven" Targeting
  - Public reports
  - Existing caseload
  - Honeypots and logs
- What to analyze
  - Check hashes in public malware repos
  - Passive DNS data on IPs / domains
  - Historical WHOIS
- How to keep tracking
  - Threat "library"
  - Alerting types
    - Web Monitoring Systems
    - Malware & Network Monitoring
    - Traditional Security Infrastructure
- Work with fellow hunters
  - Internal Sharing
  - Trust groups
  - Full disclosure style
