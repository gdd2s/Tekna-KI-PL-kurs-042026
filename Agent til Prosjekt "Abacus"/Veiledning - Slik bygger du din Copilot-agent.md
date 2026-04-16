# 🤖 Veiledning: Slik bygger du din Copilot-agent (Prosjektstøtte)

[cite_start]I denne oppgaven skal du opprette en spesialisert Copilot-agent for det fiktive prosjektet "Abacus"[cite: 10]. [cite_start]Agentens rolle er å fungere som din digitale Prosjektstøtte, med dyp kunnskap om prosjektets dokumentasjon[cite: 10].

---

### Steg 1: Klargjør dokumentasjonen på din PC
[cite_start]Før vi starter i Copilot, må du ha kildematerialet klart[cite: 10].

1.  [cite_start]Finn mappen for Prosjekt Abacus her på GitHub[cite: 10].
2.  [cite_start]Last ned zip-filen som inneholder prosjektdokumentasjonen[cite: 10].
3.  **Viktig:** Høyreklikk på zip-filen og velg "Pakk ut alle" (Unzip). [cite_start]Du må ha de enkelte filene tilgjengelige[cite: 10].
4.  [cite_start]Sørg også for at du har filene `agent-beskrivelse.txt` og `agent-instruksjoner.txt` lett tilgjengelige[cite: 10].

---

### Steg 2: Start opprettelse av ny agent
1.  [cite_start]Åpne Copilot i din nettleser[cite: 10].
2.  [cite_start]I navigasjonsruten til venstre, klikk på "Ny agent" (eller pluss-tegnet)[cite: 10].
3.  [cite_start]Du vil nå se to valg øverst: "Beskriv" og "Konfigurer"[cite: 10].
4.  [cite_start]**Velg "Konfigurer"-modus.** (Vi skal legge inn instruksene manuelt for maksimal presisjon)[cite: 10].

---

### Steg 3: Legg inn profil og instruksjoner
[cite_start]Nå skal vi definere hvem agenten er og hvordan den skal jobbe[cite: 10].

1.  [cite_start]**Navn:** Gi agenten et navn (f.eks. Abacus Prosjektstøtte)[cite: 10].
2.  [cite_start]**Beskrivelse:** Åpne filen `agent-beskrivelse.txt`, kopier teksten og lim den inn i feltet for beskrivelse[cite: 10].
3.  [cite_start]**Instruksjoner:** Åpne filen `agent-instruksjoner.txt`, kopier hele innholdet og lim det inn i feltet for instruksjoner[cite: 10].

---

### Steg 4: Tilføre kunnskap (Datakilder)
[cite_start]Dette er hjertet i agenten din[cite: 10]. [cite_start]Du har to måter å gi den tilgang til Abacus-dokumentasjonen på[cite: 10]. Velg det som passer deg best:

**Alternativ A: Direkte opplasting (Raskest under kurset)**
1.  [cite_start]Finn feltet for Kunnskap eller Datakilder i Copilot[cite: 10].
2.  [cite_start]Klikk på "Last opp filer" og velg alle de utpakkede filene fra zip-filen du klargjorde i Steg 1[cite: 10].

**Alternativ B: SharePoint-mappe (Slik man gjør det i ekte prosjekter)**
1.  [cite_start]Last opp de utpakkede filene fra zip-filen til en mappe i din egen organisasjons SharePoint[cite: 10].
2.  [cite_start]I Copilot (Konfigurer-modus), gå til feltet for Kunnskap og velg **Legg til SharePoint**[cite: 10].
3.  [cite_start]Lim inn URL-en til SharePoint-mappen der du la Abacus-filene[cite: 10].
    * [cite_start]*Dette er fordelen i virkelige prosjekter: Agenten vil automatisk kjenne til endringer hvis du oppdaterer dokumentene i mappen senere[cite: 10].*

---

### Steg 5: Begrens agentens informasjonskilder
[cite_start]For å unngå at agenten begynner å gjette eller henter generell informasjon fra internett, skal vi låse den til dine data[cite: 10].

1.  [cite_start]Finn innstillingen som heter **"Bruk bare angitte datakilder"**[cite: 10].
2.  [cite_start]**Slå denne PÅ.** [cite: 10]
3.  [cite_start]Dette sikrer at agenten kun svarer basert på Abacus-dokumentasjonen du nettopp koblet til[cite: 10].

---

### Steg 6: Ferdigstill og test
1.  [cite_start]Klikk på knappen **"Opprett"** (eller Lagre)[cite: 10].
2.  Gratulerer! [cite_start]Du har nå din egen "Prosjektstøtte"-agent[cite: 10].
3.  [cite_start]Prøv å stille den et spørsmål, for eksempel: *"Hva er de viktigste milepælene i Prosjekt Abacus de neste tre månedene?"* [cite: 10]

---

### Tips til refleksjon:
* [cite_start]**Hvorfor SharePoint?** Ved å bruke SharePoint (Alternativ B) lever agenten sammen med prosjektet[cite: 10]. [cite_start]Hvis prosjektplanen endres i SharePoint-mappen, vil agenten vite det umiddelbart uten at du må laste opp filer på nytt[cite: 10].
* [cite_start]**Sikkerhet:** Ved å slå på "Bruk bare angitte datakilder", lager du en trygg "sandkasse" hvor du vet nøyaktig hvilken informasjon KI-en bruker for å gi deg svar[cite: 10].
