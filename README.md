# temaTSC
smartwatch
<img width="1110" height="1012" alt="image" src="https://github.com/user-attachments/assets/9024962a-e35f-4613-b769-74186d94089c" />

## BOM (Bill of Materials)

| Referință | Componentă | Valoare/Descriere | Package | Cantitate | Datasheet |
|-----------|-----------|-------------------|---------|-----------|-----------|
| U1 | nRF52840 | MCU + BLE 5.0 | QFN-94 | 1 | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/NRSA/NRSA-S-A0021008244/NRSA-S-A0021008244-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054) |
| IC1 | BQ25180YBGR | LiPo Charger | BGA-8 | 1 | [Datasheet](https://www.ti.com/lit/ds/symlink/bq25180.pdf) |
| IC2 | DRV2605YZFR | Haptic Driver | DSBGA-12 | 1 | [Datasheet](https://www.ti.com/lit/ds/symlink/drv2605.pdf) |
| IC3 | BMA421 | IMU (Accelerometru) | LGA-12 | 1 | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/BSCH/BSCH-S-A0007921771/BSCH-S-A0010021471-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054) |
| IC9 | RT6160AWSC | DC/DC Converter | WLCSP | 1 | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/RHTK/RHTK-S-A0025617216/RHTK-S-A0025617221-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054) |
| U3 | MAX17048G+T10 | Fuel Gauge | SOT-23-6 | 1 | [Datasheet](https://www.analog.com/media/en/technical-documentation/data-sheets/MAX17048-MAX17049.pdf?ADICID=SYND_WW_P682800_PF-spglobal) |
| D3 | USBLC6-2SC6Y | ESD Protection USB | SOT-363 | 1 | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/SGST/SGSTS35924/SGSTS35924-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054) |
| J4 | KH-TYPE-C-16P | USB-C Connector | SMD | 1 | [Datasheet](https://www.snapeda.com/parts/KH-TYPE-C-16P/kinghelm/datasheet/) |
| J1 | 503480-2400 | E-Paper Connector | FFC 24-pin | 1 | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/MOLE/MOLE-S-A0003522481/MOLE-S-A0010982248-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054) |
| ANT1 | 2450AT18B100E | Antenă BLE 2.4GHz | SMD | 1 | [Datasheet](https://www.johansontechnology.com/datasheets/antennas/2450AT18B100E.pdf) |
| X1 | Crystal 32MHz | Oscilator principal | SMD 2016 | 1 | - |
| X2 | Crystal 32.768kHz | RTC clock | SMD 2016 | 1 | - |
| SW1-3 | EVP-AKE31A | Buton tactil SMD | SMD | 3 | [Datasheet](https://industrial.panasonic.com/cdbs/www-data/pdf/ATV0000/ATV0000CE5.pdf) |
| J2 | TC2030-IDC | SWD Debug Connector | SMD | 1 | [Datasheet](https://www.tag-connect.com/wp-content/uploads/bsk-pdf-manager/TC2030-IDC_1.pdf) |
| Q2 | DMG2305UX-7 | MOSFET P-ch | SOT-23 | 1 | [Datasheet](https://www.diodes.com/assets/Datasheets/DMG2305UX.pdf) |
| Q3 | SI1308EDL-T1-GE3 | MOSFET N-ch | SC-70 | 1 | [Datasheet](https://www.vishay.com/docs/68252/si1308edl.pdf) |
| D2,D4,D5 | MBR0530 | Diodă Schottky | SOD-123 | 3 | [Datasheet](https://www.onsemi.com/pdf/datasheet/mbr0530t1-d.pdf) |
| L1 | FTC252012SR47MBCA | Inductanță 0.47µH | 2520 | 1 | - |
| L2 | Inductanță 15nH | RF matching | 0201 | 1 | - |
| L3 | Inductanță 3.9nH | RF matching | 0201 | 1 | - |
| L5 | Inductanță 68µH | EPD driver | SMD | 1 | - |
| L7 | Inductanță 10µH | DC/DC | SMD | 1 | - |
| C* | Condensatoare 100nF | Decuplare | 0201 | multiple | - |
| C* | Condensatoare >100nF | Bulk | 0402 | multiple | - |
| R* | Rezistențe | Diverse valori | 0201 | multiple | - |
