# free-proxies

> **437 working validated proxies** last updated on **Sunday 05-04-2026 18:13:06 EAT**

Free, continuously validated **HTTP**, **SOCKS4** and **SOCKS5** proxies tested live and organised by protocol and country. Updated every **30 mins/1hr depending on my server's load balancing**.

![HTTP](https://img.shields.io/badge/HTTP-244-blue?style=flat-square)
![SOCKS4](https://img.shields.io/badge/SOCKS4-150-green?style=flat-square)
![SOCKS5](https://img.shields.io/badge/SOCKS5-43-purple?style=flat-square)
![Countries](https://img.shields.io/badge/Countries-72-orange?style=flat-square)

🌐 **Live site:** https://mauricegift.github.io/free-proxies

---

## Quick download

| Protocol | Count | Raw URL |
|----------|------:|---------|
| HTTP | 244 | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/http.json` |
| SOCKS4 | 150 | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/socks4.json` |
| SOCKS5 | 43 | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/socks5.json` |
| Combined | 437 | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/proxies.json` |
| Random 100 | — | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/random.json` |
| Metadata | — | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/metadata.json` |
| Timestamp | — | `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/timestamp.json` |

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

## Countries (72)

Per-country files live at `https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/<CC>.json`.

| Code | Country | Count | Link |
|------|---------|------:|------|
| AL | Albania | 2 | [AL.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/AL.json) |
| AR | Argentina | 9 | [AR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/AR.json) |
| AU | Australia | 2 | [AU.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/AU.json) |
| BD | Bangladesh | 25 | [BD.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BD.json) |
| BF | Burkina Faso | 1 | [BF.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BF.json) |
| BG | Bulgaria | 2 | [BG.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BG.json) |
| BO | Bolivia | 2 | [BO.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BO.json) |
| BR | Brazil | 18 | [BR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BR.json) |
| BT | Bhutan | 1 | [BT.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BT.json) |
| BW | Botswana | 1 | [BW.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/BW.json) |
| CA | Canada | 3 | [CA.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/CA.json) |
| CG | Republic of the Congo | 1 | [CG.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/CG.json) |
| CH | Switzerland | 1 | [CH.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/CH.json) |
| CL | Chile | 4 | [CL.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/CL.json) |
| CN | China | 6 | [CN.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/CN.json) |
| CO | Colombia | 25 | [CO.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/CO.json) |
| CR | Costa Rica | 1 | [CR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/CR.json) |
| CZ | Czechia | 2 | [CZ.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/CZ.json) |
| DE | Germany | 4 | [DE.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/DE.json) |
| DO | Dominican Republic | 2 | [DO.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/DO.json) |
| EC | Ecuador | 12 | [EC.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/EC.json) |
| EG | Egypt | 2 | [EG.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/EG.json) |
| ES | Spain | 2 | [ES.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/ES.json) |
| FI | Finland | 5 | [FI.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/FI.json) |
| FR | France | 2 | [FR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/FR.json) |
| GA | Gabon | 1 | [GA.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/GA.json) |
| GB | United Kingdom | 28 | [GB.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/GB.json) |
| GE | Georgia | 1 | [GE.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/GE.json) |
| GQ | Equatorial Guinea | 1 | [GQ.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/GQ.json) |
| GR | Greece | 1 | [GR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/GR.json) |
| GT | Guatemala | 2 | [GT.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/GT.json) |
| HK | Hong Kong | 1 | [HK.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/HK.json) |
| HN | Honduras | 1 | [HN.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/HN.json) |
| ID | Indonesia | 66 | [ID.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/ID.json) |
| IN | India | 24 | [IN.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/IN.json) |
| IQ | Iraq | 1 | [IQ.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/IQ.json) |
| IT | Italy | 3 | [IT.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/IT.json) |
| JP | Japan | 13 | [JP.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/JP.json) |
| KE | Kenya | 2 | [KE.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/KE.json) |
| KH | Cambodia | 5 | [KH.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/KH.json) |
| KR | South Korea | 4 | [KR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/KR.json) |
| LK | Sri Lanka | 1 | [LK.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/LK.json) |
| MM | Myanmar | 1 | [MM.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/MM.json) |
| MT | Malta | 1 | [MT.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/MT.json) |
| MX | Mexico | 6 | [MX.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/MX.json) |
| MY | Malaysia | 3 | [MY.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/MY.json) |
| NG | Nigeria | 1 | [NG.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/NG.json) |
| NL | The Netherlands | 6 | [NL.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/NL.json) |
| NP | Nepal | 1 | [NP.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/NP.json) |
| PA | Panama | 3 | [PA.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/PA.json) |
| PE | Peru | 4 | [PE.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/PE.json) |
| PH | Philippines | 9 | [PH.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/PH.json) |
| PL | Poland | 4 | [PL.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/PL.json) |
| PR | Puerto Rico | 1 | [PR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/PR.json) |
| PY | Paraguay | 1 | [PY.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/PY.json) |
| RO | Romania | 1 | [RO.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/RO.json) |
| RS | Serbia | 1 | [RS.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/RS.json) |
| RU | Russia | 18 | [RU.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/RU.json) |
| SE | Sweden | 1 | [SE.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/SE.json) |
| SG | Singapore | 6 | [SG.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/SG.json) |
| SY | Syria | 3 | [SY.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/SY.json) |
| TH | Thailand | 8 | [TH.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/TH.json) |
| TR | Türkiye | 4 | [TR.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/TR.json) |
| TW | Taiwan | 2 | [TW.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/TW.json) |
| UA | Ukraine | 5 | [UA.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/UA.json) |
| UG | Uganda | 1 | [UG.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/UG.json) |
| US | United States | 21 | [US.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/US.json) |
| UZ | Uzbekistan | 1 | [UZ.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/UZ.json) |
| VE | Venezuela | 6 | [VE.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/VE.json) |
| VN | Vietnam | 5 | [VN.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/VN.json) |
| ZA | South Africa | 3 | [ZA.json](https://raw.githubusercontent.com/mauricegift/free-proxies/master/files/countries/ZA.json) |

