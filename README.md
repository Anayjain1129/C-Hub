# C-Hub
This is a USB hub with 2 usb A and 3 usb C ports you can connect the corner usb c to your computer/laptop and then you have a usb hub that gives you more ports to use! 

# Why did i made this?
I did not only made this because of the horizons deadline i made this because i wanted to a USB hub which can hold/let me plug all of my electronics! still i have a good laptop with 3 usb A ports and 1 type C but still i needed more ports cause most of the time they remain occupied so yea that's why i made this

# What was the Hardest Part?
The hardest part was absolutely routing the PCB since i used EasyEDA for this project so like was a mess easyeda is just not so good blehh im more of my kicad guy i could have used kicad but the libraries were not available so i had to use easyeda 

# Design
The design is very unique i have made this in a form of a keychain which we can use as a usb hub too or a usb hub as keychain 👀 whatever yea so the design is very unique and simple

# How do i use it?
It's a Plug-n-play device so you can just plug it in your PC or laptop and just use it! 

# Images-
<img width="1126" height="478" alt="image" src="https://github.com/user-attachments/assets/dce53631-f7d7-4609-acd5-a3ca7e166980" />
<img width="1492" height="785" alt="image" src="https://github.com/user-attachments/assets/ccd8fc03-bd57-4349-8ffc-0834a391be7f" />
<img width="1171" height="763" alt="image" src="https://github.com/user-attachments/assets/41dded30-6eaa-4215-937b-e297f5d87a7c" />
<img width="1413" height="664" alt="image" src="https://github.com/user-attachments/assets/cd63cf08-dde1-4699-bf8a-ce1f76a68cee" />
<img width="990" height="786" alt="Screenshot 2026-09-16 085448" src="https://github.com/user-attachments/assets/9ec78759-2cca-4830-8b27-4e13b6981d38" />
<img width="919" height="673" alt="Screenshot 2026-09-16 085501" src="https://github.com/user-attachments/assets/18bec44c-c800-4edb-b21f-8a1a4e29a309" />


## Bill of Materials (BOM)

| No. | Qty | Comment | Designator | Footprint | Value | Manufacturer | Mfr. Part # | Supplier Part # | Supplier | Unit Price (USD) | Total (USD) |
|-----|-----|---------|------------|-----------|-------|---------------|-------------|------------------|----------|-------------------|-------------|
| 1 | 2 | 1uF | C1,C2 | C0603 | 1uF | — | — | — | — | $0.01 | $0.02 |
| 2 | 6 | 1uF | C3,C4,C5,C7,C8,C10 | C0603 | 1uF | — | — | — | — | $0.01 | $0.06 |
| 3 | 3 | 100nF | C6,C9,C11 | C0603 | 100nF | — | — | — | — | $0.01 | $0.03 |
| 4 | 2 | 5.1K | R1,R2 | R0603 | 5.1K | — | — | — | — | $0.01 | $0.02 |
| 5 | 4 | 56K | R3,R4,R5,R6 | R0603 | 56K | — | — | — | — | $0.01 | $0.04 |
| 6 | 1 | SL2.1s | U1 | SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL | SL2.1s | CoreChips | SL2.1s | C2684433 | LCSC | $0.45 | $0.45 |
| 7 | 3 | TYPE-C 16PIN 2MD | USB1,USB2,USB3 | USB-C-SMD_TYPE-C-16PIN-2MD-073 | TYPE-C 16PIN 2MD | SHOU HAN | TYPE-C-16PIN-2MD | C2765186 | LCSC | $0.25 | $0.75 |
| 8 | 2 | 10.0 QHHTZB6.3 | USB4,USB5 | USB-A-TH_10.0QHHTZB6.3 | 10.0 QHHTZB6.3 | SHOU HAN | 10.0QHHTZB6.3 | C668591 | LCSC | $0.20 | $0.40 |
| — | 1 | PCB (bare board) | — | — | — | JLCPCB | — | — | JLCPCB | $13.00 | $13.00 |

**Component + bare PCB total: ~$14.77 (per board)**

### PCBA (Assembled) Option

Given the small passives (0603) and fine-pitch SSOP-16 IC, factory assembly via JLCPCB is recommended over hand soldering.

| Item | Qty | Notes | Price |
|------|-----|-------|-------|
| Bare PCB | 5 boards | White, 1.6mm, HASL | $4.00 |
| PCBA (top-side assembly) | 5 boards | Economic PCBA tier | $28.26 |
| Shipping (ePacket) | — | To India | $17.03 |
| **Total (before coupon)** | | | **$49.29** |
| **Total (with $20 coupon)** | | | **$29.29** |

Works out to roughly **$5.86–$9.86 per assembled board** (5-board batch, depending on coupon availability).
