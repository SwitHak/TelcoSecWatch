# Telecommunications Security Watch - 5

## WHITEPAPER - 6G - DOCOMO
- NTT DOCOMO released a position paper regarding 5G and 6G, having some thoughts on what 6G can be and gave some interesting projections.
- 5G is still not available broadly but we already thik about the next iteration of mobile networks: 6G !
- Source:
  - [White Paper 5G Evolution and 6G](https://www.nttdocomo.co.jp/english/binary/pdf/corporate/technology/whitepaper_6g/DOCOMO_6G_White_PaperEN_20200124.pdf)

## ARTICLE - 5G - BERTHUB.EU
- Very good article reminding us how we should also be preoccupied by 3PA (Third parties Access) and the competence externalisation which was driven by businesses departments.
- You should definitively read it !
- Source:
  - [5g Elephant In The Room](https://berthub.eu/articles/posts/5g-elephant-in-the-room/)

## HUAWEI- Situation Point
### UK
- UK decision was published this week: UK chose to keep Huawei inside their networks but under specific conditions.
- NCSC UK considered they can managed the Huawei risk and more broadly, defines what an HRV (High Risk Vendor) is.
- NCSC UK defines Huawei and ZTE as HRVs. Regarding that,following limitations / restrictions are mandatory:
  - No more than 35% per HRVs per UK Mobile Networks Operator;
  - Exclusion from sensitive locations, like around government building or UK forces;
  - Exclusion from sensitive networks;
  - Exclusion from core networks:
  
```
    - a. The cyber security risk of using HRVs in the network functions set out below cannot be managed. Therefore, if effective risk management of HRVs is to be undertaken, their products and services should not be used in the following network functions.
      - i. For all networks: 
         - IP Core
         - Security Functions
         - Operational Support Systems (OSS)
         - Management and Authentication, Authorisation and Audit (AAA) functions
         - Virtualisation infrastructure (including Network Function Virtualisation Infrastructure (NFVI))
         - Orchestrator and controller functions (including Management and Network Orchestration (MANO) and Software Defined Networks (SDN) orchestrators/controllers)
         - Network monitoring and optimization
         - Interconnection equipment
         - Internet gateway functions
         - Lawful Intercept related functions.
         
      - ii. For 5G networks: 5G Core database functions, 5G core-related services including but not limited to:
         - Authentication Server Function (AUSF)
         - Access and Mobility Management Function (AMF)
         - Unstructured Data Storage Function (UDSF)
         - Network Exposure Function (NEF)
         - Intermediate NEF (I-NEF)
         - Network Repository Function (NRF)
         - Network Slice Selection Function (NSSF)
         - Policy Control Function (PCF)
         - Session Management Function (SMF)
         - Unified Data Management (UDM)
         - Unified Data Repository (UDR)
         - User Plane Function (UPF)
         - UE radio Capability Management Function (UCMF)
         - Application Function (AF)
         - 5G-Equipment Identity Register (5G-EIR)
         - Network Data Analytics Function (NWDAF)
         - Charging Function (CHF)
         - Service Communication Proxy (SCP)
         - Security Edge Protection Proxy (SEPP)
         - Non-3GPP InterWorking Function (N3IWF)
         - Trusted Non-3GPP Gateway Function (TNGF)
         - Wireline Access Gateway Function (W-AGF)
         - and future 5G core functions as specified by 3GPP TS 23.501.
         
      - iii. For 4G networks: mobile core functions, including:
        - Home Subscriber Server (HSS)
        - Packet Gateway (PGW)
        - Policy and Charging Rules Function (PCRF)
        - and, in some cases, the Mobility Management Entity(MME) and Serving Gateway (SGW).
```

- Sources: 
  - [NCSC ADVICE ON THE USE OF EQUIPMENT FROM HIGH RISK VENDORS IN UK TELECOMS NETWORKS](https://www.ncsc.gov.uk/files/Advice-on-use-equipment-from-high-risk-vendors-in-UK-telecoms.pdf)
  - [The future of telecoms in the UK](https://www.ncsc.gov.uk/blog-post/the-future-of-telecoms-in-the-uk)
  - [5G Round-up](https://www.ncsc.gov.uk/information/5g-round-up)
  - [Summary of the NCSC’s security analysis for the UK telecoms sector](https://www.ncsc.gov.uk/files/Summary%20of%20the%20NCSCs%20security%20analysis%20for%20the%20UK%20telecoms%20sector.pdf)
  - [5G Explainer](https://www.ncsc.gov.uk/information/5g-explainer)

### GERMANY
- According to information from the Handelsblatt, the Americans presented a dossier to the federal government in mid-December that gathers the findings against Huawei that intelligence agencies and judicial authorities have collected. 
- A high-ranking delegation traveled to Berlin for this. 
- The delegation was led by Matthew Pottinger, the deputy security advisor to U.S. President Donald Trump. 
- He was accompanied by two senior NSC officers and FBI Deputy Director' David Bowdich.
- Some U.S. evidence presumed to be showed to federal government but not to the MPs, they are now asking to review the evidence.
- Source:
  - [„Smoking gun“: Streit um Beweise gegen Huawei](https://www.handelsblatt.com/politik/deutschland/5g-debatte-smoking-gun-streit-um-beweise-gegen-huawei/25484764.html)

### EUROPEAN UNION
- EU published its 5G toolbox the 29th January 2020.
- EU published its risk scenarios:
  - R1: Misconfiguration of networks
  - R2: Lack of access controls
  - R3: Low product quality
  - R4: Dependency on a single supplier
  - R5: State interference through 5G supply chain
  - R6: Exploitation of 5G networks by organised crime
  - R7: Significant disruption of crit. Infrastructures services 
  - R8: Massive failure due to power interruption
  - R9: IoT exploitation
  
- And proposed set of mitigating measures, divided in two categories (Strategic & Technical) and also set of action measures:

#### Strategic measures:
  - SM01: Strengthening the role of national authorities;
  - SM02: Performing audits on operators and requiring information;
  - SM03: Assessing the risk profile of suppliers and applying restrictions for suppliers considered to be high risk - including necessary exclusions to effectively mitigate risks- for key assets;
  - SM04: Controlling the use of Managed Service Providers (MSPs) and equipment suppliers’ third line support;
  - SM05: Ensuring the diversity of suppliers for individual MNOs through appropriate multivendor strategies;
  - SM06: Strengthening the resilience at national level;
  - SM07: Identifying key assets and fostering a diverse and sustainable 5G ecosystem in the EU;
  - SM08: Maintaining and building diversity and EU capacities in future network technologies.

#### Technical measures:
  - TM01: Ensuring the application of baseline security requirements (secure network design and architecture);
  - TM02: Ensuring and evaluating the implementation of security measures in existing 5G standards;
  - TM03: Ensuring strict access controls;
  - TM04: Increasing the security of virtualised network functions;
  - TM05: Ensuring secure 5G network management, operation and monitoring;
  - TM06: Reinforcing physical security;
  - TM07: Reinforcing software integrity, update and patch management;
  - TM08: Raising the security standards in suppliers’ processes through robust procurement conditions;
  - TM09: Using EU certification for 5G network components, customer equipment and/or suppliers’ processes;
  - TM10: Using EU certification for other non 5G-specific ICT products and services (connected devices, cloud services);
  - TM11: Reinforcing resilience and continuity plans.

#### Set of targeted supporting actions:
  - SA01: Reviewing or developing guidelines and best practices on network security;
  - SA02: Reinforcing testing and auditing capabilities at national and EU level;
  - SA03: Supporting and shaping 5G standardisation;
  - SA04: Developing guidance on the implementation of security measures in existing 5G standards;
  - SA05: Ensuring the application of standard technical and organisational security measures through specific EU-wide certification scheme;
  - SA06: Exchanging best practices on the implementation of strategic measures, in particular national frameworks for assessing the risk profile of suppliers;
  - SA07: Improving coordination in incident response and crisis management;
  - SA08: Conducting audits of interdependencies between 5G networks and other critical services;
  - SA09: Enhancing cooperation, coordination and information sharing mechanisms;
  - SA10: Ensuring 5G deployment projects supported with public funding take into account cybersecurity risks 

- You should review Annex 1 (page 20) for a dedicated analysis of each measure or supporting action.
- Sources:
  - [Cybersecurity of 5G networks EU Toolbox of risk mitigating measures](https://ec.europa.eu/newsroom/dae/document.cfm?doc_id=64468)
  - [Secure 5G networks: Commission endorses EU toolbox and sets out next steps](https://ec.europa.eu/digital-single-market/en/news/cybersecurity-5g-networks-eu-toolbox-risk-mitigating-measures)
  - [Commission endorses EU toolbox to secure 5G networks](https://ec.europa.eu/commission/presscorner/api/files/document/print/en/ip_20_123/IP_20_123_EN.pdf)

## United States of America
- Some senators aren't very happy regarding UK decision to keep Huawei inside their networks.
- Source:
  - [U.S. Disappointed as Johnson Gives Huawei Partial 5G Role](https://www.bloomberg.com/news/articles/2020-01-28/u-k-allows-huawei-to-build-5g-networks-in-break-with-u-s)

## France
- Orange France, French ISP chose Ericsson & Nokia for its 5G networks in Metropolitan area only.
- We still don't know for the SFR & Bouygues Télécom ISPs, Free already confirmed an exclusive agreement with Nokia for its 5G networks.
- Huawei was at a big french conferences meeting the International Cybersecurity Forum (FIC) and two whitepapers were available on its stand and gave also a technical security talk on 5G which was interesting.
- Sources:
  - [Orange ISP](https://www.orange.com/fr/Press-Room/communiques/communiques-2020/Orange-selectionne-Nokia-et-Ericsson-en-tant-qu-equipementiers-pour-le-deploiement-du-reseau-5G-en-France-metropolitaine)
  - [Ericsson Vendor](https://www.ericsson.com/en/press-releases/2020/1/orange-france-selects-ericsson-for-5g)
  - [Nokia Vendor](https://www.nokia.com/about-us/news/releases/2020/01/31/nokia-signs-5g-deal-with-orange-france/)
  - [Free Agreement](https://www.iliad.fr/presse/2019/CP_020919.pdf)
  - [HUAWEI WP: Towards a Trustworthy Foundation to Enhance the Security of EU 5G Networks](https://www.huawei.eu/file-download/download/public/2504)
  - [HUAWEI WP: Partnering with the Industry for 5G Security Assurance](https://www-file.huawei.com/-/media/corporate/pdf/trust-center/huawei-5g-security-white-paper-4th.pdf)

## INFORMATION - DATALEAK - SPRINT
- Sprint Social care a support internal platform was exposed. This exposed sensitive data and also instructions and manual to access Sprint Internal tools.
- Source:
  - [Krebs Article](https://krebsonsecurity.com/2020/01/sprint-exposed-customer-support-site-to-web/)

#### Postscriptum
If you spotted errors, missing information or anything you want to report, feel free to contact me on Twitter: [@SwitHak](https://twitter.com/swithak/)

**SwitHak**
