# Pomp controller

### Probleem opstelling

Maken van een pomp controller die een ESP32 naar 2 Pompen kan aansturen.
De pomp werkt op 12V en heeft een Vermogen van 20W

# Blokdiagram

![image](https://user-images.githubusercontent.com/91600019/165539456-4badd72a-6aa0-4e98-a140-ba2f3281fa0a.png)

# Elecktrisch Schema

### 

![image](https://user-images.githubusercontent.com/91600019/165540538-81c22187-6720-4f9c-b0bf-3acebd8dc536.png)

### Microcontroller Peripherals

![image](https://user-images.githubusercontent.com/91600019/165540701-a9571016-1667-478b-a546-4da77ca12471.png)

### Pomp Aansturing

![image](https://user-images.githubusercontent.com/91600019/165540865-9b0e7b98-c11d-4a54-8501-4e307dd046b4.png)

### Spannings Regelaar 

![image](https://user-images.githubusercontent.com/91600019/165541373-ffcd6622-a634-476a-a338-1bc812f74609.png)

### Voeding & Montage gaten

![image](https://user-images.githubusercontent.com/91600019/165542133-74cd2027-c0d5-486e-992c-df419a1c8eac.png)

# PCB ontwerp

### Voorkant

KiCad: 

![image](https://user-images.githubusercontent.com/91600019/165544898-ac918bb3-d51f-4f5d-ab53-38924f0e7675.png)

![image](https://user-images.githubusercontent.com/91600019/165542330-8508beab-56f0-4ed9-92a2-73c7dabfee2c.png)

### Achterkant

![image](https://user-images.githubusercontent.com/91600019/165542382-c488735b-913c-4839-8997-d51b20a19b3a.png)

### 3D ontwerp

![image](https://user-images.githubusercontent.com/91600019/166697643-f6117e52-276a-4865-8d4c-58d1a359b8a6.png)


# Componenten

### Pomp

**Barwig Typ 04 0444 Laagspanning dompelpomp 600 l/h 6 m** 

![image](https://user-images.githubusercontent.com/91600019/165543210-dbb0adce-757f-4d2a-ae17-64f63fa3d84e.png)


**Gegevens**

|Spanning|Stroom|Vermogen|
|--------|--------|--------|
|12V|1.7A|20W|

### ESP32

![image](https://user-images.githubusercontent.com/91600019/165543411-e09bc5d5-a62d-436f-a4a4-63edf3d23ddb.png)

**Links: **

https://www.tinytronics.nl/shop/nl/communicatie-en-signalen/draadloos/wi-fi/modules/esp32-wrover-wifi-module-pcb-antenne-aansluiting
https://www.tinytronics.nl/shop/index.php?route=product/product/get_file&file=1719/esp32-wrover_datasheet_en.pdf

### Power mosfet

**SI2312BDS-T1-E3**

![image](https://user-images.githubusercontent.com/91600019/165543737-006d015a-3ed4-48f4-98cd-d8b8ef467183.png)

**Links:**

https://www.farnell.com/datasheets/2045689.pdf
https://be.farnell.com/vishay/si2312bds-t1-e3/mosfet-n-ch-20v-3-9a-sot-23-3/dp/2396085

### Spannings regelaar

**AP7361-33E-13**

![image](https://user-images.githubusercontent.com/91600019/165544066-c5331e54-d0bc-4ff1-91a6-5afd2911dabf.png)

**Links:**

https://be.farnell.com/diodes-inc/ap7361-33e-13/ldo-fixed-3-3v-1a-40-to-85deg/dp/3482976


# Din Rail Enclosure

RS PRO Modular Enclosure Enclosure Type, 70.0 x 90.0 x 65.0mm, ABS DIN Rail Enclosure

![image](https://user-images.githubusercontent.com/91600019/165544375-e25acbfb-de92-45d4-8fa2-6ef38c2f1d3f.png)

**Gegevens:**

Category Enclosures Modular for DIN rail
Type Full
Material ABS V0
Variant Without gasket
Height 65.0 mm
Width 90.0 mm
Length 70.0 mm
Color Lightgray (J)
Standards Met RoHS Compliant
Accessories Black hook: 1.0 pcs
Certificate number CE/032/18 Dashed line shows outline of the mounting boss under PCB board

**Afmetingen**

![image](https://user-images.githubusercontent.com/91600019/165544557-c7aaa88f-f07e-4351-b811-2b7809cf69ca.png)

Recommended mounting holes diameter ø3,5mm

**Links**

https://benl.rs-online.com/web/p/din-rail-enclosures/1862295
