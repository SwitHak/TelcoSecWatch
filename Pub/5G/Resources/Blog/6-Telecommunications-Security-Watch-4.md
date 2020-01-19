# Telecommunications Security Watch - 4

# Happy New Year 2020 !

## CONFERENCE - 36c3 
- Some interesting talks from 36c3 Conference:
  - [Der Pfad von 4G zu 5G](https://fahrplan.events.ccc.de/congress/2019/Fahrplan/events/10542.html)
  - [SIM card technology from A-Z](https://fahrplan.events.ccc.de/congress/2019/Fahrplan/events/10737.html)
  - [SigOver + alpha](https://fahrplan.events.ccc.de/congress/2019/Fahrplan/events/10801.html)

## RESEARCH - COAX - Cable Haunt
- Very interesting & impacting vulnerabilities has been discovered by LyreBirds company.
- Vulnerabilities regarding how coax modem are vulnerable to DNS rebind attacks, default credentials & a programming bug in the spectrum analyzer) CVE-2019-19494 or Technicolor specific one CVE-2019-19495
- Sources
  - [LyreBirds BlogPost](https://cablehaunt.com/)
  - [PDF Document](https://github.com/Lyrebirds/Cable-Haunt-Report/releases/latest/download/report.pdf)
  - [Script to test the vulnerability](https://github.com/Lyrebirds/cable-haunt-vulnerability-test)
  
  
## RESEARCH - SMS 2FA - Is SMS 2FA Secure? No!
- A very interesting study was released by Kevin Lee, Ben Kaiser, Jonathan Mayer & Arvind Narayanan, comparing what are the verifications for 5 major U.S. telecommunication providers during the renew of a sim card also named SIMSwap attack.
- Conclusions are bad, all five carriers use insecure authentication challenges that can easily be subverted by attackers.
- There's also a study of which sites used SMS 2FA to recover account property, results are bad too.
- Source:
  - [ISSMS5FASECURE.com](https://www.issms2fasecure.com/)
  - [Study PDF](https://www.issms2fasecure.com/assets/sim_swaps-01-10-2020.pdf)
  - [Websites 2FA Dataset](https://www.issms2fasecure.com/dataset)


## ARTICLE - Hackers Are Breaking Directly Into Telecom Companies to Take Over Customer Phone Numbers
- A really good article by Joseph Cox on a less-knowned threat in telecommunications services providers service desks.
- This article shows by tricking service desks employees, attackers obtained access to internals tools of CSP and managed to use the softwares as an employee.
- This flaw permits to attackers to easily manage to take the control of a number.
- Interestingly, the findings come just a day after a group of U.S. senators sent a letter to FCC asking what FCC did/doing/will do against these threats.
- Sources:
  - [MortherBoard Article](https://www.vice.com/en_us/article/5dmbjx/how-hackers-are-breaking-into-att-tmobile-sprint-to-sim-swap-yeh)
  - [U.S. Senators Letter to FCC](https://www.wyden.senate.gov/imo/media/doc/010920%20SIM%20Swap%20Scam%20Letter%20to%20FTC.pdf)


## HUAWEI- Situation Point
### UK
- Amid of the battle between China and U.S.A., UK is expected to publish his decision on Huawei.
- Recently, U.S.A. strengthen the pressure against UK again and again, threatening to cut intelligence feeds.
- The latter threat take a new stance when U.S. senators submitted a project bill regarding the matter. (CF USA part)
- Even with this threats UK seems to haven't listened its technical authorities like HCSEC, NCSC, GCHQ, NSC, ... and Johnson made some statements in this way.
- Sources: 
  - [Huawei deal ‘would let fox loose in chicken coop’, says GCHQ](https://www.thetimes.co.uk/article/huawei-deal-would-let-fox-loose-in-chicken-coop-says-gchq-tvnnnv7x6?shareToken=c18dbcb97babf95ef15ee8f3c92b25f5)
  - [Huawei and 5G: Why the UK's decision is getting tougher every day](https://www.zdnet.com/article/the-uks-decision-on-5g-and-huawei-is-getting-harder-every-day/)
  
### India
- India announced its decision regarding Huawei in trials part. 
- Huawei was granted telecom frequences as all others vendors who've asked the india government.
- Source:
  - [India allows Huawei to participate in 5G trials](https://economictimes.indiatimes.com/industry/telecom/telecom-news/govt-will-give-5g-spectrum-for-trials-to-all-players-prasad/articleshow/73033442.cms)

### GERMANY
- After the CDU motion against Huawei in November 2019, Merkel position is fragilized.
- Even more after the recent threats by China to german automakers, the ones that have a great lobbying capabilities in Germany and also Brussels.
- The China’s ambassador to Germany, Wu Ken, threatened clearly in one speech germans automakers regarding the china market of retaliations.
- Source:
  - [China threatens Germany with retaliation if Huawei is banned: Report](https://www.rcrwireless.com/20191216/5g/china-threatens-germany-retaliation-huawei-banned-report)

### EUROPEAN UNION
- The new DSM director, the french Thierry BRETON, made a strong statement for a strong European independance. One sentence got us “Any company, European or not, will be welcome provided of course that they abide by our European rules. We will not build a European fortress.”.
- This statement is also against a recent german one, The new DSM director made an important call regarding 5G security, that will not impede the 5G deployment timeline: "Setting up strict security conditions will not create delays in the roll out of 5G in Europe,"
- Source:
  - [EU Industry Chief Dismisses Fears Strict Security Rules Could Delay 5G](https://www.nytimes.com/reuters/2020/01/19/business/19reuters-eu-telecoms-exclusive.html)

## United States of America
- U.S.A. senator Cotton increased the pressure by submitting a bill banning intelligence sharing with countries using Huawei.
- The bill is fullly reproduced below:
    ```
    SECTION 1. PROHIBITION ON SHARING OF UNITED STATES
    INTELLIGENCE WITH COUNTRIES THAT PER5 MIT OPERATION OF HUAWEI FIFTH GENERA6 TION TELECOMMUNICATIONS TECHNOLOGY WITHIN THEIR BORDERS.
    (a) PROHIBITION.—Intelligence of or under the control of the United States, including intelligence products of the intelligence community, may not be shared with any country that permits operation within its national borders of fifth generation (5G) telecommunications technology of Huawei Technologies Co. Ltd..
    (b) DEFINITIONS.—In this section, the terms ‘‘intelligence’’ and ‘‘intelligence community’’ have the meaning given such terms in section 3 of the National Security Act of 1947 (50 U.S.C. 3003).
     ```

- Another interesting bill is the "Utilizing Strategic Allied (USA) Telecommunications Act" which aims to create two funds:
  - Public Wireless Supply Chain Innovation Fund (PWSCIF): 5 percent of the proceeds or $750,000,000
  - Multilateral Tele2 communications Security Fund (MTSF): $500,000,000
- Interestingly, the bill oriented again part of the fund to support namely the O-RAN project. This is not the first time we heard that.

- Another case, the trial for Huawei CFO (Meng Wanzhou) will start the 2020-01-20 in Vancouver, the Vancouver court will choose or not to validate the extradition of the Huawei CFO to the United States of America.

- Sources
  - [Bill: Utilizing Strategic Allied (USA) Telecommunications Act](https://www.warner.senate.gov/public/_cache/files/2/3/2365fc6a-422c-4df2-837b-f297bb293ad2/E8131EF8149D5D0E1411683ABC3DECCD.oll20034.pdf)
  - [Bill: Banning Intelligence Sharing With Countries Using Huawei](https://www.cotton.senate.gov/files/documents/Huawei%205G%20Security.pdf)
  - [Huawei CFO Extradition hearings](https://www.reuters.com/article/us-usa-huawei-tech-canada/lawyers-for-huawei-cfo-call-canada-prosecutors-arguments-circular-idUSKBN1ZG2IE)
  - [Extradition hearing of Meng Wanzhou, Huawei executive at the center of U.S.-Canada-China rift, to open in Vancouver](https://www.washingtonpost.com/world/the_americas/extradition-hearing-of-meng-wanzhou-huawei-executive-at-the-center-of-us-canada-china-rift-opens-in-vancouver/2020/01/17/97fc78a6-37d3-11ea-a1ff-c48c1d59a4a1_story.html)
  
  
## WHITEPAPER - 5G - What to Make of the Huawei Debate? 5G Network Security and Technology Dependency in Europe
- Good whitepaper which propose a new option "strategic access" which consists of two major principles:
  - Diversification of supply chains
  - Light European protectionism regarding the european 5G companies
- In my humble opinion, the paper lacks of technicals insights, especially regarding espionage and sabotage by U.S. companies, also on the cases regarding Huawei; But the 4th option is really interesting and could lead the DSM to strenghten its forces. 
- Source:
  - [WHITEPAPER PDF](https://www.ui.se/globalassets/ui.se-eng/publications/ui-publications/2020/ui-paper-no.-1-2020.pdf)


## INFORMATION - Internet shutdowns
- [Internet disrupted in Iran amid fuel protests in multiple cities regarding Soleimani strike](https://twitter.com/anakin_ww/status/1216061024492773377?s=20)


#### Postscriptum
If you spotted errors, missing information or anything you want to report, feel free to contact me on Twitter: [@SwitHak](https://twitter.com/swithak/)

**SwitHak**
