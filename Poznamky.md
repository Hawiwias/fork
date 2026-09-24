# MCU
**Micro Controller Unit**
mikrokontrolér, integrovaný obvod obsahující mikropočitač, jednočipový obvod,
jednoduché akce jako řízení, regulace, apod., je ve vestavěném embedded systému, příklady: ESP32/Intel i8051,
čipy ve smart pračkách, mikrovlnkách, Arduino, STM32, Raspberry Pi

# MPU
**Micro Processor Unit**
mikroprocesor, obsažené v CPU - celé v integrovaném obvodu, PC, pracuje v dvojkové soustavě, startuje okamžitě po zapnutí, vyžaduje externí RAM a běží na OS
**použijeme MPU, protože systém preferuje propustnost a spravedlivé rozdělení výkonu před rychlostí MCU**

## MCU vs. MPU
MPU má mnohem větší výpočetní výkon, MCU - MHz, MPU - GHz

# Embedded
**Vestavěný systém**
Jednoúčelový počítač, který je zabudován do zařízení, které ovládá. Jsou navrženy pro konkrétní účely
massprodukce, rychlost a jednoduché použití, bankomaty, kalkulačky, herní konzole, elektrospotřebiče

## PLC
**Programmable Logic Controller**
Foxtrot, malý průmyslový počítač sloužící k automatizaci, pracuje v cyklech, 
neslouží k osobní potřebě, v továrně na výrobu, kompaktní - pevná konfigurace a modulární - volná konfigurace, vysoká odolnost, SIMATIC S7-1200

# IPC
**Industrial PC**
Industriální počítač používaný ve firmách, většinou server, mají vyšší standardy spolehlivosti a přesnosti, nejčastěji řízeny Linuxem

# NC
**Numerical Control**
automatické řízení strojů pomocí kódovaných instrukcí, CNC stroje, 3D stroje, soustruhy,

## programovatelná relé (mini-PLC)
obsahuje jak PLC, tak i relé součástky, nastavení pomocí USB/LAN, PAPOUCH QUIDO_USB_4, Eaton easyE4

## Základní parametry
### **výpočetní výkon**
*parametr, který určuje, jak rychle a efektivně dokáže počítač zpracovávat data a plnit úlohy*

### **robustnost** 
*schopnost systému odolávat chybám, errorům, nečekaným změnám a zátěži*

### **odolnost** 
*jak moc odolává vůči desti, prachu, atd.* 
*použijeme lepší krytí IP (Ingress Protection), použijeme IP68*

### **IP68**
6 - ochrana proti prachu, 8 - odolnost proti dlouhému ponoření do vody*

*minimální ochrana pro montáž ven pod střechu - IP23*

# PLC
**malé** - všechno složené v jednom těle, malá kapacita a výkon, hodí se pro jednoduché stroje, domovní
instalace

**velké** - skládají se z externích komponentů (samostatné CPU, zdroj, karet), zvládají tisíce až desetitisíce
instrukcí, velká paměť, použití v továrnách, výrobní linky, vysoký výkon

## Potřebná paměť

**MPU - potřebuje externí čipy RAM**

**MCU - obsahuje vnitřní paměť**

**PLC - vnitřní RAM paměť + zálohovaná paměť (EEPROM, SD karty)**

**Rozdělení paměti**
**RAM** - dočasné úložiště pro běžící programy a data 
**flash paměť** - trvalé úložiště aplikací a dat
**EEPROM** - velmi malé úložiště pro běžící konfiguraci, nesmí zmizet při vypnutí

## Výpočetní technika pro běžné uživatele vs. pro průmysl

**výpočetní technika pro běžné uživatele** - osobní použití, slabší komponenty, jednoduché použití

**řídicí jednotky pro průmysl** - vhodný pro massprodukci, složitá konfigurace, postavený pro dlouhodobě vyráběný produkt
