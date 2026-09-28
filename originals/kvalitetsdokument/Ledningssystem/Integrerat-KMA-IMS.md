# Integrerat KMA-system (ISO 9001 + 14001 + 45001)

## Översikt
Ett integrerat ledningssystem (IMS / KMA) kombinerar kvalitet, miljö och arbetsmiljö i ett gemensamt ramverk baserat på High Level Structure (Annex SL). Detta minskar dubbelarbete avsevärt.

## Möjliga integrerade kombinationer

| Kombination                  | Vanligt namn       | Rekommenderad för                  |
|------------------------------|--------------------|------------------------------------|
| ISO 9001 + ISO 14001        | Kvalitet + Miljö   | Tillverkning, leverantörer         |
| ISO 9001 + ISO 45001        | Kvalitet + Arbetsmiljö | Bygg, industri, service       |
| ISO 14001 + ISO 45001       | Miljö + Arbetsmiljö | Kemikaliehantering, verkstäder   |
| ISO 9001 + 14001 + 45001    | Fullt KMA / IMS    | De flesta små/medelstora företag   |

## Huvudstruktur (gemensam för alla)

| Kapitel | Avsnitt | Gemensamt innehåll |
|---------|---------|--------------------|
| 4 | Kontexten | Scope, intressenter, risker/aspekter |
| 5 | Ledarskap | **Integrerad KMA-policy**, roller |
| 6 | Planering | **Integrerad riskbedömning**, lagkrav, mål |
| 7 | Stöd | Kompetens, dokumentstyrning |
| 8 | Verksamhet | Operationell kontroll, nödsituationer |
| 9 | Utvärdering | Övervakning, intern revision, ledningsgenomgång |
| 10 | Förbättring | Avvikelsehantering, kontinuerlig förbättring |

## Samtliga kärndokument i ett integrerat system

### Gemensamma dokument
1. **Integrerad KMA-policy**
2. Scope / Verksamhetsbeskrivning
3. Uppgiftsfördelning / ansvarsmatris
4. **Integrerad risk- & möjligheterbedömning** (kvalitet + miljöaspekter + arbetsmiljörisker)
5. Samlat lagkravsregister
6. Gemensamma mål & handlingsplaner
7. Processbeskrivningar med KMA-aspekter
8. Dokument- och versionshantering
9. Kompetensmatris
10. Nödsituationer & beredskapsplan
11. Avvikelse- & tillbudshantering
12. Intern revision (täcker alla tre)
13. Ledningsgenomgång (en per år)
14. Övervakning & KPI:er

### Specifika tillägg per område (valfria)
- Kvalitet: Kundnöjdhet, processkartor, leverantörsbedömning
- Miljö: Miljöaspektsregister, avfallsplan, kemikalieförteckning
- Arbetsmiljö: Riskbedömning (fysisk/psykosocial), SAM-rutiner

## Rekommenderad mappstruktur (modulär)

```
src/features/operations/kma/
├── policy/                    ← Integrerad KMA-policy
├── scope-context/
├── risk-mojligheter/          ← Integrerad riskbedömning (viktigast)
├── lagkrav/                   ← Samlat register (filtreras per standard)
├── mal-handlingsplan/
├── processer/
├── dokumentstyrning/
├── kompetens/
├── emergency/
├── avvikelse-tillbud/
├── revision-ledningsgenomgang/
├── kvalitet/                  ← Specifika tillägg (valfritt)
├── miljo/
└── arbetsmiljo/
```

## Modulär design i Quality Works Small
- Kunden väljer vilka standarder de vill ha (checkboxar)
- Systemet visar bara relevanta fält och dokument
- En app – tre (eller färre) certifieringar

## Fördelar med integrerat system
- Upp till 60-70% mindre administration
- En policy, en revision, en ledningsgenomgång
- Bättre helhetssyn
- Starkt konkurrensmedel vid upphandlingar

## Tips för implementation
1. Börja med integrerad riskbedömning
2. Skapa en gemensam policy
3. Använd digitala formulär för enkelhet
4. Planera en gemensam intern revision

---
*Skapad för Quality Works Small – Praktiska och prisvärda verktyg för småföretag*
