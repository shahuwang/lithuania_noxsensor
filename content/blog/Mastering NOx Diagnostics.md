---
title: NOx diagnostikos įvaldymas
description: NOx diagnostikos įvaldymas naudojant įleidimo ir išleidimo duomenis SCR efektyvumui nustatyti
breadcrumbs: true
date: "2023-12-10T00:35:28+08:00"
draft: false
---
### **NOx diagnostikos įvaldymas: įleidimo ir išleidimo duomenų naudojimas SCR efektyvumui nustatyti**

Pagrindinė dviejų NOx jutiklių, esančių transporto priemonės išmetimo sistemoje, funkcija – leisti variklio valdymo blokui (ECU) realiuoju laiku apskaičiuoti selektyviosios katalitinės redukcijos (SCR) konversijos efektyvumą. Šis efektyvumo skaičiavimas yra pagrindinis rodiklis tiek išmetamųjų teršalų kontrolei, tiek borto diagnostikai (OBD).

### **Pagrindinis skaičiavimas: SCR konversijos efektyvumas**

SCR sistemos veikimas kiekybiškai įvertinamas pagal tai, kiek NOx paverčiama nekenksmingu N2 (azotu) ir H2O (vandeniu). ECU naudoja paprastą dviejų jutiklių rodmenų santykį šiam stebėjimui:

> **SCR konversijos efektyvumas (%) = ((Įleidimo NOx – Išleidimo NOx) / Įleidimo NOx) x 100**

### **Tiesioginių duomenų scenarijų interpretavimas**

Įleidimo (Upstream) ir išleidimo (Downstream) NOx rodmenų santykio analizė padeda nustatyti pagrindinę išmetamųjų teršalų gedimo priežastį:

| Įleidimo NOx rodmuo | Išleidimo NOx rodmuo | SCR efektyvumas | Diagnozė |
| :--- | :--- | :--- | :--- |
| **Didelis (~800 ppm)** | **Mažas (~100 ppm)** | **Didelis (~87% - 90%)** | **Sistema veikia normaliai:** DEF dozavimas yra teisingas, o SCR katalizatorius aktyvus. |
| **Didelis** | **Didelis (≈ Įleidimo)** | **Mažas (~0% - 30%)** | **Katalizatoriaus arba dozavimo gedimas:** SCR nesumažina NOx. Pirmiausia patikrinkite DEF sistemą, tada įtarkite katalizatoriaus degradaciją. |
| **Nepagrįstas/įstrigęs** | **Normalus** | **Netinkamas** | **Įleidimo jutiklio gedimas:** ECU negali pasitikėti Įleidimo rodmeniu, todėl dozavimas yra netinkamas (dažnai remiantis atsarginiu modeliu). **Pakeiskite Įleidimo jutiklį.** |
| **Normalus** | **Nepagrįstas/įstrigęs** | **Netinkamas** | **Išleidimo jutiklio gedimas:** ECU negali patikrinti atitikties. **Pakeiskite Išleidimo jutiklį.** |

### **OBD monitorius ir gedimų slenksčiai**

ECU nuolat stebi šį efektyvumo santykį. Jei apskaičiuotas SCR efektyvumas nukrenta žemiau teisiškai nustatyto OBD slenksčio (pvz., 80 %) nustatytam važiavimo laikotarpiui, ECU užfiksuoja efektyvumo gedimo kodą (P420 arba P20EE atitikmenį).

Svarbu tai, kad neteisingas rodmuo iš **bet kurio** – tiek Įleidimo, tiek Išleidimo NOx jutiklio – iškreips šį skaičiavimą, todėl ECU neteisingai pažymės katalizatoriaus arba dozavimo gedimą, o tai sukels nereikalingų remonto išlaidų.

Mūsų jutikliai teikia patvirtintus, stabilius ir sinchroniškus rodmenis, užtikrinančius, kad ECU efektyvumo skaičiavimas visada remtųsi patikimais duomenimis, o tai leidžia technikams pasitikėti sistemos diagnostinėmis išvadomis.
