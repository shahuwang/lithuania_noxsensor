---
title: Šildytuvo grandinės esminis vaidmuo NOx jutiklio veikime
description: NOx jutiklis yra pažangus elektrocheminis prietaisas, veikiantis esant fundamentaliam reikalavimui **aukštai temperatūrai**. 
breadcrumbs: true
date: "2024-02-01T00:35:28+08:00"
draft: false
---
## Pagrindinis Šildytuvo Grandinės Vaidmuo NOx Jutiklio Veikime

NOx jutiklis yra pažangus elektrocheminis prietaisas, veikiantis esant fundamentaliam reikalavimui: **aukštai temperatūrai**. Sudėtingoms jutiklio cirkonio pagrindo jutimo celėms reikia palaikomos temperatūros tarp 700 laipsnių Celsijaus ir 800 laipsnių Celsijaus, kad jos veiktų tinkamai. Tai pasiekiama naudojant specialią, integruotą šildytuvo grandinę. Kai ši grandinė sugenda, jutiklis tampa nenaudingas, nepaisant jo fizinės būklės.

### **Vidinio Šildytuvo Dviguba Funkcija**

Šildytuvas, be abejonės, yra labiausiai apkrautas komponentas NOx jutiklyje, atliekantis du gyvybiškai svarbius vaidmenis:

1.  **Matavimo Įjungimas:** Esant žemesnei išmetamųjų dujų temperatūrai (pvz., paleidimo metu ar esant mažai apkrovai), šildytuvas greitai pakelia keraminę celę iki reikiamos darbinės temperatūros. Be šios temperatūros deguonies jonų judrumas, kuris yra elektrocheminio NOx matavimo variklis, yra nepakankamas.
2.  **Savaiminis Valymas (Suodžių Šalinimas):** Aukšta temperatūra, palaikoma šildytuvo, yra būtina suodžių ir drėgmės deginimui. Ši savaiminio valymo funkcija reikalinga siekiant išvengti užsiteršimo ir signalo blokavimo, kurie yra pagrindinės signalo dreifo priežastys.

### **Šildytuvo Gedimo Priežastys ir Diagnostika**

Šildytuvo grandinės gedimai paprastai skirstomi į dvi kategorijas, abi iš karto užregistruojamos ECU kaip diagnostiniai gedimų kodai (DTC) P2200 diapazone (pvz., P2205 Šildytuvo Valdymo Grandinės Gedimas).

| Gedimo Tipas | Aprašymas | Diagnostinis požymis (Tiesioginiai Duomenys) |
| :--- | :--- | :--- |
| **Atvira Grandinė (Dažniausias)** | Kaitinimo elemento ritė nutrūksta dėl šiluminio įtempio ar įtrūkimo. | **Šildytuvo Srovė yra Nulis.** ECU duoda komandą srovei, bet jutiklis praneša, kad jos nėra. Vidinė temperatūra išlieka žema. |
| **Trumpasis Jungimas** | Trumpasis jungimas įvyksta laiduose arba elemento ritėje. | **Šildytuvo Srovė yra Neįprastai Didelė.** Tai suaktyvina ECU galios ribojimo apsaugą, išjungiančią grandinę. |
| **Valdymo Logikos Gedimas** | Jutiklio vidinis modulis netinkamai reguliuoja impulso pločio moduliavimo (PWM) signalą šildytuvui. | Šildytuvas įsijungia ir išsijungia nereguliariai, o tai sukelia stipriai svyruojančią vidinę temperatūrą ir NOx rodmenis. |

### **Pasekmė: SCR Sistemos Išjungimas**

Kai šildytuvo grandinė sugenda, ECU negali gauti galiojančio NOx rodmens. Tai nedelsiant suaktyvina sistemos apsaugos protokolus:

* ECU sustabdo DEF dozavimą, nes negali patikrinti poveikio.
* Automobilio išmetamųjų teršalų kontrolės sistema laikoma neveikiančia, o tai sukelia privalomus įspėjimus ir galiausiai, **galios sumažinimą (Avarinis Režimas)**, siekiant užtikrinti atitiktį.

Mūsų pakaitiniai jutikliai turi aukščiausios kokybės kaitinimo elementus ir OEM lygio valdymo elektroniką, kurie yra griežtai išbandyti atsižvelgiant į ekstremalų šiluminį ciklą, siekiant užkirsti kelią priešlaikiniam šildytuvo gedimui ir užtikrinti nuolatinį pasirengimą matavimui.
