# Projektplan – The IT-Girly's Guide to University

## Idéen fra start

Projektet tog udgangspunkt i en idé om at skabe en hjemmeside målrettet nye og
kommende kvindelige IT-studerende på AAU. Målet var at skabe en hjemmeside der både var visuelt indbydende og indholdsrig,
så den kunne fungere som en reel ressource for målgruppen.

---

## Proces og arbejdsmetode

### Scrum og agil udvikling

Vi valgte at arbejde efter en agil tilgang inspireret af Scrum. Det betyder at vi
opdelte projektet i kortere arbejdsperioder, hvor vi fokuserede på
afgrænsede dele af projektet ad gangen.

Vi oprettede et Scrum Board i GitHub Projects, hvor vi nedbrød projektet i konkrete
opgaver. Hver opgave blev tildelt et gruppemedlem under Assignees, så der
var fuld transparens om hvem der lavede hvad. Opgaverne blev flyttet fra Backlog →
In Progress → Done efterhånden som arbejdet skred frem.

### Roadmap

Vi anvendte GitHub Projects' Roadmap-funktion til at lægge en overordnet tidslinje
for projektet. Roadmappet gav os overblik over hvornår de forskellige faser skulle
være færdige, og fungerede som styringsredskab undervejs.

Vi har i store træk holdt vores tidslinje, men har løbende tilpasset den, da nogle
dele af designfasen og læringsprocessen af GitHub tog længere tid end forventet.

---

## Faser i projektet

### Planlægning og design

Vi startede med at definere projektets formål, målgruppe og indhold. Derefter gik
vi i gang med den visuelle identitet:

- Vi udarbejdede moodboards med referencer til den æstetik vi ønskede – en blanding
  af tech og feminin "IT-Girl" vibe med lilla, pink og navy som primærfarver
- Vi lavede wireframes og mockups i Figma for alle 8 sider, så vi havde et klart
  billede af layoutet inden kodningen begyndte
- Vi fastlagde sidens struktur: hvilke 8 sider der skulle være, hvad de skulle
  indeholde. 

### Dokumentation og UML

Inden kodningen udarbejdede vi den tekniske dokumentation:

- Projektbeskrivelse, rollebeskrivelser og roadmap blev skrevet i Markdown og
  gemt i documentation-mappen i GitHub
- Vi tegnede et Use Case Diagram der viser brugerens interaktioner med systemet
- Vi tegnede et Sequence Diagram der viser flowet når en bruger navigerer mellem
  siderne

### Kodning

Med design og dokumentation på plads gik vi i gang med selve kodningen. Vi fulgte
princippet om HTML først, CSS bagefter:

- Vi startede med at kode HTML-skelettet for forsiden (index.html) med hjælp af AI værktøj, da vi er nybegyndere i kode. Herefter uploadede vi det til main-branchen
- CSS blev struktureret i to filer: global.css til layout og struktur, og theme.css
  til farver og visuel identitet

### Tilpasning og finjustering

Efter at alle sider var kodet gennemgik vi hjemmesiden samlet og foretog
tilpasninger:

- Billeder blev indsat på forsiden
- Tekster blev tilrettet så de passede til sidens tone og målgruppe
- Vi testede navigationen på tværs af alle sider

### Retrospective og aflevering

Afslutningsvis skrev vi et retrospective hvor vi reflekterede over processen:
hvad gik godt, hvad kunne have været gjort anderledes, og hvad vi lærte undervejs.
Herefter foretog vi de sidste finjusteringer og klargjorde projektet til aflevering.

---

## Mappestruktur i GitHub

Projektet er organiseret i følgende mappestruktur i GitHub-repositoryet:

    M6-Projekt/
    ├── css/
    │   ├── global.css        ← Layout, navigation, grid og knapper
    │   └── theme.css         ← Farver, typografi og visuel identitet
    ├── documentation/
    │   ├── projektbeskrivelse.md
    │   ├── roller.md
    │   ├── projektplan.md
    │   ├── roadmap.md
    │   ├── retrospective.md
    │   ├── UML-diagrammer.md
    │   ├── use-case-diagram.svg
    │   └── sequence-diagram.svg
    ├── images/               ← Alle billeder brugt på siden og illustration af UML-diagrammer
    ├── index.html            ← Forside
    ├── educations.html
    ├── study-tips.html
    ├── exams.html
    ├── balance.html
    ├── social-life.html
    ├── economy.html
    └── information.html

Strukturen sikrer at alle gruppemedlemmer kan arbejde parallelt med så få
konflikter som muligt – HTML-filerne er adskilt, CSS-filerne deles og
dokumentationen ligger samlet i én mappe.
