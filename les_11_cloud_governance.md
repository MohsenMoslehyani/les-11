# Cloud Governance & Platform
## Microsoft Cloud Adoption Framework (CAF)

### Introductie
Cloud computing maakt het voor organisaties relatief eenvoudig om snel nieuwe IT‑diensten te ontwikkelen en te gebruiken. Een proof‑of‑concept is zo opgezet, een applicatie is snel uitgerold en teams kunnen vrijwel direct aan de slag. Maar zodra de cloud structureel wordt ingezet, ontstaan er nieuwe risico’s. Denk aan onverwachte kosten, onduidelijk eigenaarschap, beveiligingsproblemen of vragen van auditors en het management. Precies op dat punt komt **cloud governance** in beeld.

Cloud governance gaat niet over het afremmen van innovatie, maar over het creëren van duidelijke spelregels waarmee de cloud veilig, beheersbaar en voorspelbaar kan worden gebruikt. In deze opdracht staat het **Microsoft Cloud Adoption Framework (CAF)** centraal. Dit framework biedt een praktisch en gestructureerd model om cloud governance en platformbeheer in te richten, met name binnen Microsoft Azure.

---

### Wat is het Microsoft Cloud Adoption Framework?
Het Microsoft Cloud Adoption Framework is een verzameling richtlijnen, best practices, documentatie en tools die organisaties helpen bij het plannen, implementeren en beheren van cloudoplossingen. Het framework is niet alleen gericht op techniek, maar kijkt expliciet naar de combinatie van **business, mensen, processen en technologie**.

CAF beschrijft de volledige cloudreis van een organisatie: van strategie en planning tot migratie, innovatie en beheer. Governance vormt daarin een aparte, maar zeer belangrijke pijler. Zonder governance bestaat het risico dat cloudgebruik oncontroleerbaar wordt, wat kan leiden tot beveiligingsincidenten, complianceproblemen en hoge kosten.

---

### Governance binnen CAF
Binnen het Cloud Adoption Framework is governance geen losstaand document, maar een set van afspraken en controles die continu worden toegepast. Microsoft verdeelt governance grofweg in de volgende domeinen:

**Kostenbeheer**  
Cloudresources zijn flexibel, maar die flexibiliteit kan duur uitpakken. CAF adviseert het gebruik van budgetten, cost alerts, tagging en cost management tools om inzicht te houden in uitgaven.

**Beveiliging en identiteit**  
Identiteit wordt gezien als de nieuwe beveiligingsperimeter. CAF legt daarom veel nadruk op identity & access management (bijvoorbeeld Entra ID), least‑privilege toegang, multi‑factor authenticatie en security baselines.

**Compliance en risico’s**  
Het framework helpt organisaties om wet‑ en regelgeving (zoals AVG, ISO‑normen of NEN‑standaarden) te vertalen naar concrete cloudmaatregelen. Denk aan logging, auditing, dataclassificatie en bewaartermijnen.

**Resource‑consistentie**  
Door het gebruik van policies, templates en landing zones zorgt CAF ervoor dat cloudresources altijd volgens vaste standaarden worden uitgerold.

---

### Cloud platform en landing zones
Een belangrijk onderdeel van CAF is het concept van **Azure Landing Zones**. Een landing zone is de technische en organisatorische basis waarop workloads veilig kunnen landen.

Een landing zone bevat onder andere:
- Een vaste netwerkstructuur
- Identiteit en toegangsbeheer
- Logging en monitoring
- Beveiligingsinstellingen en policies

Door eerst het platform goed in te richten, wordt voorkomen dat elke applicatie ‘op zijn eigen manier’ wordt gebouwd. Dit maakt het beheer eenvoudiger en de omgeving beter schaalbaar.

---

### Governance versus management
Een belangrijk onderscheid binnen CAF is het verschil tussen governance en management. Governance gaat over **kaders en richtlijnen**: wat mag wel, wat mag niet en onder welke voorwaarden. Management gaat over de **dagelijkse uitvoering**, zoals incidentafhandeling, monitoring en onderhoud.

CAF combineert deze twee werelden. Governance bepaalt de spelregels, terwijl managementprocessen (bijvoorbeeld ITIL‑processen) zorgen voor de dagelijkse operatie. Dit sluit goed aan bij moderne cloudomgevingen waarin DevOps en platformteams samenwerken.

---

### Sterke punten van het Cloud Adoption Framework
Een groot voordeel van CAF is de praktische insteek. Het framework is geen theoretisch model, maar biedt concrete handvatten, templates en voorbeelden. Daarnaast sluit het goed aan op bestaande frameworks zoals ITIL, COBIT en ISO‑normen.

Andere sterke punten zijn:
- Duidelijke focus op zowel business als IT
- Goede ondersteuning voor governance en compliance
- Sterke integratie met Azure‑diensten
- Geschikt voor zowel kleine als grote organisaties

---

### Zwakke punten en beperkingen
Hoewel CAF zeer compleet is, kent het ook beperkingen. Het framework is sterk gericht op Microsoft Azure. Voor organisaties die multi‑cloud of cloud‑agnostisch willen werken, is aanvullende afstemming nodig.

Daarnaast kan CAF in het begin complex aanvoelen. Zonder duidelijke prioriteiten bestaat het risico dat governance te zwaar of bureaucratisch wordt. Het is daarom belangrijk om governance stapsgewijs in te voeren.

---

### Conformiteit met cloudproviders
Microsoft Azure is vanzelfsprekend volledig afgestemd op het Cloud Adoption Framework. Veel onderdelen van CAF worden ondersteund door native Azure‑diensten zoals Azure Policy, Defender for Cloud en Cost Management.

Andere cloudproviders, zoals AWS en Google Cloud, hebben vergelijkbare frameworks (bijvoorbeeld het AWS Cloud Adoption Framework). De principes van governance zijn grotendeels gelijk, maar de tooling verschilt per platform.

---

### Conclusie
Het Microsoft Cloud Adoption Framework biedt een solide en praktisch fundament voor cloud governance en platformbeheer. Door duidelijke kaders te stellen op het gebied van kosten, beveiliging, compliance en standaardisatie, helpt CAF organisaties om controle te houden zonder innovatie te blokkeren.

Voor organisaties die Azure gebruiken, is CAF een logische keuze. Het framework laat zien dat cloud governance geen rem is, maar juist een versneller voor veilige en duurzame digitale transformatie.

---

### Bronnen
- Microsoft Cloud Adoption Framework documentatie  (https://learn.microsoft.com/nl-nl/azure/cloud-adoption-framework/overview)
- Microsoft Learn – Cloud Governance  
- College slides Les 11 – Cloud Governance Frameworks

