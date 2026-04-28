# Oppgave: Bruk av Copilot i Excel — analyse av spørreundersøkelse

*Praktisk øvelse · 10 minutter*

---

## Format

Excel-fil med ferdig analyse og minst én visualisering, basert på vedlagt datasett.

## Formål

Få egen erfaring med Copilot i Excel som verktøy for å strukturere og analysere data fra en spørreundersøkelse — fra rådata til ledervennlig innsikt på minutter, ikke timer.

## Scenario

Fiktive Nordfjord Industri AS (ca. 250 ansatte) gjennomførte i mars 2026 en spørreundersøkelse blant ansatte om hjemmekontor-politikken. HR har samlet rådata i en Excel-fil og bedt deg som prosjektleder om en kjapp analyse til neste ledermøte. Du har 10 minutter — bruk Copilot.

## Vedlegg

`Hjemmekontor_undersokelse_2026.xlsx` — 84 respondenter, 10 spørsmål av blandet type (single-choice, Likert-skala 1–5, multi-select, fritekst), pluss demografiske felt (avdeling, ansiennitet, rolle, aldersgruppe).

## Forutsetninger

- Du har Microsoft 365 med Copilot-lisens aktivert
- Last ned vedlegget og åpne det i Excel (skrivebords-versjon eller web)
- Konverter dataområdet til en tabell (Sett inn → Tabell, eller Ctrl+T) hvis Copilot ber om det

## Forslag til prompter

Bruk gjerne disse som utgangspunkt — Copilot fungerer best i dialog. Begynn med én, juster basert på hva du får tilbake, og bygg videre.

### Prompt 1 — Strukturer og rens dataene

"Her er data fra en spørreundersøkelse om hjemmekontor-politikken vår. Hjelp meg å strukturere dataene. Avdelingsnavnene er skrevet på mange ulike måter (IT/It/i.t./IT-avdelingen, Salg/Sales/Salgsavdelingen, osv.) — kan du foreslå hvordan jeg får disse harmonisert til én konsistent verdi per avdeling? Sjekk også om det er duplikater eller andre datakvalitetsproblemer jeg bør vite om."

### Prompt 2 — Lag en enkel oversikt

"Lag en oversikt som viser hvor mange ganger hvert svaralternativ har blitt valgt på spørsmål Q2 (tilfredshet med dagens politikk, 1–5). Sorter fra flest svar til færrest. Gi deretter en kort kommentar på hva dette innebærer."

### Prompt 3 — Visualiser et sammenligningsbilde

"Lag en visualisering som sammenligner gjennomsnittlig tilfredshet (Q2) på tvers av avdelinger. Bruk de rensede avdelingsnavnene fra forrige steg."

### Prompt 4 — Utforskende analyse (hvis du har tid)

"Er det noen interessante sammenhenger i disse dataene? Se særlig på om svarene varierer med ansiennitet, rolle (leder vs. ikke-leder) eller avdeling."

## Det dette demonstrerer

- **Strukturering før analyse:** Copilot håndterer "skitt" i rådata — inkonsistente skrivemåter, varierte datoformater, blanke felter — og kan foreslå opprydding
- **Fra spørsmål til svar:** Vanlig naturlig språk gir tabeller, diagrammer og kommentarer uten formler
- **Kritisk vurdering:** Copilot-svar er forslag, ikke fasit. Sjekk om grupperingene gir mening, om visualiseringen faktisk svarer på spørsmålet, og om kommentaren tåler å bli lest av ledelsen.

---

*Tips: Hvis Copilot-ruten ikke viser «Avansert analyse»-knappen, sørg for at dataområdet er konvertert til en Excel-tabell. Funksjonen krever strukturerte tabeller for å fungere.*
