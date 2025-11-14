# Informační systém pro turistické skupiny skauty a podobně

## Krátký popis
Webová aplikace určená pro skautské oddíly, která slouží ke správě členů, vedoucích a skupin, plánování akcí, evidenci účasti, správě plateb a sdílení fotografií z akcí.

---

## Cíl systému a cílová skupina
**Cíl systému:**  
Cílem projektu je vytvořit jednotný informační systém pro vodní skautský oddíl, který nahradí papírové a tabulkové evidence. Systém umožní efektivní plánování, komunikaci a správu členské základny včetně rodičů mladších členů.

**Cílová skupina:**  
- zájmové skupiny a jejich členové
- skautské oddíly 

---

## Role a oprávnění

### **Admin**
- Spravuje celý systém a všechna data.  
- Přidává, upravuje a maže uživatelské účty.  
- Nastavuje oprávnění pro jednotlivé role.  
- Spravuje databázi akcí, skupin a fotogalerií.  
- Zajišťuje zálohování dat.

### **Hlavní vedoucí**
- Schvaluje nové akce a rozdělení členů do skupin.  
- Vidí kompletní přehled členů, vedoucích a plateb.  
- Generuje statistiky účasti a přehled plateb.  
- Může upravovat údaje všech uživatelů.  

### **Vedoucí oddílu**
- Plánuje akce pro svůj oddíl (výpravy, schůzky, tábory).  
- Sleduje účast členů na akcích.  
- Spravuje seznam členů a vedoucích skupin ve svém oddílu.  
- Nahrává fotografie z akcí do fotogalerie oddílu.  

### **Vedoucí skupiny (družiny)**
- Spravuje členy své skupiny (docházka, účast na akcích).  
- Může přidávat nové akce skupiny a zvát členy.  
- Zaznamenává plnění úkolů nebo odborek členů.  

### **Člen**
- Vidí svůj profil, přehled akcí a účast.  
- Přihlašuje se / odhlašuje z plánovaných akcí.  
- Sleduje své platby členství a příspěvků.  
- Může přidávat komentáře nebo hodnocení k akcím.  

### **Rodič**
- Vidí profil svého dítěte (člena).  
- Potvrzuje účast dítěte na akcích.  
- Má přehled o platbách, přihláškách a fotkách z akcí.  

---

##  Spravovaná data
| Typ dat | Popis |
|----------|--------|
| **Členové** | Jméno, příjmení, datum narození, kontakt, zdravotní informace, role, skupina, stav plateb |
| **Vedoucí** | Jméno, funkce, kontaktní údaje, oddíl/skupina |
| **Skupiny (družiny)** | Název, vedoucí, seznam členů |
| **Akce** | Název, typ (schůzka, výprava, tábor, akce pro veřejnost), datum, místo, popis, seznam přihlášených |
| **Účast** | Jméno člena, účast (ANO/NE), poznámky, potvrzení rodičem |
| **Platby** | Typ platby (členství, akce, tábor), částka, datum, stav (zaplaceno/neuhrazeno) |
| **Fotogalerie** | Název alba, datum, popis, nahrané fotografie, přidružená akce |
| **Zprávy** | Interní komunikace mezi vedoucími, členy a rodiči |

---

##  Základní funkce systému
- **Správa členů a vedoucích** – přidávání, úprava, filtrování podle skupin.  
- **Plánování akcí** – přehledný kalendář s možností přihlášení.  
- **Seznam účastníků** – zobrazení, kdo se přihlásil na akci, potvrzení účasti.  
- **Evidence plateb** – přehled zaplacených a chybějících příspěvků.  
- **Fotogalerie** – sdílení fotek z akcí, propojené s konkrétními událostmi.  
- **Oznámení a zprávy** – možnost komunikace uvnitř systému.  

---

##  Bezpečnost a přístup
- Každý uživatel má vlastní přihlašovací údaje (jméno + heslo).  
- Role určují, k jakým datům má kdo přístup.  
- Citlivé údaje (např. zdravotní) jsou přístupné pouze vedoucím a rodičům.  
- Data jsou pravidelně zálohována a uložena v souladu s GDPR.  

---

##  Možná rozšíření do budoucna
- Mobilní aplikace pro rychlé potvrzení účasti na akci.  
- Export přehledů do PDF (např. seznam účastníků, stav plateb).  
- Napojení na mapu (zobrazení míst konání akcí).  
- Modul pro evidenci plavebních deníků a odznaků.  

**Autor:** *Lukáš Vlček*  
**Datum:** *listopad 2025*
