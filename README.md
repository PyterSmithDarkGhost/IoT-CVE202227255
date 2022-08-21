# CVE-2022-27255 - Realtek eCos SDK SIP ALG buffer overflow 

Este repositório contém os materiais para a palestra "Exploring the hidden attack surface of OEM IoT devices: pwning milhares de roteadores com uma vulnerabilidade no SDK da Realtek para eCos OS.", que foi apresentada em [DEFCON30](https://forum.defcon.org/node/241835).

O conteúdo deste repositório inclui:

- `analysis`: Automated firmware analysis to detect the presence of CVE-2022-27255 (Run `analyse_firmware.py`).
- `exploits_nexxt`: PoC and exploit code. The PoC should work on every affected router, however the exploit code is specific for the Nexxt Nebula 300 Plus router.
- `ghidra_scripts`: Vulnerable function call searching script and CVE-2022-27255 detection script.
- `DEFCON`: Slide deck & poc video.

## Dispositivos vulneráveis:

- Nexxt Nebula 300 Plus
- Tenda F6 V5.0
- Tenda F3 V3
- Tenda F9 V2.0
- Tenda AC5 V3.0
- Tenda AC6 V5.0
- Tenda AC7 V4.0
- Tenda A9 V3
- Tenda AC8 V2.0
- Tenda AC10 V3
- Tenda AC11 V2.0
- Tenda FH456 V2.0
- Zyxel NBG6615 V1.00
- Intelbras RF 301K V1.1.15
- Multilaser AC1200 RE018
- iBall 300M-MIMO (iB-WRB303N)
- Brostrend AC1200 extender
- MT-Link MT-WR850N
- MT-Link MT-WR950N
- Everest EWR-301
- D-Link DIR-822 h/w version B
- Speedefy K4
- Ultra-Link Wireless N300 Universal Range Extender
- Keo KLR 301
- QPCOM QP-WR347N
- NEXT 504N
- Nisuta NS-WIR303N (probably V2)
- Rockspace AC2100 Dual Band Wi-Fi Range Extender
- KNUP KP-R04
- Hikvision DS-3WR12-E

Se você encontrar um novo dispositivo vulnerável, envie uma solicitação de pull.
