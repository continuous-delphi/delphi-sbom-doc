# delphi-sbom-doc

Documentation and resources for SBOM requirements for Delphi Developers

<img width="400" height="266" alt="image" src="https://github.com/user-attachments/assets/6c9b8b89-6de5-4383-b051-19823613aae3" />

## Reference Links
- [Cyber Resilience Act](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)
- [Digital Operational Resilience Act (DORA)](https://www.eiopa.europa.eu/digital-operational-resilience-act-dora_en)
- [OWASP Foundation standard - ClycloneDX](https://cyclonedx.org/)
  - [Authoritative Guide to SBOM](https://cyclonedx.org/guides/OWASP_CycloneDX-Authoritative-Guide-to-SBOM-en.pdf)
- [CISA-Software Bill of Materials](https://www.cisa.gov/sbom)
- [EU Cyber Resilience Act](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)
- [NTIA Minimum Elements for a Software Bill of Materials](https://www.ntia.gov/report/2021/minimum-elements-software-bill-materials-sbom)

## General Links

- `2026.04.21` **Intentional Delphi Blog** [SBOMgen: Open Source](https://wmeyer.tech/2026/04/21/sbomgen-open-source/)
  - Introducing SBOMgen: A Free SBOM Generator for Delphi
  - It parses MAP and DPR files to detect third-party and internal components, collects package metadata, and produces CycloneDX 1.6 JSON output validated against both the official CycloneDX CLI validator and the CycloneDX web validator with all options enabled — strict validation, best practices, Package URL validation, and SPDX license identifier validation.
  - [Reddit Post](https://www.reddit.com/r/delphi/comments/1sr8bsq/sboms_and_delphi_the_challenge_of_a_mature_build/)
- `2026.04.20` **Intentional Delphi Blog** [SBOMs and Delphi: The Challenge of a Mature Build Pipeline](https://wmeyer.tech/2026/04/20/sboms-and-delphi-the-challenge-of-a-mature-build-pipeline/)
- `2026.04.13` **Intentional Delphi Blog** [SBOM Publisher Responsibilities: What the Regulations Actually Require](https://wmeyer.tech/2026/04/13/sbom-publisher-responsibilities-what-the-regulations-actually-require/)
- `2026.04.07` **Intentional Delphi Blog** [How Does an SBOM Actually Protect You?](https://wmeyer.tech/2026/04/07/how-does-an-sbom-actually-protect-you/)
- `2026.04.05` **Peganza Announcement** [Create an SBOM with Pascal Analyzer!](https://peganza.com/create-sbom-with-pascal-analyzer.html)
- `2026.04.03` **Intentional Delphi Blog** [What Is an SBOM, and Why Should Developers Care?](https://wmeyer.tech/2026/04/03/what-is-an-sbom-and-why-should-developers-care/)
- `2026.03.26` **Delphi-PRAXiS Forum** [https://en.delphipraxis.net/topic/15251-ann-march-updates-for-pascal-analyzer-pascal-expert-and-pascal-browser/](https://en.delphipraxis.net/topic/15251-ann-march-updates-for-pascal-analyzer-pascal-expert-and-pascal-browser/)
  - New `Security Report` announcement
- `2026.03.18` **Twitter Post** Olaf Monien [Just open-sourced DX.Comply: One-click SBOM generation for Delphi projects](https://x.com/omonien/status/2034424004258263432)
- `2026.02.09` **Blog Article** ERPwerk `Embarcadero Consulting Partner` [The-importance-of-sbom-for-delphi-developers-in-2023](https://www.delphientwickler.de/en/delphi-news.html)
- `2026.02.08` **Embarcadero Blog** [What Is SBOM And Why Is It So Important This Year?](https://blogs.embarcadero.com/what-is-sbom-and-why-is-it-so-important-this-year/)
  + Related YouTube Video [What is SBOM and Why is it so Important This Year?](https://youtu.be/q302LR0nlmU)
  > SCA, SBOM, Dora, CRA - that’s a whole load of acronyms flying around! This year has started out with a huge clutch of new EU and US software and data security laws. SCA and SBOM in particular are two things you are probably going to need to understand, and provide, in order to comply with the regulations and even continue to sell to certain markets. It’s not FUD, it’s a fact.
  > Join Embarcadero Developer Advocate Ian Barker and special guest Valerie Kim (Der Scanner) and get the details on what these regulations are and have Valerie demonstrate how to automatically scan your software for vulnerabilities and produce that all-important SBOM report.
- `2026.01.09` **DerScanner Blog** [https://derscanner.com/blog/delphi-sca-release](https://derscanner.com/blog/delphi-sca-release)
- `2023.06.26` **Delphi-PRAXiS Forum** [https://en.delphipraxis.net/topic/9303-sbom-tool-for-delphi/](https://en.delphipraxis.net/topic/9303-sbom-tool-for-delphi/)


## Open Source Solutions

### DX.Comply

DX.Comply produces standards-compliant CycloneDX 1.5 SBOMs

- Repo: [https://github.com/omonien/DX.Comply](https://github.com/omonien/DX.Comply)
- Author: [https://github.com/omonien](https://github.com/omonien)

### SBOMgen

Generates CycloneDX 1.6 Software Bills of Materials (SBOMs) for Delphi applications. 

- Repo: [https://github.com/wmeyer48/SBOMgen](https://github.com/wmeyer48/SBOMgen)
- Author: [https://github.com/wmeyer48](https://github.com/wmeyer48)


### DelphiSBOM

A CycloneDX 1.5 SBOM (Software Bill of Materials) generator for Delphi applications.

- Repo: [https://codeberg.org/GITLAK/DelphiSBOM](https://codeberg.org/GITLAK/DelphiSBOM)
- Author: [https://github.com/wmeyer48](https://codeberg.org/GITLAK)

### sbom-tool

The SBOM tool is a highly scalable and enterprise ready tool to create SPDX 2.2 compatible SBOMs for any variety of artifacts.

- Repo: [https://github.com/microsoft/sbom-tool](https://github.com/microsoft/sbom-tool)
- Author: [https://github.com/microsoft](https://github.com/microsoft)

## Commercial Solutions

### Pascal Analyzer

- Product Page: [https://peganza.com/products_pal.html](https://peganza.com/products_pal.html)
- Online Help: [https://peganza.com/PALHelp/index.html?security_report.htm](https://peganza.com/PALHelp/index.html?security_report.htm)
- YouTube: [The Pascal Analyzer Family of Products](https://youtu.be/i2UkzpKyfVg)
  
### DerScanner

- Product Page: [https://derscanner.com/product/delphi](https://derscanner.com/product/delphi)
