---
type: meta
title: "Log"
updated: 2026-05-01
---

# Log d'operacions

Registre cronològic de tots els canvis a la wiki. Append-only — noves entrades a dalt.

---

## 2026-05-02 — Ingest PAU 2022 setembre

**Fonts:** `.raw/examens-pau/Enunciat 2022 septembre.pdf` + `Solucio 2022 septembre.pdf`

**Creat:**
- [[PAU 2022 setembre]] — pàgina d'examen completa (10 pts, totes les opcions A/B + part comuna, totes les respostes del solucionari)
- [[src-pau-2022-setembre]] — pàgina de font

**Actualitzat:**
- [[examens/_index]] — afegit PAU 2022 setembre + patrons recurrents inicials

**Lectures obligatòries identificades:** *La plaça del Diamant* (Rodoreda) + *Aigües encantades* (Puig i Ferreter) — wikilinks pendents de crear.

---

## 2026-05-01 — Lint: health check post-tanda-4

Reporte: [[lint-report-2026-05-01]] (`wiki/meta/`).

**Estat global:** 121 pàgines, 155 wikilinks únics, **0 orfes**, 31 issues (cap crítica).

**Issues per categoria:**
- 6 dead links per mismatch de filename (diacrítics): `Ausiàs Marc` vs `Ausiàs March`, `Francesc Vicenç Garcia` vs `Francesc Vicent Garcia`, `Josep M. Benet i Jornet` (amb punts), `Maria Mercè Marçal` vs `Maria-Merce Marcal`, `Miquel Martí i Pol`, `Famílies linguístiques` (fitxer amb error: `Familias linguistiques.md`).
- 4 backslash artifacts en taules: `Angel Guimera\`, `Guerra-i-Postguerra\`, `Renaixenca\`, `Santiago Rusinol\`.
- 19 path-style wikilinks inconsistents (`[[autors/_index]]`, `[[sources/src-*]]`).
- ~9 pàgines referenciades sense fitxer: ⭐ `[[La plaça del Diamant]]`, `[[Tirant lo Blanc]]`, `[[Solitud]]`, `[[Jocs Florals]]`, `[[Oda a la pàtria]]`, `[[Gabriel Ferrater]]`, `[[Joan Vinyoli]]`, `[[Marius Torres]]`, `[[Jordi de Sant Jordi]]`.
- 2 placeholders d'agent: `[[Obra 1]]`, `[[Obra 2]]`.
- Frontmatter gaps a meta-pàgines i 5 src-* de tanda 1 (camps `created`/`updated`).

**Auto-fix:** cap aplicat. Esperant decisió de l'usuari (sessió tancada).

---

## 2026-05-01 — Ingest: Tema 3 Morfologia (temari general, 19 pàg.)

Font ingerida: `.raw/temari/general/Tema 3 Morfologia .pdf` (19 pàgines, editorial Cruïlla, temari 2n Batx).

**Pàgina enriquida:**
- ⭐ [[Morfologia]] (`wiki/gramatica/`) — `status` pujat a `mature`. Integra ara el dossier UAB Idiomes (Unitats 4–6) + Tema 3. Contingut nou afegit: taula de categories gramaticals (8 categories + sintagmes); gènere substantiu complet (canvis consonàntics/vocals/accentuació, sufixos, heterònims, invariables, gèneres dobles amb significat diferent: *el llum/la llum, el fi/la fi, el pols/la pols, el son/la son, la terra/el terra*…); llista masculins/femenins difícils; nombre (doble plural *-sc/-st/-xt/-ig*, invariables); adjectiu (graus amb irregulars, classificadors vs. valoratius); determinants complerts (demostratius, possessius tònics+àtons, numerals amb abreviatures, quantitatius PAU *molt/gaire/bastant/prou/massa/força*, indefinits, funció pronominal); pronoms tònics + interrogatius; adverbis (manera, temps, lloc, quantitat, afirmació/dubte/negació, modalitzadors; remarques PAU: *inclús→fins, igual→potser, potser/pot ser, molt/gaire, bastant/prou, gens/res, gairebé/gaire bé*); preposicions febles (usos PAU: per/per a; CD/CI; CRV; expressions de lloc i temps); preposicions fortes simples i compostes; locucions prepositives; remarques PAU preposicions (*degut a, com a, quant a, a mitjan, tocant a, amb relació a/en relació amb*); conjuncions (taula); interjecció; formació de mots (derivació, composició, parasíntesi, abreviacions, neologismes); taula d'errors PAU ampliada.

**Font creada:**
- [[src-tema-3-morfologia]] (`wiki/sources/`) — font overwritten (stub → complet)

**Index actualitzat:**
- [[gramatica/_index]] — entrada de Morfologia ampliada

---

## 2026-05-01 — Ingest: Dossier Morfologia i Sintaxi UAB (dossier mestre)

Fonts ingerides:
- `.raw/temari/general/dossier-morfologia-i-sintaxi.pdf` (56 pàg., UAB Idiomes)
- `.raw/temari/general/Solucionari morfologia i sintaxi.pdf` (solucionari complet)

**Pàgines creades:**
- [[src-dossier-morfo-sintaxi]] (`wiki/sources/`) — resum de les 9 unitats del dossier + diferencial respecte als agents paral·lels
- [[Preposicions i conjuncions]] (`wiki/gramatica/`) — per/per a, fins/fins a, cap/cap a; canvi/caiguda de preposició; com/com a; si no/sinó; perquè/per què/per a què/doncs; 20 errors PAU; exercicis resolts
- [[Morfologia]] (`wiki/gramatica/`) — gènere del nom (5 marques de femení; heterònims; noms de doble gènere); plurals (Model I/II; invariables; doble forma); morfologia de l'adjectiu (dues terminacions Model I/II; una terminació; doble plural masc.); quantitatius i indefinits
- [[Ser i estar]] (`wiki/gramatica/`) — taula completa (localització/qualitats/temps/locució prep.); haver-hi; adjectius de doble possibilitat; exercicis resolts del solucionari UAB

**Pàgines enriquides:**
- [[Els verbs]] — afegit § 14 "Dossier UAB": velarització (esquema complet + cadena de temps); participis resolts del solucionari (17 exemples); gerundi correcte/incorrecte (8 exemples); perífrasis d'obligació/probabilitat (5 correccions)
- [[Oracions de relatiu]] — afegit § 6 "Dossier UAB": exercicis resolts adjectives/substantives/neutres (20+ exemples del solucionari); advertència *lo que*; errors de pleonasme resolts
- [[Pronoms febles]] — afegit §§ 6–7: metodologia sistemàtica UAB (CD det./indet./neutre → el/en/ho; CI sing./pl. → li/els; combinació CI+CD amb regla l'hi); atribut *estar/semblar* sempre *ho*; atribut emfàtic *en*; predicatiu *hi*; 18 exemples resolts del solucionari
- [[Funcions sintactiques]] — afegit § "Diferenciació CD/CI": mètode passiva + pronominalització; cas CD amb *a*; 6 exercicis resolts CD/CI i 5 de canvi/caiguda de preposició del solucionari
- [[gramatica/_index]] — afegides entrades per [[Morfologia]], [[Preposicions i conjuncions]], [[Ser i estar]]; enriquides entrades [[Pronoms febles]] i [[Els verbs]]

**Callouts `[!example]` amb solucions del solucionari afegits a:**
- [[Preposicions i conjuncions]] — 7+5+2+6+5+7+... exercicis resolts (per/per a, fins, cap, canvi/caiguda, com/com a, si no/sinó, perquè/per què)
- [[Morfologia]] — 7 noms de gènere difícil resolts
- [[Ser i estar]] — 10+ exercicis de localització i qualitats resolts
- [[Els verbs]] — 17 participis + 8 gerundis + 5 perífrasis resolts
- [[Oracions de relatiu]] — 20+ exercicis de pronoms relatius i pleonasmes resolts
- [[Pronoms febles]] — 18 combinacions de pronoms febles resoltes
- [[Funcions sintactiques]] — 11 exercicis CD/CI i canvi/caiguda de preposició resolts

---

## 2026-05-01 — Ingest: Sintaxi Presentació Batx 2n (tipologia d'oracions)

Font ingerida: `.raw/temari/general/Sintaxi Presentació Batx 2n.pdf` (33 diapositives, GIEC 2018).

**Pàgines creades:**
- [[src-sintaxi-presentacio]] (`wiki/sources/`) — presentació de classe sobre tipologia d'oracions
- [[Sintaxi - oracions]] (`wiki/gramatica/`) — oració simple/composta; coordinada (6 classes + taula connectors + *sinó* vs *si no*); juxtaposada; subordinada substantiva (4 classes + 7 funcions); subordinada de relatiu (taula pronoms relatius GIEC, especificativa/explicativa, sense antecedent); subordinada adverbial (9 subtipus + connectors); taula funcions pronoms relatius amb antecedent

**Pàgines enriquides:**
- [[Funcions sintactiques]] — nova secció "Els sintagmes: nucli i complements" (SN/SV/SAdj/SAdv/SP + callout tip); nova secció "Subordinades que fan funcions nominals" (taula subjecte/CD/CRV/CN + callout PAU elisions davant *que*); actualitzada taula pronominalitzacions (afegit *ho* per a subordinada substantiva); actualitzats "Vegeu també" amb wikilinks a [[Oracions de relatiu]] i [[Oracions adverbials]]
- [[gramatica/_index]] — afegit bloc "Sintaxi — Tipologia d'oracions" amb [[Sintaxi - oracions]]; actualitzada descripció [[Funcions sintactiques]]

---

## 2026-05-01 — Ingest: Oracions adverbials (teoria + exercicis)

Fonts ingerides:
- `.raw/temari/general/Oracions adverbials-2.pdf` (~95 KB, 12 diapositives, teoria completa)
- `.raw/temari/general/Exercicis Oració adverbial.pdf` (~39 KB, Fitxa 7, 8 exercicis)

**Pàgines creades:**
- [[Oracions adverbials]] (`wiki/gramatica/`, `status: mature`) — tipologia completa, connectors per tipus, errors PAU, exercicis resolts
- [[src-oracions-adverbials]] (`wiki/sources/`) — font doble (teoria + exercicis)

**Pàgines actualitzades:**
- [[gramatica/_index]] — nova secció *Sintaxi — Oracions subordinades* amb entrada
- [[index]] — entrada a *Gramàtica — Notes* i a *Fonts*

**Cross-links establerts:** [[Correlacions verbals]] (condicionals), [[Funcions sintactiques]] (CC), [[Sintaxi - oracions]] (pendent), [[Els verbs]] (pendent), [[Banc preguntes PAU]]

---

## 2026-05-01 — Ingest: Els verbs (temari general, 14 pàgines)

Font ingerida: `.raw/temari/general/Els verbs.pdf` (14 pàgines, 2 capítols: morfologia verbal + sintaxi verbal).

**Pàgines creades:**
- [[src-els-verbs]] (`wiki/sources/`) — font del temari verbal complet
- [[Els verbs]] (`wiki/gramatica/`, status: mature) — conjugacions (1a/2a/3a), irregularitats (ortogràfiques/eufòniques/lexemàtiques), participis i gerundis irregulars (~50), formes no personals, perífrasis verbals (aspecte + modals), correlacions de temps, *ser/estar*, verbs pronominals, doblets, errors PAU

**Pàgines actualitzades:**
- [[Correlacions verbals]] — hook substituït per wikilink real a [[Els verbs]]
- [[gramatica/_index]] — nova secció "Morfologia — Verbs"
- [[index]] — [[Els verbs]] afegit a "Gramàtica — Notes"

---

## 2026-05-01 — Ingest: Oracions de relatiu 2 (presentació)

Font ingerida: `.raw/temari/general/Oracions de relatiu 2.pdf` (12 diapositives, presentació visual temari).

**Pàgines creades:**
- [[src-oracions-relatiu]] (`wiki/sources/`) — font del temari d'oracions subordinades adjectives
- [[Oracions de relatiu]] (`wiki/gramatica/`, status: mature) — pronoms relatius, especificatives vs. explicatives, formes incorrectes, errors PAU

**Pàgines actualitzades:**
- [[gramatica/_index]] — nova secció "Sintaxi — Oracions subordinades"

---

## 2026-05-01 — Ingest: Pronoms febles — teoria (Nivell D, Castellnou)

Font ingerida: `.raw/temari/general/Pronoms febles teoria (1)-2.pdf` (5 pàgines, format visual, *Nivell D*, ed. Castellnou).

**Pàgines creades:**
- [[src-pronoms-febles]] (`wiki/sources/`) — font processada, taula completa de substitucions per funció
- ⭐ [[Pronoms febles]] (`wiki/gramatica/`) — pàgina madura: quadre complet (18 funcions × pronom), combinacions binàries (l'hi / la hi / els hi / les hi / li'n / li-ho), posició proclisi/enclisi, formes plena/reforçada/elidida, errors típics PAU

**Pàgines actualitzades:**
- [[gramatica/_index]] — nova secció "Morfologia — Pronoms" amb entrada a [[Pronoms febles]]
- [[index]] — entrada nova a "Gramàtica — Notes"

**Cross-links establerts:**
- [[Funcions sintactiques]] ja tenia taula de pronominalitzacions → ara apunta a [[Pronoms febles]] (les entrades "pendent" ja estaven redactades com a links)

---

## 2026-05-01 — Enriquiment: La narrativa — teoria (Sullà, UOC)

Font ingerida: `.raw/temari/literatura/Narrativa Enric sullà.pdf` (50 pàgines, PID_00156094, UOC).

**Pàgines creades:**
- [[src-narrativa-sulla]] (`wiki/sources/`) — manual universitari de narratologia sistemàtica (Genette, Tomashevskij)

**Pàgines enriquides:**
- ⭐ [[La narrativa - teoria]] — `status` pujat a `mature`. Noves seccions afegides (al final del fitxer, sense reescriure el que ja hi havia):
  - **Temps — subtipus d'analepsi/prolepsi** (externa/interna) amb taula i exemples catalans: [[Mirall trencat]] pàg. 179 (prolepsi interna), "Tres sorores" (Espriu, analepsi), *Solitud* (V. Català)
  - **Temps — durada** (escena/el·lipsi/resum/pausa) amb fórmules Tn/Th i exemples: *La plaça del Diamant*, *Josafat*
  - **Temps — freqüència** (singulativa/iterativa/repetitiva) amb indicadors verbals (pretèrit/imperfet) i exemples: Espriu, Cabré
  - **Narrador — tipologia 2×2 de Sullà** (hetero/homodiegètic × extra/intradiegètic): taula dels 4 tipus amb exemples catalans; nota PAU sobre estatus extrahomodiegètic de Natàlia/Colometa
  - **Narratari** extradiegètic i intradiegètic amb exemples (*Bearn*, Conrad)
  - **Focalització** (interna fixa/variable, externa): taula + cita canònica de Genette
  - **Caracterització del personatge** — 5 eixos de Sullà (aspecte extern, caràcter, posició social, accions, relació)

---

## 2026-05-01 — Enriquiment: El teatre — teoria (Teatre.pdf)

Font ingerida: `.raw/temari/literatura/Teatre.pdf` (~363 KB, pàg. 40–48).

**Pàgina principal actualitzada:**
- ⭐ [[El teatre - teoria]] — de `developing` a `mature`. Seccions afegides:
  - § 3.2: text principal / secundari (Roman Ingarden); contingut detallat d'acotacions.
  - § 3.3: plantejament/nus/desenllaç amb detall de clímax; tècnica de les darreres escenes.
  - § 3.4: anagnòrisi / descobriment; personatges dinàmics; rols oposats; funcions del cor.
  - § 3.5 NOU: Modes d'expressió — diàleg + monòleg (líric, tècnic, reflexiu, apart) + soliloqui.
  - § 3.6 NOU: Classificació completa dels gèneres (teatre culte + popular profà + popular religiós); subgèneres de comèdia i drama; entremès vs. sainet (taula); farsa; misteri/miracle/moralitat.
  - Taula del teatre català amb Soler, Guimerà, Rusiñol, Sagarra, Espriu, Brossa, Benet i Jornet, Belbel.
  - Callout tip per al comentari de text + cross-link a [[Figures retoriques]].

**Pàgines d'autors actualitzades:**
- [[Angel Guimera]] — obres amb dates/gèneres; exemples de monòleg i acotacions.
- [[Josep Maria de Sagarra]] — *El cafè de la Marina* (1933); característica del diàleg col·loquial.
- [[Salvador Espriu]] — *Antígona* (1955) classificada com a tragèdia; mite de Sinera.

**Pàgines noves:**
- [[Frederic Soler]] (`wiki/autors/`) — dramaturg Renaixença, sainet, «Pitarra».
- [[Josep M Benet i Jornet]] (`wiki/autors/`) — *El manuscrit d'Ali Bei* (1985), *Fugaç* (1994).
- [[src-teatre-pdf]] (`wiki/sources/`) — font registrada.

**Índex actualitzat:**
- [[autors/_index]] — afegits [[Frederic Soler]] i [[Josep M Benet i Jornet]].

---

## 2026-05-01 — Enriquiment: La narrativa — teoria (El text narratiu.pdf)

Font ingerida: `.raw/temari/literatura/El text narratiu.pdf` (~605 KB, manual didàctic, cap. 2, pàg. 25–39).

**Pàgines creades:**
- [[src-text-narratiu-pdf]] (`wiki/sources/`) — índex d'obres citades + continguts del manual

**Pàgines enriquides:**
- ⭐ [[La narrativa - teoria]] — enriquit amb seccions i exemples didàctics del PDF:
  - **Novel·la vs conte**: framing didàctic (precedents *fabliaux*, lais)
  - **Línies narratives**: exemples concrets (Rusiñol, Montserrat Roig, Boccaccio)
  - **Temps narratiu**: taula d'exemples (Pedrolo, Jordi Coca, Dumas, Joyce)
  - **Retrospecció/Prolepsi**: exemples literaris (Oller, Torrent)
  - **Ritme narratiu**: el·lipsi, exemples (*Tirant lo Blanc*); temps simultani (Pedrolo, Cabré); temps de lectura (*1984*)
  - **L'espai**: topònims reals/ficticis, espai protector vs opressor, dimensions (exterior/interior, etc.); exemples (*La plaça del Diamant*, Saramago, *Josafat*)
  - **Personatges**: Forster (plan/rodó), exemples (Colometa, l'Alba); presentació directa/mixta/indirecta detallada
  - **Narrador**: narratari explícit (*Bearn*, Villalonga); punt de vista variable
  - **Gèneres (per tema)**: taula completa amb definicions i obres catalanes + universals
  - **Gèneres (per forma)**: epistolar i polièdrica amb exemples
  - **Tipus d'expressió**: taula de trets lingüístics per narració/descripció/diàleg
  - **Evolució històrica**: Antiguitat → s. XX (esquema complet)
  - **Cross-links**: [[Tipologies textuals]], [[Mirall trencat]], [[src-text-narratiu-pdf]]

---

## 2026-05-01 — Enriquiment: La poesia — teoria i mètrica (Poesia.pdf)

Font ingerida: `.raw/temari/literatura/Poesia.pdf` (~813 KB, 18 pàgines, manual de poesia).

**Pàgines creades:**
- [[src-poesia-pdf]] (`wiki/sources/`) — font amb llista completa d'autors i obres citats

**Pàgines enriquides:**
- ⭐ [[La poesia - teoria metrica]] — `status` pujat a `mature`. Seccions afegides o molt ampliades:
  - **Definició** — cites de Joan Brossa, Carles Riba, Pere Verdaguer; Miquel Martí i Pol
  - **Característiques generals** — interiorització, brevetat i concentració, manca d'història, instantaneïtat, versificació
  - **Cesura** — detall decasíl·lab clàssic (4+6), decasíl·lab èpic (6+4), 5+5; alexandrí trimembre (4+4+4)
  - **Versos en forma de salt de falla** — descripció + exemple Martí i Pol
  - **Rima** — convenció de lletres (majúscules/minúscules), nota sobre combinació de rimes en un mateix poema
  - **Apariat** — variants noves rimades i codolada
  - **Sextet/Sexteta** — esquema ABAD+CC i variant **sextina**
  - **Octava** — cobla/octava clàssica (4 esquemes) i octava reial
  - **Dècima** — esquema abba:cddc (espinela)
  - **Sonet** — rol dels quartets (situació) vs tercets (conclusió)
  - **Mètrica accentual** — mètode d'anàlisi per peus mètrics, estrofa sàfica (Costa i Llobera), dístic elegíac (Carles Riba)
  - **El tema** — sintagma nominal, temes recurrents en 6 categories amb exemples
  - **El to** — taula: greu, festiu, melanconiós, humorístic
  - **La veu poètica** — anàlisi detallada del poema «La més alta» de Carner
  - **Gèneres** — descripcions ampliades (cançó → cobles, elegia → plany, epigrama → sàtira, epitalami: Carner i Salvat-Papasseit)
  - **Prosa poètica** — definició + exemple Rodoreda *Viatges i flors*
  - **Poema en prosa** — Baudelaire, J.V. Foix (*Darrer comunicat*), Joan Perucho
  - **Cal·ligrama** — Salvat-Papasseit *Ossa Menor* (1925) i *L'irradiador* (1921)
  - **Poema visual** — Joan Brossa «Camisa» (*La clau a la boca*, 1996)
  - **Acròstic** — Francesc Vicent Garcia «En forma de laberint» (*La Armonía del Parnás*, 1703)

---

## 2026-05-01 — Ingesta: Figures retòriques (PDF, 1r Batx)

Font ingerida: `.raw/temari/general/Figures retòriques 1r batx .pdf` (5 pàgines).

**Pàgines creades:**
- ⭐ [[Figures retoriques]] (`wiki/tecniques/`) — 20 figures en 4 categories (fòniques, sintàctiques, semàntiques, lògiques), amb definició, exemple poètic d'autor català i efecte expressiu. Inclou taula resum i nota sobre confusions freqüents PAU.
- [[src-figures-retoriques]] (`wiki/sources/`)

**Pàgines actualitzades:**
- [[La poesia - teoria metrica]] — afegit cross-link i nota cap a [[Figures retoriques]]
- [[Banc preguntes PAU]] — afegit callout tip cap a [[Figures retoriques]] a la secció de figures
- [[tecniques/_index]] — nova secció "Recursos retòrics"
- `wiki/index.md` — entrada a "Tècniques"

---

## 2026-05-01 — Ingesta: Taula de funcions sintàctiques (PDF)

Ingerit `.raw/temari/general/Taula-funcions-sintactiques-PDF.pdf` (2 pàgines, recurs "Parlem d'escriure en català").

**Pàgines creades:**
- ⭐ [[Funcions sintactiques]] (`wiki/gramatica/`) — pàgina de referència completa: 10 funcions (subjecte, CD, CI, CRV, CC amb 8 subtipus, C.pred., atribut, CN, C.adj., C.adv.), taula resum, proves d'identificació, exemples, taula de pronominalitzacions. Wikilinks cap a [[Pronoms febles]] i [[Sintaxi - oracions]] (pendents tanda 4).
- [[src-funcions-sintactiques]] (`wiki/sources/`)

**Pàgines actualitzades:**
- [[gramatica/_index]] — nova secció "Sintaxi — Funcions sintàctiques"
- `wiki/index.md` — afegida entrada a "Gramàtica — Notes" i a "Fonts"

---

## 2026-05-01 — Enriquiment: Tipologies textuals (PDF)

- **Font ingerida:** `.raw/temari/general/Tipologies textuals.pdf` (Departament de Llengua Catalana, 11 pàg.)
- **Nova font:** [[src-tipologies-textuals-pdf]]
- **Pàgina enriquida:** [[Tipologies textuals]] — afegits per cada tipologia:
  - **Explicatiu:** distinció científic vs divulgatiu; adjectius classificatius/especificatius vs valoratius; mitjans visuals escrits vs orals.
  - **Argumentatiu:** gèneres (assaig, editorial, article d'opinió, sermó, queixa); oració negativa per rebatre; nexes ordinals i classificatius.
  - **Descriptiu:** subtipus **caricatura** (nou); oracions atributives (*ser, estar, semblar, tenir, posseir, portar*); adverbis espacials.
  - **Narratiu:** gèneres complets (novel·la, conte, relat, llegenda, memòries, dietaris, biografies, poesia); perfet anterior i indefinit.
  - **Predictiu:** redefinit com a variant explicativa; gèneres concrets (meteorologia, avenços científics, descripció de viatge).
  - **Instructiu:** definició ampliada (dirigir, exhortar, aconsellar); gèneres (receptes, prospectes, instruccions treball); detall estructural (presentació inclou material + objectiu; procediment amb títols/subtítols); puntuació com a delimitadora.

---

## 2026-05-01 — Ingest: Fonètica — Canvis fonètics (4 PDFs)

- **Fonts ingerides:** 4 PDFs del temari general (`.raw/temari/general/`): canvis de mode, canvis de punt, ensordiment/sonorització, emmudiment/sensibilització/geminació
- **Pàgina creada:** [[Fonetica - canvis fonetics]] — pàgina consolidada amb 4 seccions, taules i exemples de cada fenomen
- **Font creada:** [[sources/src-fonetica-canvis]]
- **Actualitzades:** [[gramatica/_index]], [[index]]

---

## 2026-05-01 — Ingest: Correlacions verbals (el condicional)

- **Font ingerida:** `.raw/temari/general/Correlacions verbals_ el condicional - Documentos de Google.pdf`
- **Nova pàgina:** [[Correlacions verbals]] — regles, taula de correlacions, errors normatius PAU (doble subjuntiu, `*si tindria`)
- **Nova font:** [[src-correlacions-verbals]]
- **Actualitzats:** [[gramatica/_index]], [[index]]
- **Hook pendent:** enllaçar *Els verbs.pdf* (tanda 4) quan s'ingesti

---

## 2026-05-01 — Tancament de sessió

- MCP `obsidian-vault` reconfigurat a port 27124 amb la nova API key. Pendent reinici de Claude Code per activar.
- Hot cache i log actualitzats per recuperar context fàcilment a la propera sessió.

## 2026-05-01 — Enriquiment de pàgines de moviments existents

Actualitzades amb la informació detallada del temari (que abans només estava al `src-temari-2batx-md`):

- [[Renaixenca]] — afegit Memorial de Greuges, Decrets de Nova Planta, Jocs Florals com a context, [[Pompeu Fabra]]
- [[Realisme-i-Naturalisme]] — context positivista, anàlisi psicològica, distinció Naturalisme/Realisme
- [[Modernisme]] — influències detallades (simbolisme, decadentisme, esteticisme), "art per l'art", crisi existencial
- [[Noucentisme]] — Mancomunitat, IEC, Biblioteca de Catalunya, [[Pompeu Fabra]] com a referència
- [[Avantguardes]] — taula amb futurisme/dadaisme/expressionisme/surrealisme
- [[Guerra-i-Postguerra]] — tres camins (exili, resistència, silenci), enllaç a [[Mirall trencat]]
- [[Anys-60-80]] — Nova Cançó com a eina cultural

**Nova pàgina:** [[Pompeu Fabra]] (stub) — figura clau de la normalització lingüística que es referenciava de múltiples pàgines.

Status passat de `developing` a `mature` per a aquestes 7 pàgines de moviments.

## 2026-05-01 — Ingesta del temari complet (Markdown 2 Batx)

Ingerit `.raw/temari/general/Copia de Català 2Batx.md` (2.332 línies, ~164 KB).

**Pàgines noves:**
- ⭐ [[Mirall trencat]] — anàlisi completa de la lectura obligatòria (`wiki/obres/`)
- [[Sociolinguistica - conceptes basics]], [[Familias linguistiques]], [[Història de la llengua catalana]] (`wiki/sintesi/`)
- [[Variants dialectals]], [[Tipologies textuals]] (`wiki/gramatica/`)
- [[La narrativa - teoria]], [[La poesia - teoria metrica]], [[El teatre - teoria]] (`wiki/tecniques/`)
- [[Topics literaris]] (`wiki/sintesi/`)
- [[Banc preguntes PAU]] (`wiki/examens/`)
- [[src-temari-2batx-md]] (`wiki/sources/`)

**Pàgines actualitzades:**
- [[Merce Rodoreda]] de stub a developing (biografia, exili, estil)
- `_index.md` de gramatica, tecniques, sintesi, examens, obres
- `index.md` mestre

**Funcions clau detectades:**
- *Mirall trencat* és **lectura obligatòria** de la PAU (750 línies del temari dedicades).
- *La plaça del Diamant* apareix també com a referència recurrent.
- Els 17 moviments literaris ja estaven al wiki (de la tanda 1) i el temari els confirma.

## 2026-05-01 — Tanda 1 ingerida (literatura: panoràmica)

Ingerits 4 PDFs de `.raw/temari/literatura/`:
- `Autors des del s.XII fins el segle XVIII.pdf`
- `Moviments catalans s.XII-XVIII.pdf`
- `Autors des del s. XIX-XXI.pdf`
- `Moviments literaris catalans des de S.XIX.pdf`

**Pàgines creades:**
- 4 fonts a `wiki/sources/`
- **17 moviments** a `wiki/literatura/` (Trobadorisme → Postmodernitat)
- **45 autors** a `wiki/autors/` (de Guillem de Berguedà s. XII a Jaume Cabré s. XXI)
- Actualitzats `literatura/_index.md` i `autors/_index.md` amb la línia del temps completa

**Observacions:**
- Tots els autors són stubs amb obres principals i moviment. Cal aprofundir per obra concreta.
- Algunes obres mencionades són candidates a fitxa pròpia: *Tirant lo Blanc*, *La plaça del Diamant*, *Solitud*, *Oda a la pàtria*.
- L'obra *Mecanoscrit del segon origen* probablement és una de les lectures obligatòries (a confirmar).

## 2026-05-01 — Ajuste: `.raw/` orientado al temario

- Renombrado `.raw/apunts/` → `.raw/temari/`
- Subcarpetas: `temari/gramatica`, `temari/literatura`, `temari/general`
- Razón: la mayoría de fuentes serán material de temario del curso

## 2026-05-01 — Scaffold inicial

- Creada estructura de carpetes (mode F + E adaptat a estudi PAU)
- Creats _index.md per cada secció
- Creat hot.md, overview.md, index.md
- Creats _templates per cada tipus de nota
- Aplicada CSS de colors per carpeta
