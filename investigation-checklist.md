### Initial Setup
- [ ] Generate prefix (if necessary)
- [ ] Generate name
- [ ] Create [actor template](/templates/actor.json) and open PR

### Initial Search
- [ ] Google search
- [ ] [ThreatConnect](http://threatconnect.com)
- [ ] [VirusTotal](https://www.virustotal.com)
    - [ ] Hashes
    - [ ] URLs
    - [ ] IPs
    - [ ] Domains
- [ ] [PassiveTotal](https://www.passivetotal.org)
- [ ] [OpenDNS Umbrella](https://sgraph.opendns.com/main)
- [ ] Look for malware samples
    - [ ] [MalShare](http://malshare.com)
    - [ ] [SARVAM](http://sarvam.ece.ucsb.edu/home)
    - [ ] [VirusTotal](https://www.virustotal.com) - If accessible
    - [ ] [VirusShare](http://virusshare.com)
    - [ ] [Totalhash](http://totalhash.com)
- [ ] WHOIS history via [DomainTools](http://domaintools.com)

### Deconflict
- [ ] Check indicators against other groups
- [ ] Identify alternative group names (CrowdStrike)

### Ongoing Monitoring
- [ ] Set up Google Alerts
- [ ] Set up PassiveTotal Monitoring
- [ ] Set up [Scumblr](https://github.com/netflix/scumblr)
- [ ] Write YARA rules
- [ ] Deploy detections
