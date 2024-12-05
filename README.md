# SV08 Filament Cutting MOD

Bamboo Hotend integrated filament cutting mode.

I have modified the STEP CAD file available on Sovol's GitHub.
Thank you to Sovol for providing the CAD STEP files.

https://github.com/Sovol3d/SV08/tree/main/STEP



<br>
<br>
<br>


**아래 동작 유투브 영상 참조하세요~**

Refer to operation youtube video as below.

https://www.youtube.com/watch?v=FpVqoYQupSA









![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08-Filamnet_Cutting_mod/blob/main/Photos/SV08_cutting_mod_hotend1.png)

![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08-Filamnet_Cutting_mod/blob/main/Photos/SV08_cutting_mod_hotend.png)




## **1. Prepare parts**

(1) Bambu HOTEND : 1ea

(2) Blade Cutter : 1ea

![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08-Filamnet_Cutting_mod/blob/main/Photos/blade.png)


(3) M3 Insert : 5ea

(4) pen spring : 1ea

(5) space : 2ea

(6) M2*4mm : 1ea  (blade for fixing)

(7) M3*16mm : 3ea

(8) M3*20mm : 5ea

(9) M3*8mm : 1ea

(10) M3 nut : 1ea (required loctite after joint)

(11) M4*16~20 : 1ea



<br>
<br>


## **2. Insert assembly**

인서트를 아래 사진과 같이 삽입을 합니다.

![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08-Filamnet_Cutting_mod/blob/main/Photos/SV08_M3%20insert1.png)
![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08-Filamnet_Cutting_mod/blob/main/Photos/SV08_M3%20insert2.png)
![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08-Filamnet_Cutting_mod/blob/main/Photos/SV08_M3%20insert3.png)
![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08-Filamnet_Cutting_mod/blob/main/Photos/SV08_M3%20insert4.png)
![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08-Filamnet_Cutting_mod/blob/main/Photos/SV08_M3%20insert5.png)


(1) HOTEND와 마운트를 먼저 체결합니다.

![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08_Filament_Cutting_mod/blob/main/Photos/hotend_screw01.png)


(2) 마운트를 헤더에 체결을 합니다.

![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08_Filament_Cutting_mod/blob/main/Photos/hotend_screw02.png)


(3) 레버 마운트를 헤더에 체결합니다.

(4) 컷팅 가이드를 HOTEND 마운트와 체결합니다.


(5) 칼날과 칼날 마운트를 M2 볼트로 조립합니다.

(6) 칼날 조립 부품을 헤더쪽에 가이드에 맞춰 삽입합니다.

(7) 칼날 가이드 레일을 레버 마운트와 M3*20mm 2개로 고정합니다.

(8) 레버 하단부 M3*20mm로 레버 마운트에 체결입니다.<br>
    M3 SPACE(와셔)를 양쪽에 넣어주면 좋습니다.<br>    
    (주의) 레버가 움직이도록 꽉 체결하지 말 것! 움직여야 합니다.<br>

(9) 칼날 마운트 부품과 레버를 조립합니다. <br>
    M3 너트와 체결하며 록타이트로 너트가 빠지지 않도록 합니다.<br>
    (옵션) M3너트 안쪽에  M4 스페이스를 추가해도 됩니다.<br>    
    (주의) 칼날 마운트와 꽉 체결하지 말 것! 움직여야 합니다.<br>
    
![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08_Filament_Cutting_mod/blob/main/Photos/hotend_screw03.png)


(10) 레버를 움직이며 칼날이 자연스레 움직이는지 확인합니다.

![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08_Filament_Cutting_mod/blob/main/Photos/lever_screw01.png)


![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08_Filament_Cutting_mod/blob/main/Photos/hotend_cutting_lever_assembly01.png)







<br>
<br>
<br>

![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08_Filament_Cutting_mod/blob/main/Photos/SV08_Lever_Fixed_bar.png).




## **5. ORCA Slice Machin start-G-code Change**

Must chnage to all x positon X10



<br>
<br>
<br>


## **6. Add Chage Filament G-code** 

![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08_Filament_Cutting_mod/blob/main/Photos/ORCA_Slice_Change_Filament_G-code.png).







<br>
<br>
<br>

## **7. Add macro G-code in Macro.cfg file** 


![Image of ERCF Toolheadsensor](https://github.com/pure100kim/SV08_Filament_Cutting_mod/blob/main/Photos/macro.png).



<br>
<br>
<br>

## **8. Change note**

(1) Basic design NOV 20 ~ DEC.01 2024

(2) DEC 02 (Mon) : Modify lever M2*8mm screw interupt 

(3) DEC 02 (Mon) : screw assembly added

(4) DEC 04 (Wen) : Adjust torrence CAD, printout and assembly

(5) DEC 05 (Thu) : Add Lever & Guide holder.

(6) DEC 05 (Thu) : push bar modeling

(7) DEC 05 (Thu) : Final Testing and macro coding

(8) DEC 05 (Thu) : Relase SV08 Filament Cutting mode


감사합니다.
Thank you!

미스터 굿맨 Mr.goodman 



