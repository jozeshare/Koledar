# Sorško polje — iCalendar naročnine

Datoteke `.ics` so pripravljene po kategorijah. Ljudje jih dodajo v Google / Apple / Outlook koledar.

## Kategorije

| Datoteka | Koledar | Vsebina |
|---|---|---|
| `00-vse.ics` | Vse (agregat) | Vse spodnje kategorije skupaj |
| `01-trznice.ics` | Tržnice | Mavška (4. petek), Stražiška (2. petek) — RRULE |
| `02-vrtovi.ics` | Vrtovi | Praše (sreda), Barka Zbilje (torek) — RRULE |
| `03-lastni-dogodki.ics` | Lastni dogodki | Sestanki, pohodi, eko praznik, ogledi |
| `04-predavanja.ics` | Predavanja in tečaji | Antropozofija, DOPPS, kreativno pisanje, Steiner |
| `05-narava.ics` | Narava in ptice | DOPPS (začetek; dopolni z napovednikom) |
| `06-festivali.ics` | Festivali | Lahko.si, Teden podeželja, biodinamika, eko praznik |
| `07-drugi-organizatorji.ics` | Drugi organizatorji | Razdelek iz digesta Sorško polje |

## Kako se naročiti (za uporabnike)

**Google Koledar:** Nastavitve → Dodaj koledar → Iz URL-ja → prilepi javni `https://…/01-trznice.ics`  
**Apple:** Datoteka → Nov koledarski naročniški račun → URL  
**Outlook:** Dodaj koledar → Iz interneta

Za naročnino potrebuješ **javni HTTPS URL** do `.ics` (ne lokalne datoteke). Lokalno lahko datoteko tudi enkrat uvoziš (File → Import).

## Opombe

- Časi vrtov: splet pravi 16–19 (jul–avg od 17); v digesti so bili tudi 16–18 / 17–19. RRULE uporablja 16–18 — prilagodi po želji.
- Steiner termini v mailu mešajo 2025/2026 — v koledarju je prvo srečanje 6. 10. 2026 + rok prijave.
- Za sprotno osveževanje: parser Kit digesta + RSS DOPPS/Medvode + TeamUp ICS (ko dobiš pravi link).
