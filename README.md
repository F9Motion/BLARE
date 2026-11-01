# BLARE
BLARE - is cutom alarm clock. Of course, you can use your phone but, come on! Custom alarm clock more interesting than phone. This is cube form alarm clock with display and 4 buttons.
<img width="1675" height="891" alt="Снимок экрана 2026-11-01 155736" src="https://github.com/user-attachments/assets/035fdd4c-64f8-488d-b88c-a5d244b4c399" />
<img width="1576" height="852" alt="Снимок экрана 2026-11-01 181257" src="https://github.com/user-attachments/assets/a7cb3475-df4d-4f77-8225-263100fcbcef" />
# Why I made this?
I find this project in FABRICATE tutorials and find this **BLARE**. I haven't any other alarm clock so this good thing for me.

# Feautures
1. This alarm clock have a display(or had if you like me just steal things from old projects to make new project :D)
2. Have 4 buttons (or had) if you think 2 is a few
3. Case printed in 3D printer if you haven't 3D printer you can use service printing legion from hack club
4. This alarm clock is with firmware writed in Arduino IDE

# Imagines
<img width="1581" height="852" alt="Снимок экрана 2026-11-01 181309" src="https://github.com/user-attachments/assets/771455d2-c185-43c7-bb1c-998eafdf2fae" />
<img width="1249" height="717" alt="Снимок экрана 2026-11-01 181213" src="https://github.com/user-attachments/assets/0b18780c-8566-4b96-b4d5-140b81a227fd" />
<img width="1445" height="848" alt="Снимок экрана 2026-11-01 155753" src="https://github.com/user-attachments/assets/cd0850fb-5bd8-43d9-8613-0032cfa19dce" />
<img width="1553" height="798" alt="Снимок экрана 2026-11-01 155725" src="https://github.com/user-attachments/assets/dd464fba-cbfa-45a0-bbf2-678e4f089ae9" />


# How it works?
The firmware is in **ESP32**, so you can use Arduino IDE for writing firmware and the best function of this is... this is custom! That means you can upload to ESP32 not mine, your firmware if you want. So it's works: 4 buttons put signal to ESP32 "we pushshed!" and ESP32 "OK".

# How to assemble
Just to this step and use Blade:
1. Print the **PCB** from JLCPCB
2. Order microcontrollers(you can find this in BOM)
3. Solder to PCB this microcontrollers
4. Print CAD in 3D printer
5. Instal firmware to ESP32
6. Use this!

# Bill Of Materials(BOM)
| Name         | Price | Link |
|--------------|-------|------|
| XIAO ESP32   | $4.9  | https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html |
| switchs      | $7.42 | https://aliexpress.ru/item/4001111706889.html?shpMethod=CAINIAO_STANDARD&sku_id=10000014442813977&spm=a2g2w.productlist.search_results.0.48c575ddYCQpmf         |
| Buzzer       | $1.25 | https://aliexpress.ru/item/1005006613648485.html?shpMethod=AE_CN_SUPER_ECONOMY_G&sku_id=12000037825538791&spm=a2g2w.productlist.search_results.0.17d02d3dQT85Dr |
| Display      | $4.02 | https://aliexpress.ru/item/1005012250582857.html?shpMethod=AE_CN_SUPER_ECONOMY_G&sku_id=12000057857651313&spm=a2g2w.productlist.search_results.5.4d2f7214h6M6bk |
| wire         | $1.5  | https://aliexpress.ru/item/1005004338950885.html?shpMethod=AE_CN_SUPER_ECONOMY_G&sku_id=12000028815659129&spm=a2g2w.productlist.search_results.4.4d0d4feaKCfQsK |
| Printing PCB | $9    | JLCPCB no link |
| bottom.step  | $0.4  | felament price only |
| top.step     | $0.09 | felament price only |


# Credits
Blender, KiCad, Arduino
Worked person: Rasul
