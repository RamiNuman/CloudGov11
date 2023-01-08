# The Open Group - TOGAF 9.1

## Standaard / Framework:
The Open Group Architecture Framework (TOGAF) is een openstandaard die ontwikkeld is om een standaard te creeren voor het ontwikkelen en beheren van organisatie of enterprise architectuur. TOGAF bestaat uit best practices en richtlijnen voor het plannen, implementeren en het besturen van organisatiearchitectuur.

Een kernonderdeel van de Framework is de Architecture Developement Method (ADM). AMD beschrijft 4 verschillende fasen, genoemd domeinen, om de enterprise architectuur te ontwikkelen. Deze domeinen zijn:
1. Business architecture
2. Data architecture
3. Application architecture
4. Technology architecture

Alle componenten van TOGAF zijn:
- AMD
- Architecture Content Framework
- Reference Models
- AMD Guidelines & Techniques
- Enterprise Continuum
- Architecture Capability Framework

De 6 onderdelen worden in dit document kort uitgelegd

### The Architecture Developement Method
Een bewezen manier van het ontwikkelen van een architectuur. Ontwikkeld om business benodigdheden aan te pakken. AMD is een iteratieve methode en zorgt ervoor dat een complexe groep van benodigdheden zijn specifiek aangepakt

![TOGAF AMD](/img/togaf.png)
Elke iteratie is een nieuwe beslissing. Beslissingen ijn gebaseerd op:
- Bevoegheid / resource beschikbaarheid
- Waarde die toekomt aan de onderneming.

| **AMD Iteration**                 | **Detail**                                                                                                                                                                |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Preliminary                       | Prepare the organization for a successful architecture project                                                                                                            |
| Architecture vision               | Set the scope, constraints and expectations for a TOGAF project; create the Architecture Vision; validate the business context; create the Statement of Architecture Work |
| Business Architecture             | Develop Business Architecture, Develop baseline and target architectures and analyze the gaps                                                                             |
| Information Systems Architectures | Develop Information Systems Architectures Develop baseline and target architectures and analyze the gaps                                                                  |
| Technology Architecture           | Develop Technology Architecture Develop baseline and target architectures and analyze the gaps                                                                            |
| Opportunities and Solutions       | Perform initial implementation planning; identify major implementation projects                                                                                           |
| Migration Planning                | Analyze costs, benefits and risks; develop detailed Implementation and Migration Plan                                                                                     |
| Implementation Governance         | Provide architectural oversight for the implementation; ensure that the implementation project conforms to the architecture                                               |
| Architecture Change Management    | Provide continual monitoring and a change management process to ensure that the architecture responds to the needs of the enterprise                                      |
| Requirements Management           | Ensure that every stage of a TOGAF project is based on and validates business requirements                                                                                |

### Architectural Content Framework
Biedt een gedetaileerde model aan van architectonisch werkproducten. Dit houdt Deliverables, Artifacts en Architecture Building Blocks (ABBs) in. Helpt om een betere consistantie te brengen in de output van TOGAF. Biedt een uitgebreiden checklist van architectuur outputs. Bevordert betere integraties van werkproducten en als laatste biedt het een openstandaard voor hoe architecturen beschreven moeten worden.
![TOGAF ACF](/img/togaf2.png)

### Reference Models
Er zijn 2 modellen die gerefereerd worden:
- The TOGAG Technical Reference Model (TRM)
	- Foundation Architecture
	- Model and taxonomy of generic platform
- The Integrated Information Infrastructure Model (III-RM)
	- Model for business applications and infrastructure applications
	- Specifically aimed to support the vision of Boundaryless Information Flow

### AMD Guidelines and Techniques
Een set van richtlinen en technieken om de applicatie van AMD te ondersteunen. Het help om met meerdere scenario's om te gaan, inclusie verschillende process stylen. De techniek ondersteunt specifieke taken binnen de AMD, bijvoorbeeld principes definieren, business scenario's, gap analyse, migratieplannen en risk management

### Enterprise Continuum
De Enterprise Continuum bestaat uit meerdere onderdelen die uiteindelijk de architectuur context en benodigdheden vertaald naar een geimplementeerde solution binnnen een organisaties.

Architecture Context and Requirements zijn de basis requirements van een organisatie voor een architectuur. Deze kan beinvloed worden door externe factoren buiten de organisatie. Architecture Context wordt vervolgens vertaald naar een Architecture Continuum. Hierbij wordt er een specifieke Architectuur model geadopteerd voor gebruik. Architecture Continuum wordt ondersteund door Solutions Continuum via richtlijnen en ondersteuningen. Solution Continuum worden geinitieerd binnen een deployment naar een Deployed Solutions

![togaf EC](/img/togaf3.png)

### Architecture Capability Framework
Om een architectuurfunctie binnen een onderneming succesvol uit te voeren, is het noodzakelijk om de juiste organisatiestructuren, processen, rollen, verantwoordelijkheden en vaardigheden in te voeren om de architectuurcapaciteit te realiseren. Architecture Capability Framework biedt een reeks referentiematerialen voor het opzetten van een dergelijke architectuurfunctie. Lezers moeten er rekening mee houden dat hoewel dit deel een aantal richtlijnen bevat ter ondersteuning van kernactiviteiten, het Architecture Capability Framework in zijn huidige vorm niet bedoeld is als een uitgebreide sjabloon voor het uitvoeren van een Enterprise Architecture Capability

De verschillende gedefinieerde rollen binnen de Capability Framework zijn:
| Role             | Uitleg                                                                                                                                                                                                                                                                                             |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Board            | Versee the implementation of the strategy                                                                                                                                                                                                                                                          |
| Compliance       | Ensuring the compliance of individual projects with the Enterprise Architecture is an essential aspect of Architecture Governance                                                                                                                                                                  |
| Contracts        | The joint agreements between development partners and sponsors on the deliverables, quality, and fitness-for-purpose of an architecture                                                                                                                                                            |
| Governance       | The practice and orientation by which Enterprise Architectures and other architectures are managed and controlled at an enterprise-wide level.                                                                                                                                                     |
| Maturity Models  | Many organizations know that they need to improve their processes in order to successfully manage change, but don't know how. Maturity models address this problem by providing an effective and proven method for an organization to gradually gain control over and improve its change processes |
| Skills Framework | provide a view of the competency levels required for specific roles                                                                                                                                                                                                                                |

## Bijdragen van de framework
In Nederland wordt TOGAF framework door zowel overheidsorganisaties als in de prive sector veel gebruikt. Wereldwijd wordt de framework door 80% van de top 50 Globale bedrijven gebruikt en 60% door 500 Fortune Companies.

## Sterke en minder sterke punten
| Sterktes                            | Zwaktes                                           |
| ----------------------------------- | ------------------------------------------------- |
| Biedt stap voor stap aanpak         | Geen specifieke toepassing op Cloud governance    |
| Verbeterd gebruik van open systemen | Minder secuirty aspecten t.o.v. andere frameworks | 
| Reduceert risico's                  |                                                   |

## Framework betrokkenheid bij Public Cloud providers
TOGAF is een openstandaard en wordt gebruikt door veel organisatie. Hoewel Public Cloud providers hun eigen framework implementatie gebruiken, heeft TOGAF principes wel plaats kunnen vinden in hun implementaties. Voorbeeld van organisatie die gebruik maken van de TOGAF Framework zijn:
- IBM
- Oracle
- Cisco
- HP

## Bronnen
- [Online versie (RAW Source)](https://raw.githubusercontent.com/RamiNuman/CloudGov11/main/framework.md)
- [Youtube bron](https://www.youtube.com/watch?v=JB6XEGv_Z0M)
- [Wat is TOGAF](https://academy.capgemini.nl/thema/wat-is-togaf)
- [TOGAF intro documentatie](https://www.opengroup.org/public/member/proceedings/q312/togaf_intro_weisman.pdf)
- [Arichtecture Capability Framework](https://pubs.opengroup.org/architecture/togaf9-doc/m/chap39.html)
- [TOGAF certified organization](https://www.opengroup.org/public/member/proceedings/q412/certification_update.pdf)