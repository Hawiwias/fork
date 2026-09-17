MCU = mikrokontrolér, integrovany obvod obsahujici mikropocitac, jednocipovy obvod,
jednoduche akce jako rizeni, regulace, apod., je ve vestavenem embedded systemu, ESP32/Intel i8051
cipy ve smart prackach, mikrovlnkach, Arduino, STM32, Raspberry Pi
MPU = mikroprocesor, obsazene v cpu - cele v integrovanem obvodu, PC, pracuje v dvojkove soustave, startuje okamzite po zapnuti, vyzaduje externi ram a bezi na OS
embedded = vestaveny system, jsou vetsinou specializovane pro jeden ucel na rozdil od pocitace, massprodukce,
rychlost a jednouduche pouziti, bankomat, kalkulacky, herni konzole
PLC = programmable logic controller, Foxtrot, maly prumyslovy pocitac slouzici k automizaci, pracuje v cyklech, 
neslouzi k osobni potrebe, v tovarne na vyrobu, kompaktni - pevna konfigurace a modularni - volna konfiguraci, vysoka odolnost, SIMATIC S7-1200
iPC - instructions per cycle, meritko efektivity procesoru, prumerne cislo instrukci spustenych v cyklu,
iPC = celkovy pocet instrukci / celkovy pocet cyklu
NC - Numerical Control, automaticke rizeni stroju pomoci kodovanych instrukci, CNC stroje, 3D stroje, soustruhy
programovatelná relé (mini-PLC)  - obsahuje jak PLC tak i rele soucastky, nastaveni pomoci USB/LAN, PAPOUCH QUIDO_USB_4, Eaton easyE4
vypocetni vykon - parametr, ktery urcuje jak rychle a efektivne dokaze pocitac zpracovavat data a plnit ulohy
MCU vs MPU - MPU ma mnohem vetsi vypocetni vykon, MCU - MHz, MPU - GHZ
PLC - male - vsechno slozene v jednom tele, mala kapacita a vykon, hodi se pro jednoduche stroje, domovni
instalace, velke - skladaji se z externich komponentu (samostatne CPU, zdroj, karet), zvladaji tisice az desetitisice
instrukci, velka pamet, pouziti ve tovarnach, vyrobni linky, vysoky vykon
MPU - potrebuje externi cipy RAM, MCU - obsahuje vnitri pamet, PLC - vnitrni RAM pamet + zalohovana pamet (EEPROM, 
SD karty)
pouzijeme MPU protoze system preferuje propustnost a spravedlive rozdeleni vykonu pred rychlosti MCU
RAM - docasne uloziste pro bezici programy a data, flash pamet - trvale uloziste aplikaci a dat, EEPROM - velmi male uloziste pro bezici konfiguraci, nesmi zmizet pri vypnuti
robustnost - schopnost systemu odolavat chybam, errorum, necekanym zmenam a zatezi
odolnost - pouzijeme lepsi kryti IP (Ingress Protection), pouzijeme IP68
IP68 - 6 = ochrana proti prachu, 8 = odolnost proti dlouhemu ponoreni do vody
minimalni ochrana pro montaz ven pod strechu - IP23
výpočetní technika pro běžné uživatele - osobni pouziti, slabsi komponenty, jednoduche pouziti
řídící jednotky pro průmysl - vhodny pro massprodukci, slozita konfigurace, postaveny pro dlouhodobe vyrabeny produktu