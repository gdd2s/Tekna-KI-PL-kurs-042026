# 🤖 Veiledning: Slik bygger du din Copilot-agent (Prosjektstøtte)

I denne oppgaven skal du opprette en spesialisert Copilot-agent for det fiktive prosjektet **"Abacus"**. Agentens rolle er å fungere som din digitale Prosjektstøtte, med dyp kunnskap om prosjektets dokumentasjon.

---

### Steg 1: Klargjør dokumentasjonen på din PC
Før vi starter i Copilot, må du ha kildematerialet klart.

1.  Finn mappen for Prosjekt Abacus her på GitHub.
2.  Klikk på og så last ned **zip-filen** som inneholder prosjektdokumentasjonen.
3.  **Viktig:** Etter nedlasting, høyreklikk på zip-filen og velg **"Pakk ut alle"** (Unzip). Du må ha de enkelte filene tilgjengelige for opplasting.
4.  Sørg også for at du har filene `agent-beskrivelse.txt` og `agent-instruksjoner.txt` lett tilgjengelige.

---

### Steg 2: Start opprettelse av ny agent
1.  Åpne Copilot i din nettleser: https://copilot.microsoft.com/
2.  I navigasjonsruten til venstre, klikk på **"Ny agent"** (eller pluss-tegnet).
3.  Du vil nå se to valg øverst: "Beskriv" og "Konfigurer".
4.  **Velg "Konfigurer"-modus.** (Vi skal legge inn instruksene manuelt for maksimal presisjon).

---

### Steg 3: Legg inn profil og instruksjoner
Nå skal vi definere hvem agenten er og hvordan den skal jobbe.

1.  **Navn:** Gi agenten et navn (f.eks. *Abacus Prosjektstøtte*).
2.  **Beskrivelse:** Åpne filen `agent-beskrivelse.txt`, kopier teksten og lim den inn i feltet for beskrivelse.
3.  **Instruksjoner:** Åpne filen `agent-instruksjoner.txt`, kopier hele innholdet og lim det inn i feltet for instruksjoner. Dette er agentens "kjøreregler".

---

### Steg 4: Tilføre kunnskap (Datakilder)
Dette er hjertet i agenten din. Du har to måter å gi den tilgang til Abacus-dokumentasjonen på. Velg det som passer deg best:

**Alternativ A: Direkte opplasting (Raskest under kurset)**
1.  Finn feltet for **Kunnskap** eller **Datakilder** i Copilot.
2.  Klikk på **"Last opp filer"** og velg alle de utpakkede filene fra zip-filen du klargjorde i Steg 1.

**Alternativ B: SharePoint-mappe (Slik man gjør det i ekte prosjekter)**
1.  Last opp de utpakkede filene fra zip-filen til en mappe i din egen organisasjons SharePoint.
2.  I Copilot (Konfigurer-modus), gå til feltet for **Kunnskap** og velg **Legg til SharePoint**.
3.  Lim inn URL-en til SharePoint-mappen der du la Abacus-filene.
    * *Fordelen i virkelige prosjekter: Agenten vil automatisk kjenne til endringer hvis du oppdaterer dokumentene i mappen senere.*

---

### Steg 5: Begrens agentens informasjonskilder
For å unngå at agenten begynner å gjette eller henter generell informasjon fra internett, skal vi låse den til dine data.

1.  Finn innstillingen som heter **"Bruk bare angitte datakilder"**.
2.  **Slå denne PÅ.**
3.  Dette sikrer at agenten kun svarer basert på Abacus-dokumentasjonen du nettopp koblet til.

---

### Steg 6: Ferdigstill og test
1.  Klikk på knappen **"Opprett"** (eller Lagre).
2.  Gratulerer! Du har nå din egen "Prosjektstøtte"-agent.
3.  Prøv å stille den et spørsmål, for eksempel: *"Hva er de viktigste milepælene i Prosjekt Abacus de neste tre månedene?"*

---

### Tips til refleksjon:
* **Hvorfor SharePoint?** Ved å bruke SharePoint (Alternativ B) lever agenten sammen med prosjektet. Hvis prosjektplanen endres i SharePoint-mappen, vil agenten vite det umiddelbart uten at du må laste opp filer på nytt.
* **Sikkerhet:** Ved å slå på "Bruk bare angitte datakilder", lager du en trygg "sandkasse" hvor du vet nøyaktig hvilken informasjon KI-en bruker for å gi deg svar.
