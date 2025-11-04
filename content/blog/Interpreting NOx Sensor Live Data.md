---
title: Diagnostikos menas NOx jutiklio tiesioginių duomenų interpretavimas
description: Efektyviam SCR sistemos remontui reikia ne tik nuskaityti gedimų kodus, bet ir įsigilinti į jutiklio realiojo laiko duomenų srautą.
breadcrumbs: true
date: "2024-10-31T00:35:28+08:00"
draft: false
---
## Išsami diagnostika: „NOx“ jutiklio realiojo laiko duomenų interpretavimas

Efektyviam SCR sistemos remontui reikia ne tik nuskaityti gedimų kodus, bet ir įsigilinti į jutiklio realiojo laiko duomenų srautą. Ši realiojo laiko informacija yra raktas į tikslią problemų, nesvarbu, ar jos susijusios su pačiu jutikliu, ar su platesne išmetamųjų teršalų sistema (pvz., DEF dozavimu arba SCR katalizatoriumi), diagnostiką.

### **1. Prieš srovę ir Pasroviui esančių „NOx“ jutiklių palyginimas (konversijos efektyvumas)**

Svarbiausia diagnostikos funkcija yra palyginti dviejų „NOx“ jutiklių rodmenis.

* **Prieš srovę esantis jutiklis (įvade):** matuoja „NOx“ koncentraciją, patenkančią į SCR katalizatorių. Ši vertė atspindi „NOx“ iš variklio.
* **Pasroviui esantis jutiklis (išvade):** matuoja „NOx“ koncentraciją, išeinančią iš SCR katalizatoriaus. Ši vertė atspindi „NOx“ išmetimo vamzdyje.
* **Interpretacija:** sveikoje, įšilusioje SCR sistemoje „NOx“ rodmuo išvade turi būti žymiai mažesnis nei „NOx“ rodmuo įvade. Sveikas SCR konversijos efektyvumas paprastai yra **80 % arba didesnis**.
    * *Jei tiek įvado, tiek išvado rodmenys yra aukšti ir beveik identiški, tai dažnai rodo sugedusį SCR katalizatorių, rimtą DEF dozavimo problemą arba vieno iš „NOx“ jutiklių gedimą*.

### **2. Amoniako kryžminio jautrumo dekodavimas (pratekėjimo indikatorius)**

„NOx“ jutikliai naudoja elektrocheminius principus, dėl kurių jie yra jautrūs amoniakui ($NH_3$), aktyviam reduktoriui DEF. Šis akivaizdus trūkumas naudojamas kaip saugos funkcija.

* **Į ką atkreipti dėmesį:** jei DEF dozavimo greitis yra per didelis, nesureagavęs $NH_3$ „pratekės“ pro SCR katalizatorių. Kai pasroviui esantis „NOx“ jutiklis aptinka šį $NH_3$ pratekėjimą, jo išvesties rodmuo **laikinai šoktels aukštyn**.
* **Interpretacija:** staigus didelis „NOx“ jutiklio išvade rodmuo, kuris nesusijęs su variklio apkrovos pokyčiais, dažnai yra **amoniako pratekėjimo**, o ne „NOx“ šuolio, rodiklis. Tai rodo problemą su DEF dozavimo valdymu, o ne būtinai sugedusį „NOx“ jutiklį.
* **Mūsų pranašumas:** mūsų jutikliai užtikrina labai stabilų signalo išėjimą, todėl ECU lengviau atskirti tikruosius „NOx“ svyravimus nuo $NH_3$ kryžminio jautrumo šuolių.

### **3. Vidinės būsenos parametrų stebėjimas**

Išplėstiniai diagnostikos įrankiai leidžia technikams peržiūrėti vidinius jutiklio parametrus, kurie dažnai yra pirmieji gresiančio gedimo požymiai.

| Parametras | Funkcija | Nukrypimo interpretacija |
| :--- | :--- | :--- |
| **Vidinė jutiklio temperatūra** | Faktinė jutimo elemento temperatūra. | Jei varikliui įšilus vertė yra per maža arba nestabili, įtarkite šildytuvo grandinės arba maitinimo šaltinio problemą. |
| **Šildytuvo srovė** | Elektrinė srovė, kurią naudoja kaitinimo elementas. | Neįprastai didelis arba mažas srovės suvartojimas rodo gendančią kaitinimo elementą arba modulio maitinimo problemą. |
| **Jutiklio būsenos vėliavėlės** | Dvejetainis kodas, nurodantis dabartinį jutiklio veikimo režimą (pvz., Šildymas, Matavimas, Klaida). | Jei vėliavėlė per ilgai užstrigo ties „Šildymas“ arba „Klaida“, tikėtina, kad jutiklis sugedo viduje. |

Įvaldydamos šių realiojo laiko duomenų srautų interpretavimą, techninės priežiūros komandos gali tiksliai nustatyti išmetamųjų teršalų gedimų pagrindinę priežastį, drastiškai sumažindamos prastovos laiką ir užkirsdamos kelią nereikalingam komponentų keitimui.

---
Ar norėtumėte, kad patikrinčiau bet kurį konkretų terminą, susijusį su „NOx“ jutikliais ar SCR sistemomis, lietuvių kalba?