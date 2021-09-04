# ESPHome-20-port-RJ45-GPIO
ESPHome 25 port RJ45 GPIO

This is a simple device that uses a Wemos D1 Mini and a MCP23017 port expander to give you 20 binary sensor ports.  Each RJ45 connector contains 4 twisted pair and each twisted pair acts as one binary sensor for connecting to reed switches, buttons, switches, you decide.  This can replace a home alarm system panel to connect the Home Assistant via ESPHome.  Simply use RJ45 Keystome connectors and connect your alarm panel wires to each pair on the jack.  Then connect the jack to device via thernet cable. 

![GitHub Logo](https://github.com/logichousepcb/ESPHome-20-port-RJ45-GPIO/blob/main/20_PORT-WEMOS-PIC.PNG)

I have included sample yaml for ESPHome, the STL files to 3D print the case, the BOM (bill of mataerials for the circuit board), and the GERBER file for the circuit board to simply order from JLPCB or PCBWay.

To build the simple board you will need:

(1) Wemos D1 Mini - https://www.amazon.com/Organizer-ESP8266-Internet-Development-Compatible/dp/B081PTPYBX/ref=sr_1_14?dchild=1&keywords=wemos+d1+mini&qid=1621771739&sr=8-14

(2) 8x1 female header (usually comes with the Wemos)

(5) RJ45 connectors - https://lcsc.com/product-detail/Ethernet-Connectors-Modular-Connectors-RJ45-RJ11_TE-Connectivity-215877-1_C305919.html

(1) 10k resistor - https://lcsc.com/product-detail/Metal-Film-Resistor-TH_TyoHM-RN-1-8W-10K-F-T-B-A1_C433502.html

(4) M2x8mm - https://www.amazon.com/gp/product/B00YBMRAH4/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1

(1) MCP23017-E/SO - https://lcsc.com/product-detail/Interface-I-O-Expanders_Microchip-Tech-MCP23017-E-SO_C47023.html

![GitHub Logo](https://github.com/logichousepcb/ESPHome-20-port-RJ45-GPIO/blob/main/20_PORT-WEMOS-PARTS.PNG)

When I was confronted with a hoard of wire sticking out the wall where the alarm panel used to exist, it was a task itself to determine which wires went to which sensors.  In my case there were 12 zones broken down as follows:
4 doors (front/back/garage entry/basement)
8 windows (living room/dining room/kitchen/bath/family room/basement/basement side) 
I would note some of the windows were in pairs and had their own sensors but counted as 1 zone per pair)

I used Network RJ45 connectors to connect the wire pairs to.  Each cable that was prewired had 4 wires (red/black/green/yellow)

![image](https://github.com/logichousepcb/ESPHome-20-port-RJ45-GPIO/blob/main/RJ45%20punchdown.JPG)

I have recently created a 4 button panel that cneected via RJ45 to go in a decora switch plate.  You can run 5 panels with 4 buttons each off this board.  I have designed a decora faceplate and the .stl are on here as well.

![image](https://github.com/logichousepcb/ESPHome-20-port-RJ45-GPIO/blob/main/4%20Button%20switchplate.JPG)

I have a limited supply of kits with all the parts to assemble minus the 3D Printed case.  Contact me at logixpcb@gmail.com for a built baord.  

Also available in my Etsy shop.    https://www.etsy.com/listing/1010173064/esphome-20-port-expander?ref=shop_home_active_1
