---
type: meta
title: "Log"
updated: 2026-05-01
---

# Log d'operacions

Registre cronològic de tots els canvis a la wiki. Append-only — noves entrades a dalt.

---

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
