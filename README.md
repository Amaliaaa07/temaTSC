# temaTSC
smartwatch
<img width="1110" height="1012" alt="image" src="https://github.com/user-attachments/assets/9024962a-e35f-4613-b769-74186d94089c" />

## BOM (Bill of Materials)

| Referință | Componentă | Valoare/Descriere | Package | Cantitate | Link JLC | Datasheet |
|-----------|-----------|-------------------|---------|-----------|----------|-----------|
| U1          | MCU             | nRF52840               | 1         | [JLC](https://jlcpcb.com/partdetail/NordicSemiconductor-nRF52840_QIAA/C190794) | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/NRSA/NRSA-S-A0021008244/NRSA-S-A0021008244-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054)  |
| IC1         | LiPo Charger    | BQ25180YBGR            | 1         | [JLC](https://componentsearchengine.com/prices/BQ25180YBGR?manufacturer=Texas%20Instruments)     | [Datasheet](https://www.ti.com/lit/ds/symlink/bq25180.pdf)                                                     |
| IC2         | Haptic Driver   | DRV2605YZFR            | 1         | [JLC](https://componentsearchengine.com/prices/DRV2605YZFR?manufacturer=Texas%20Instruments)     | [Datasheet](https://www.ti.com/lit/ds/symlink/drv2605.pdf)                                                     |
| IC3         | IMU             | BMA423                 | 1         | [JLC](https://componentsearchengine.com/prices/BMA423?manufacturer=BOSCH)                      | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/BSCH/BSCH-S-A0007921771/BSCH-S-A0010021471-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054)    |
| IC9         | DC/DC Converter | RT6160AWSC             | 1         | [JLC](https://componentsearchengine.com/prices/RT6160AWSC?manufacturer=RICHTEK)               | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/RHTK/RHTK-S-A0025617216/RHTK-S-A0025617221-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054)                                |
| U3          | Fuel Gauge      | MAX17048G+T10          | 1         | [JLC](https://componentsearchengine.com/prices/MAX17048G%2BT10?manufacturer=Analog%20Devices)      | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/RHTK/RHTK-S-A0025617216/RHTK-S-A0025617221-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054)         |
| D3          | ESD Protection  | USBLC6-2SC6Y           | 1         | [JLC](https://componentsearchengine.com/prices/USBLC6-2SC6Y?manufacturer=STMicroelectronics)   | [Datasheet](https://www.analog.com/media/en/technical-documentation/data-sheets/MAX17048-MAX17049.pdf?ADICID=SYND_WW_P682800_PF-spglobal)                                             |
| J4          | USB-C Connector | KH-TYPE-C-16P          | 1         | [JLC](https://www.snapeda.com/parts/KH-TYPE-C-16P/kinghelm/view-part/?ref=search&t=KH-TYPE-C-16P&ab_test_case=b)                    | [Datasheet](https://www.snapeda.com/parts/KH-TYPE-C-16P/kinghelm/datasheet/)        |
| J1          | E-Paper Connector | 503480-2400E         | 1         | [JLC](https://componentsearchengine.com/prices/5034802400?manufacturer=Molex)                 | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/MOLE/MOLE-S-A0003522481/MOLE-S-A0010982248-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054)                                      |
| ANT1        | Antena BLE      | 2450AT18B100E          | 1         | [JLC](https://componentsearchengine.com/prices/2450AT18B100E?manufacturer=JOHANSON%20TECHNOLOGY)             | [Datasheet](https://www.johansontechnology.com/docs/1187/2450AT18B100_X8XXogU.pdf)                     |
| X1          | Crystal 32MHz   | SMD 2016               | 1         | [JLC](https://componentsearchengine.com/prices/SMD2016B050TF?manufacturer=Yageo%20Group)                   | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/YAGO/YAGO-S-A0024580626/YAGO-S-A0024591343-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054)                            |
| X2          | Crystal 32.768kHz | SMD 2016             | 1         | [JLC](https://componentsearchengine.com/prices/SMD2016B050TF?manufacturer=Yageo%20Group)               | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/YAGO/YAGO-S-A0024580626/YAGO-S-A0024591343-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054)                               |
| SW1-3       | Buton tactil    | EVP-AKE31A             | 3         | [JLC](https://componentsearchengine.com/prices/EVP-AKE31A?manufacturer=Panasonic)               | [Datasheet](https://industrial.panasonic.com/cdbs/www-data/pdf/ATK0000/ATK0000C434.pdf)                        |
| J2          | SWD Connector   | TC2030-IDC             | 1         | [JLC](https://componentsearchengine.com/prices/TC2030-IDC?manufacturer=Tag%20Connect)             | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/TGCN/TGCN-S-A0008988129/TGCN-S-A0008988129-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054)                   |
| Q2          | MOSFET P-ch     | DMG2305UX-7            | 1         | [JLC](https://componentsearchengine.com/prices/DMG2305UX-7?manufacturer=Diodes%20Incorporated)                 | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/DIOD/DIOD-S-A0013043571/DIOD-S-A0013120650-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054)                                            |
| Q3          | MOSFET N-ch     | SI1308EDL-T1-GE3       | 1         | [JLC](https://componentsearchengine.com/prices/Si1308EDL-T1-GE3?manufacturer=Vishay)             | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/VISH/VISH-S-A0000692786/VISH-S-A0000692786-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054)                                                   |
| D2, D4, D5  | Dioda Schottky  | MBR0530                | 3         | [JLC](https://componentsearchengine.com/prices/MBR0530?manufacturer=MCC)           | [Datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/MCCC/MCCCS04194/MCCCS04194-1.pdf?hkey=61A2E4C270F0397D049F8F05BD4F1054)                                         |
| L1          | Inductanta 0.47µH | FTC252012SR47MBCA    | 1         | [JLC](https://jlcpcb.com/partdetail/6763488-FTC252012SR47MBCA/C5832368)                 |
| L2          | Inductanta 15nH | RF matching 0201       | 1         | [JLC](https://jlcpcb.com/partdetail/Sunlord-SDCL0201C15NJTDF/C389547)          |     -                   |
| L3          | Inductanta 3.9nH | RF matching 0201      | 1         | [JLC](https://jlcpcb.com/partdetail/Sunlord-SDCL0201C3N9STDF/C389544)          |     -                   |
| L5          | Inductanta 68µH | EPD driver SMD         | 1         | [JLC](https://jlcpcb.com/partdetail/Sumida-CDMC4D28NP680MC/C408336)            |     -                       |
| L7          | Inductanta 10µH | DC/DC SMD              | 1         | [JLC](https://jlcpcb.com/partdetail/Sunlord-MWSA0402S100MT/C408352)            |     -                     |
| C*          | Condensatoare   | 100nF decuplare 0201   | multiple  | [JLC](https://jlcpcb.com/partdetail/Samsung-CL03B104KO3NNNC/C15195)            | -                                                                                                               |
| C*          | Condensatoare   | >100nF bulk 0402       | multiple  | [JLC](https://jlcpcb.com/partdetail/Samsung-CL05A475KP5NRNC/C25771)            | -                                                                                                               |
| R*          | Rezistente      | Diverse valori 0201    | multiple  | [JLC](https://jlcpcb.com/partdetail/UNI-ROYAL-0201WAF1001T5E/C17513)           | -                                                                                                               |

## Descrierea funcționalității hardware

### Microcontroller — nRF52840

Inima dispozitivului este **Nordic nRF52840**, un SoC (System on Chip) cu procesor ARM Cortex-M4 la 64 MHz, cu unitate FPU, 1 MB Flash, 256 KB RAM și radio Bluetooth 5.0 integrat. Chipul operează la 3.3V și gestionează toate perifericele prin interfețele SPI, I2C și GPIO.

### Alimentare

Lanțul de alimentare funcționează astfel:
- **USB-C (KH-TYPE-C-16P)** furnizează VBUS (5V) prin conectorul de încărcare
- **USBLC6-2SC6Y** protejează liniile D+/D- împotriva descărcărilor electrostatice (ESD)
- **BQ25180YBGR** este charger-ul LiPo care încarcă bateria de 3.7V și comunică cu MCU-ul prin I2C pentru a raporta starea încărcării. Curentul maxim de încărcare este de 350mA.
- **MAX17048G+T10** este fuel gauge-ul care măsoară tensiunea bateriei și estimează starea de încărcare (SoC) prin algoritmul ModelGauge, comunicând prin I2C. Generează o întrerupere ALERT când bateria scade sub un prag configurat.
- **RT6160AWSC** este un convertor DC/DC boost care generează tensiunea de 3.3V necesară MCU-ului și perifericelor din tensiunea bateriei. Frecvența de comutare este de 1.5MHz, folosind inductanța L7 de 10µH.

### Display E-Paper

Display-ul e-paper se conectează prin conectorul FFC **503480-2400** (24 pini). Interfața de comunicație este **SPI** (MOSI, SCK) împreună cu semnale de control GPIO:
- **EPD_CS** — chip select
- **EPD_DC** — selectare mod Data/Command
- **EPD_RST** — reset display
- **EPD_BUSY** — semnal de ocupat (MCU-ul așteaptă să devină LOW înainte de a trimite date noi)

Circuitul de drive al display-ului conține diode Schottky MBR0530, MOSFET-uri și inductanța L5 (68µH) pentru generarea tensiunilor ridicate necesare panoului e-paper (PREVGH pozitiv, PREVGL negativ). Marele avantaj al display-ului e-paper este consumul zero în standby — imaginea rămâne afișată fără alimentare (display bistabil).

### IMU — BMA421

Senzorul de mișcare **BMA421** de la Bosch este un accelerometru 3-axis cu consum ultra-redus, folosit pentru:
- Detectarea pașilor (pedometru integrat în hardware)
- Recunoașterea activității (mers, alergat, stat)
- Detectarea orientării dispozitivului
- Wake-up la mișcare (trezirea MCU-ului din sleep)

Comunică cu MCU-ul prin **I2C** la adresa 0x18 sau 0x19 (selectabilă prin pinul SDO). Generează întreruperi pe liniile **INT1** și **INT2** pentru a trezi MCU-ul la detectarea unor evenimente, fără a consuma energie în modul standby. Tensiunea de alimentare este 3.3V (VDDIO și VDD).

### Driver Haptic — DRV2605YZFR

**DRV2605YZFR** de la Texas Instruments este un driver pentru actuatoare haptice (LRA/ERM) cu bibliotecă internă de 123 de efecte de vibrație stocate în ROM. Comunică prin **I2C** la adresa 0x5A și este activat de MCU prin semnalul **HAPTIC_EN** (GPIO). Oferă feedback tactil utilizatorului la interacțiunile cu interfața (notificări, confirmare butoane etc.).

### Conectivitate BLE

Radio-ul BLE integrat în nRF52840 operează la 2.4GHz și suportă Bluetooth 5.0 cu rate de date de 1Mbps (LE 1M PHY) și 2Mbps (LE 2M PHY). Este conectat la antena **2450AT18B100E** de la Johanson Technology printr-o rețea de matching RF compusă din L2 (15nH), L3 (3.9nH) și condensatoare de 1pF. Antena este plasată la exteriorul PCB-ului, iar zona de sub antenă este decupată complet (fără cupru și fără trasee) pentru a nu degrada performanța RF.

### Butoane

Trei butoane tactile **EVP-AKE31A** de la Panasonic (SW_UP, SW_DN, SW_ENT) sunt conectate la GPIO-urile MCU-ului cu rezistențe de pull-up de 10kΩ. La apăsare, pinul GPIO este tras la GND. Butoanele sunt plasate pe marginea PCB-ului, aliniate cu orificiile fizice din carcasă.

### Debug SWD

Interfața de programare și depanare **SWD** este expusă prin conectorul **TC2030-IDC** (Tag-Connect 6-pin, fără găuri). Semnalele disponibile sunt SWDIO, SWDCLK, SWO (trace), RESET, 3.3V și GND. Toate sunt marcate pe silkscreen cu test pad-uri dedicate.

### Oscilatoare

- **Crystal 32 MHz** — oscilator principal pentru MCU și radio BLE, cu condensatoare de sarcină de 12pF. Conectat pe pinii dedicați P0.00/XL1 și P0.01/XL2.
- **Crystal 32.768 kHz** — oscilator pentru RTC (Real Time Clock), cu condensatoare de 12pF. Conectat pe pinii dedicați XC1 și XC2. Permite timekeeping precis în modul low power.

---

## Calcul consum de energie

| Componentă | Curent tipic | Mod |
|-----------|-------------|-----|
| nRF52840 | 4.8 mA | Activ CPU |
| nRF52840 | 0.4 µA | Deep sleep |
| nRF52840 | 5.3 mA | BLE advertising |
| BMA421 | 150 µA | Normal |
| BMA421 | 2 µA | Low power |
| DRV2605 | 9 mA | Activ |
| DRV2605 | 40 µA | Standby |
| MAX17048 | 23 µA | Activ |
| RT6160AWSC | ~50 µA | Quiescent |
| Display e-paper | ~26 mA | Refresh |
| Display e-paper | 0 mA | Standby (bistabil) |

**Estimare autonomie:** Cu o baterie LiPo de 200mAh, în modul normal de utilizare (MCU în sleep majoritatea timpului, refresh display de câteva ori pe zi, BLE advertising periodic), curentul mediu estimat este de aproximativ 1-2mA, rezultând o autonomie de **4-8 zile**.


## Pinii nRF52840 utilizați

| Pin nRF52840 | Semnal | Componentă | Interfață | Motiv |
|-------------|--------|-----------|-----------|-------|
| P0.00/XL1 | XL1 | Crystal 32MHz | XTAL | Pin dedicat oscilator principal |
| P0.01/XL2 | XL2 | Crystal 32MHz | XTAL | Pin dedicat oscilator principal |
| XC1, XC2 | - | Crystal 32.768kHz | XTAL | Pini RTC dedicați |
| P0.04 | EPD_CS | E-Paper | SPI CS | Chip select display |
| P0.05 | EPD_DC | E-Paper | GPIO | Data/Command select |
| P0.06 | MOSI | E-Paper | SPI | Date SPI |
| P0.07 | SCK | E-Paper | SPI | Clock SPI |
| P0.08 | EPD_RST | E-Paper | GPIO | Reset display |
| P0.09 | EPD_BUSY | E-Paper | GPIO | Busy signal display |
| P0.13 | D- | USB-C | USB | Linie date USB |
| P0.14 | D+ | USB-C | USB | Linie date USB |
| P0.25 | SDA | I2C bus | I2C | Date I2C (IMU, Haptic, Charger, FuelGauge) |
| P0.26 | SCL | I2C bus | I2C | Clock I2C |
| P0.27 | PMIC_INT | BQ25180 | GPIO | Întrerupere charger |
| P0.28 | ALERT | MAX17048 | GPIO | Alertă fuel gauge |
| P1.01 | HAPTIC_EN | DRV2605 | GPIO | Enable driver haptic |
| P1.02 | IMU_INT1 | BMA421 | GPIO | Întrerupere IMU 1 |
| P1.03 | IMU_INT2 | BMA421 | GPIO | Întrerupere IMU 2 |
| P1.04 | SW_UP | Buton UP | GPIO | Buton sus |
| P1.05 | SW_DN | Buton DOWN | GPIO | Buton jos |
| P1.06 | SW_ENT | Buton ENTER | GPIO | Buton enter |
| P0.18/RESET | RESET | SWD | SWD | Reset MCU |
| SWDCLK | SWDCLK | TC2030-IDC | SWD | Clock debug |
| SWDIO | SWDIO | TC2030-IDC | SWD | Date debug |
| P0.22 | SWO | TC2030-IDC | SWD | Trace output |
| ANT | RF | Antenă BLE | RF | Pin antenă dedicat |
| VBUS | VBUS | USB-C | Power | Detecție VBUS |

---

## Design log

### Probleme întâmpinate și decizii luate

**Erori Overlap (12) — Aprobate**: Cele 12 erori de overlap 
sunt de trei tipuri:

**Via-Smd Overlap (2)**: Via-uri care se suprapun ușor 
  cu pad-uri SMD în zone aglomerate ale PCB-ului. Mutarea 
  acestora ar compromite rutarea semnalelor din zonă.

**Solid Polygon Shape-Pad Overlap (2)**: Pad-ul 
  termal al unui circuit integrat se suprapune ușor 
  cu conturul (courtyard) componentei vecine. 
  Suprapunerea este minimă și nu afectează 
  funcționalitatea electrică sau asamblarea, 
  deoarece componentele nu se suprapun fizic.

**Smd-Via Overlap (6)**: Via-uri plasate în apropierea 
  pad-urilor SMD în zone aglomerate ale PCB-ului. Acestea 
  sunt necesare pentru rutarea semnalelor și nu pot fi 
  mutate fără a compromite rutarea generală. Suprapunerea 
  este minimă și nu afectează funcționalitatea electrică 
  sau procesul de fabricație.

**Modelele 3D**
Componentele mici (rezistențe 0201, condensatoare 0201/0402) nu au modele 3D individuale asociate și folosesc modelul generic din Fusion 360. Componentele principale (nRF52840, BQ25180, conectorul USB-C, butoanele, cristalele) au modele 3D reale asociate.

---

## Imagini

Randările PCB-ului și ale dispozitivului complet se găsesc în folderul `/Images`.

---

## Licență

Acest proiect este licențiat sub licența **Apache 2.0**. Vezi fișierul [LICENSE](LICENSE) pentru detalii.
