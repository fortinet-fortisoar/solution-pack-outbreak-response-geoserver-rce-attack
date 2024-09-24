# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

A remote code execution vulnerability within GeoServer is currently under active exploitation, with recent incidents targeting 40,000 sensors. This vulnerability is being exploited by the Earth Baxia APT group, as reported by FortiGuard Recon. The root cause of this vulnerability lies in the absence of proper input validation during request handling, posing a significant risk of system compromise upon successful exploitation. 

 The **Outbreak Response - GeoServer RCE Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.0.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*, *QRadar*, *Splunk*, and *Azure Log Analytics*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/geoserver-rce) contains information about the outbreak alert **Outbreak Response - GeoServer RCE Attack**. 

## Background: 

GeoServer is an open-source platform designed for the purpose of sharing geospatial data. Recently, the Cybersecurity and Infrastructure Security Agency (CISA) included this particular vulnerability in its list of Known Exploited Vulnerabilities (KEV), just a couple of months ago. 

## Announced: 

 

## Latest Developments: 

September 5, 2024: FortiGuard Labs analysis of the threat
https://www.fortinet.com/blog/threat-research/threat-actors-exploit-geoserver-vulnerability-cve-2024-36401 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|