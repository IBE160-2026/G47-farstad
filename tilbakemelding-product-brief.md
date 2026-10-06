# Tilbakemelding på product brief

| | |
|---|---|
| **Gruppe** | G47 – G47-farstad |
| **Product brief** | Ingen product brief funnet på main per 2026-10-06 (siste commit `d219a8f`) |
| **Tilbakemelding fra** | Faglærer i IBE160 (utarbeidet med KI-støtte) |
| **Dato** | 2026-10-06 |

## Samlet vurdering

- **Bør revideres før dere går videre.** Rett punktene markert «Endre» før dere lager PRD og arkitektur.

Vi fant ingen product brief eller tilsvarende prosjektbeskrivelse på main i repoet per 2026-10-06. Repoet inneholder bare `README.md` og `.gitignore` fra opprettelsen av gruppeprosjektet, og det finnes ingen commits fra gruppen. Vi har derfor ikke grunnlag for å vurdere prosjektidé, vanskelighetsgrad eller gjennomførbarhet.

**Det viktigste nå:**

1. Endre: Skriv en product brief og legg den i repoet så snart som mulig.
2. Endre: Ta med en begrunnet vurdering av vanskelighetsgrad og gjennomførbarhet, kalibrert mot forslagslista.
3. Endre: Commit og push arbeidet jevnlig, slik at historikken viser hvordan planen utvikler seg.

## Hvorfor product brief er viktig for mappen

Product brief er utgangspunktet for PRD, arkitektur, stories og til slutt koden. Del 1 av mappen vurderes blant annet på om sensor kan følge en sporbar vei fra plan til ferdig app. Den vurderes også på om appen gjør det dere har beskrevet, om den er testet, om den er godt designet, og om den kan kjøres etter README. Et uklart, for stort eller for lite brief gjør alt dette vanskeligere senere. Det er mye enklere å rette nå enn sent i semesteret.

Prosess og KI-styring er det kriteriet som teller mest i del 1 (30 %). Sensor ser etter planleggingsdokumenter fra BMAD som faktisk er brukt og oppdatert, og etter jevn utvikling over tid. Når repoet er tomt i oktober, blir det vanskeligere å vise en slik prosess.

## Hva briefen bør inneholde

Følg BMAD-flyten (product brief → PRD → arkitektur → epics og stories) og bruk gjerne BMAD sin product brief-arbeidsflyt i Claude Code. Faglærers eksempelprosjekt viser hvordan dette kan se ut: https://github.com/IBE160-2026/beergame. Briefen bør dekke disse delene:

| Del av brief | Hva den bør svare på |
|---|---|
| Executive Summary | Hva er appen, og hvilket problem løser den? To–tre setninger. |
| The Problem | Et konkret problem med reelle situasjoner og brukere. |
| The Solution | Hva brukeren opplever og får gjort i appen, ikke bare teknologi. Beskriv én kjerneflyt i 3–5 steg. |
| What Makes This Different | En ærlig vurdering av hva som finnes fra før, og hva som er deres vri. |
| Who This Serves | Én tydelig primærbruker og hva hun trenger. «Alle» er ingen målgruppe. |
| Success Criteria | Kriterier som kan testes, for eksempel «brukeren kan registrere X og se det i oversikten». |
| Scope | Hva som er med i første versjon («In for v1»), og hva som ikke er det («Explicitly out»). |
| Vision | Hvor appen kan gå etter v1, uten å blåse opp omfanget nå. |

I tillegg bør briefen, eller et kort tillegg, inneholde en begrunnet vurdering av **vanskelighetsgrad og gjennomførbarhet**:

- Sammenlign med forslagslista «Prosjektforslag for IBE160». Enkle prosjekter er for eksempel 1) AI Study Buddy, 6) To-do-liste med smarte etiketter og 8) Foredragsnotater – sammendrag og quizgenerator. Middels er 2) AI CV- og søknadsassistent og 7) Kurs-FAQ-chatbot. Vanskelige er 3) KI-styrt simulering av prosjektledelse, 4) KI-støttet MRP II og 5) KI-styrt sensurering.
- Et enkelt prosjekt gir stor sjanse for å bli ferdig, men krever mer i design, testing, dokumentert prosess og README for å nå helt opp. Et vanskelig prosjekt gir større mulighet, men også større risiko.
- Vurder om v1 kan bli ferdig og stabil i løpet av semesteret med hele BMAD-flyten, om dere selv kan kontrollere at KI-ens kode gir riktige svar, og om sensor kan kjøre appen etter README uten deres nøkler eller betalte kontoer. Bruker appen en språkmodell, trenger dere en plan for testmodus eller mock-svar.
## Neste steg for gruppen

1. Velg prosjektidé denne uka, gjerne fra forslagslista hvis dere ikke har en egen idé, og skriv en product brief med delene over. Legg den i repoet, for eksempel i `docs/product-brief.md`.
2. Installer BMAD i repoet og bruk faglærers eksempel (https://github.com/IBE160-2026/beergame) som mønster for struktur og arbeidsflyt.
3. Commit og push briefen, og gå deretter videre til PRD og arkitektur. Ta kontakt med faglærer eller hjelpelærer dersom dere står fast.

Oppdater product brief i repoet når dere har gjort endringene, slik at historikken viser hvordan planen utviklet seg. Det er en del av prosessen sensor ser etter.
