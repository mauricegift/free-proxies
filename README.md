# free-proxies

> **647 working validated proxies** last updated on **Sunday 05-04-2026 15:07:39 EAT**

Free, continuously validated **HTTP**, **SOCKS4** and **SOCKS5** proxies scraped from 20+ sources, tested live, and organised by protocol and country. Updated every **20 minutes**.

![HTTP](https://img.shields.io/badge/HTTP-202-blue?style=flat-square)
![SOCKS4](https://img.shields.io/badge/SOCKS4-144-green?style=flat-square)
![SOCKS5](https://img.shields.io/badge/SOCKS5-301-purple?style=flat-square)
![Countries](https://img.shields.io/badge/Countries-63-orange?style=flat-square)

---

## Quick download

| Protocol | Count | Raw URL |
|----------|------:|---------|
| HTTP | 202 | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/http.json` |
| SOCKS4 | 144 | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/socks4.json` |
| SOCKS5 | 301 | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/socks5.json` |
| Combined | 647 | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/proxies.json` |
| Random 100 | — | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/random.json` |
| Metadata | — | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/metadata.json` |
| Timestamp | — | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/timestamp.json` |
| Logs | — | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/proxies.log` |

## File format

All files are JSON. Protocol files contain:
```json
{ "proxies": ["1.2.3.4:8080", "5.6.7.8:3128"] }
```
`proxies.json` combines all three:
```json
{ "http": [...], "socks4": [...], "socks5": [...] }
```
`random.json` holds up to 100 randomly sampled entries in `protocol://ip:port` form.

## Countries (63)

Per-country files live at `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/<CC>.json`.

| Code | Country | Count | Link |
|------|---------|------:|------|
| AR | Argentina | 11 | [AR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/AR.json) |
| AU | Australia | 5 | [AU.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/AU.json) |
| BA | Bosnia and Herzegovina | 1 | [BA.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BA.json) |
| BD | Bangladesh | 21 | [BD.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BD.json) |
| BF | Burkina Faso | 1 | [BF.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BF.json) |
| BG | Bulgaria | 5 | [BG.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BG.json) |
| BR | Brazil | 17 | [BR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BR.json) |
| BW | Botswana | 1 | [BW.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BW.json) |
| CA | Canada | 1 | [CA.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/CA.json) |
| CL | Chile | 2 | [CL.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/CL.json) |
| CN | China | 10 | [CN.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/CN.json) |
| CO | Colombia | 20 | [CO.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/CO.json) |
| DE | Germany | 5 | [DE.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/DE.json) |
| EC | Ecuador | 7 | [EC.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/EC.json) |
| EG | Egypt | 1 | [EG.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/EG.json) |
| ES | Spain | 2 | [ES.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/ES.json) |
| FI | Finland | 4 | [FI.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/FI.json) |
| FR | France | 4 | [FR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/FR.json) |
| GB | United Kingdom | 60 | [GB.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/GB.json) |
| GE | Georgia | 1 | [GE.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/GE.json) |
| HK | Hong Kong | 6 | [HK.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/HK.json) |
| HN | Honduras | 1 | [HN.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/HN.json) |
| HR | Croatia | 1 | [HR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/HR.json) |
| HU | Hungary | 1 | [HU.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/HU.json) |
| ID | Indonesia | 55 | [ID.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/ID.json) |
| IN | India | 20 | [IN.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/IN.json) |
| IQ | Iraq | 1 | [IQ.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/IQ.json) |
| IT | Italy | 1 | [IT.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/IT.json) |
| JP | Japan | 19 | [JP.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/JP.json) |
| KE | Kenya | 2 | [KE.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/KE.json) |
| KH | Cambodia | 4 | [KH.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/KH.json) |
| KR | South Korea | 7 | [KR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/KR.json) |
| LK | Sri Lanka | 1 | [LK.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/LK.json) |
| LS | Lesotho | 1 | [LS.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/LS.json) |
| LT | Lithuania | 1 | [LT.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/LT.json) |
| LV | Latvia | 1 | [LV.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/LV.json) |
| LY | Libya | 1 | [LY.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/LY.json) |
| MM | Myanmar | 1 | [MM.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/MM.json) |
| MX | Mexico | 12 | [MX.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/MX.json) |
| MY | Malaysia | 2 | [MY.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/MY.json) |
| NL | The Netherlands | 12 | [NL.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/NL.json) |
| NP | Nepal | 2 | [NP.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/NP.json) |
| PA | Panama | 1 | [PA.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/PA.json) |
| PE | Peru | 3 | [PE.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/PE.json) |
| PH | Philippines | 5 | [PH.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/PH.json) |
| PK | Pakistan | 2 | [PK.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/PK.json) |
| PL | Poland | 7 | [PL.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/PL.json) |
| PT | Portugal | 1 | [PT.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/PT.json) |
| RS | Serbia | 2 | [RS.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/RS.json) |
| RU | Russia | 19 | [RU.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/RU.json) |
| SG | Singapore | 9 | [SG.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/SG.json) |
| SK | Slovakia | 1 | [SK.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/SK.json) |
| TH | Thailand | 6 | [TH.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/TH.json) |
| TR | Türkiye | 5 | [TR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/TR.json) |
| UA | Ukraine | 6 | [UA.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/UA.json) |
| US | United States | 41 | [US.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/US.json) |
| UY | Uruguay | 1 | [UY.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/UY.json) |
| UZ | Uzbekistan | 2 | [UZ.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/UZ.json) |
| VE | Venezuela | 4 | [VE.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/VE.json) |
| VN | Vietnam | 7 | [VN.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/VN.json) |
| XK | Kosovo | 1 | [XK.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/XK.json) |
| ZA | South Africa | 3 | [ZA.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/ZA.json) |

## Sources

Proxies are scraped from 20+ public lists including TheSpeedX, proxifly, ShiftyTR, monosans, roosterkid, hookzof, clarketm, almroot, mmpx12, and the Geonode API, then tested live before publishing.

---

*Auto-generated by [free-proxies-updater](https://github.com/mauricegift/free-proxies) — do not edit manually.*
