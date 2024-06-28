# Oplium Threat Labs - Indicators of Compromise (IOCs)

Welcome to the **Oplium Threat Labs - Indicators of Compromise (IOCs)** repository. This repository is dedicated to centralizing and sharing threat information, specifically IOCs, discovered and discussed in our publications.

## Objectives

The primary objectives of this repository are:
- **Centralization of Threat Data**: To create a centralized repository for all IOCs identified by Oplium Threat Labs, making it easier for the cybersecurity community to access and utilize this information.
- **Community Sharing**: To share threat intelligence with the global cybersecurity community, promoting collaborative defense efforts.
- **Enhancing Cyber Defense**: To provide actionable intelligence that can be used by organizations and individuals to bolster their cyber defense strategies.

## What Are Indicators of Compromise (IOCs)?

Indicators of Compromise are artifacts observed on a network or in an operating system that indicate a potential intrusion. These artifacts can include:
- IP addresses
- Domain names
- File hashes (MD5, SHA-1, SHA-256)
- URLs
- Email addresses
- Registry keys
- File paths

## How to Use This Repository

This repository contains IOCs categorized by different threat reports and publications from Oplium Threat Labs. Each IOC file includes relevant details such as the type of IOC, associated threat actor, and context of the threat.

### Repository Structure

- **/reports/**: Contains subdirectories for each report or publication, with corresponding IOC files.
  - **/report_name/**: Directory for a specific report.
    - **iocs.csv**: A CSV file containing IOCs related to the report.
    - **iocs.json**: A JSON file for easy integration with security tools.
    - **README.md**: Details about the report and the associated IOCs.

### Example

```
/reports/
  /ransomware_campaign_june2024/
    - iocs.csv
    - iocs.json
    - README.md
```

## Contributing

We welcome contributions from the community. Here’s how you can contribute:
1. **Submit IOCs**: If you have identified IOCs that are not listed here, please submit them via a pull request.
2. **Report Issues**: If you find any discrepancies or have suggestions for improvement, please open an issue.
3. **Collaborate**: Join our [discussion forum](https://github.com/orgs/OpliumThreatLabs/discussions) to discuss threats and share insights.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact Us

For more information, you can reach out to us via:
- **Email**: [labs@oplium.com](mailto:labs@oplium.com)
- **Website**: [Oplium Threat Labs](https://oplium.com/threatlabs)

---

Together, we can enhance our collective defense against cyber threats by sharing knowledge and resources. Thank you for your contributions and support!
