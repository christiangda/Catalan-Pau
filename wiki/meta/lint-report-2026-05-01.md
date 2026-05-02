---
type: meta
title: "Lint Report 2026-05-01"
created: 2026-05-01
updated: 2026-05-01
tags: [meta, lint]
status: developing
---

# Lint Report: 2026-05-01

Post-tanda-4 health check after ~30 PDFs ingerits en 4 tandes paral·leles.

## Summary
- Pages scanned: **121** (excloent `_templates/`)
- Wikilinks únics: **155**
- Issues found: **31**
- Auto-fixed: **0** (esperant decisió de l'usuari)
- Needs review: **31**

---

## 🔴 Dead Links — alta prioritat

Wikilinks que apunten a pàgines inexistents.

### A. Filename mismatches (mateixa entitat, nom diferent)
Aquests es resolen renombrant el wikilink, no creant pàgina:

| Link usat | Fitxer real | Acció suggerida |
|-----------|-------------|-----------------|
| `[[Ausiàs Marc]]` | `Ausiàs March.md` | renombrar enllaços → `[[Ausiàs March]]` |
| `[[Francesc Vicenç Garcia]]` | `Francesc Vicent Garcia.md` | renombrar → `[[Francesc Vicent Garcia]]` |
| `[[Josep M. Benet i Jornet]]` (amb punts) | `Josep M Benet i Jornet.md` | renombrar → `[[Josep M Benet i Jornet]]` |
| `[[Maria Mercè Marçal]]` | `Maria-Merce Marcal.md` | renombrar wikilinks o **renombrar fitxer** (preferible diacritic) |
| `[[Miquel Martí i Pol]]` | `Miquel Marti i Pol.md` | mateixa decisió: alias o renombrar |
| `[[Famílies linguístiques]]` | `Familias linguistiques.md` | el fitxer té error ortogràfic castellà — **renombrar fitxer** a `Famílies lingüístiques.md` |

### B. Markdown artifacts (escapatori `\` final de línia)
Backslash residual al final d'enllaços dins taules. **Editar les taules** per eliminar el `\`:
- `[[Angel Guimera\]]`
- `[[Guerra-i-Postguerra\]]`
- `[[Renaixenca\]]`
- `[[Santiago Rusinol\]]`

### C. Path-style wikilinks (funcionen però són inconsistents)
Obsidian els resol però trenquen la convenció. Substituir per nom net:
- `[[autors/_index]]`, `[[examens/_index]]`, `[[gramatica/_index]]`, `[[literatura/_index]]`, `[[obres/_index]]`, `[[sintesi/_index]]`, `[[tecniques/_index]]`, `[[vocabulari/_index]]`
- 11× `[[sources/src-*]]` (ex. `[[sources/src-fonetica-canvis]]` → `[[src-fonetica-canvis]]`)

### D. Pàgines mencionades sense fitxer (decidir crear stub o eliminar enllaç)
- ⭐ `[[La plaça del Diamant]]` / `[[La placa del Diamant]]` — **molt referenciada**; probable lectura PAU. Cal crear pàgina d'obra (recordatori ja a `hot.md`).
- `[[Tirant lo Blanc]]` — obra clàssica referenciada en gèneres + tradició; cal stub.
- `[[Solitud]]` (Víctor Català) — referenciada com a exemple narratiu; stub.
- `[[Jocs Florals]]` — concepte clau de la Renaixença; stub.
- `[[Oda a la pàtria]]` (Aribau) — referenciada; stub.
- `[[Gabriel Ferrater]]`, `[[Joan Vinyoli]]`, `[[Marius Torres]]`, `[[Jordi de Sant Jordi]]` — autors referenciats; cap fitxa. Crear stubs o eliminar mencions si tangencials.

### E. Placeholders d'agent
- `[[Obra 1]]`, `[[Obra 2]]` — placeholders deixats per algun agent. **Eliminar o substituir per obra real.**

---

## 🟡 Frontmatter Gaps

| Fitxer | Camps absents |
|--------|---------------|
| `overview.md`, `hot.md`, `log.md`, `index.md` | `status`, `created` |
| 7× `_index.md` (cada subdomini) | `status`, `created` |
| `sources/src-figures-retoriques.md` | `status`, `created`, `updated` |
| 4× `sources/src-{autors,moviments,temari}*` (tanda 1) | `created`, `updated` |
| `sources/src-tipologies-textuals-pdf.md` | `status`, `created` |

> Els `_index.md` i les pàgines meta normalment no necessiten `status`, però sí `created`. Decidir convenció.

---

## 🟢 Orphan Pages

**0 pàgines orfes**. Cada fitxer té com a mínim un enllaç entrant. Excel·lent connectivitat post-ingest paral·lel.

---

## 🟢 Empty Sections

Cap detectada en una mostra ràpida. Si vols verificació exhaustiva, cal grep més fi.

---

## 🟡 Stale / Duplicate Risk

Revisió manual recomanada (parallel ingest pot haver duplicat conceptes):

- [[Correlacions verbals]] vs [[Els verbs]] vs [[Oracions adverbials]] — **triangle delicat** sobre condicionals. La cadena d'ingest els va deixar amb cross-links bidireccionals, però cal verificar que les **regles d'ús** del condicional no es repeteixen literalment a les 3.
- [[Funcions sintactiques]] vs [[Sintaxi - oracions]] — el segon va ser dissenyat per cobrir tipologia (no funcions), però la separació podria ser borrosa en llocs.
- [[Morfologia]] absorveix algunes parts que també hi ha a [[Pronoms febles]] (pronoms personals tònics) i [[Els verbs]] (categoria verb). Cross-links existeixen; verificar que no hi ha definicions repetides.
- [[Variants dialectals]] vs [[Sociolinguistica - conceptes basics]] — possible solapament en àmbit territorial.

---

## 📋 Top 5 prioritats per decidir

1. **Crear stub `[[La plaça del Diamant]]`** — referenciada moltes vegades, pendent des de hot.md, podria sortir a la PAU.
2. **Resoldre 6 filename mismatches** (Ausiàs Marc/March, Maria-Merce Marçal, etc.) — decidir: renombrar fitxers per recuperar diacrítics? O afegir aliases als wikilinks?
3. **Netejar 4 backslash artifacts** (`Angel Guimera\`, etc.) — edició mecànica de les taules afectades.
4. **Eliminar `[[Obra 1]]` i `[[Obra 2]]`** — placeholders olvidats.
5. **Substituir 19× path-style wikilinks** (`[[autors/_index]]`, `[[sources/src-*]]`) per la forma curta — millora autocomplete d'Obsidian.

Stubs nous suggerits (poc esforç, alt valor PAU): `Tirant lo Blanc`, `Jocs Florals`, `Oda a la pàtria`, `Solitud`.

---

## Next steps

L'usuari ha de decidir abans d'auto-fix:
- ¿Renombrem fitxers d'autors per recuperar diacrítics (Maria-Merce → Maria Mercè), o mantenim noms ASCII i actualitzem wikilinks?
- ¿Crear stubs ara per a les 4 obres canòniques (`Tirant`, `Solitud`, `La plaça del Diamant`, `Oda a la pàtria`), o esperar nova font?
- ¿Aplicar l'auto-fix de path-style wikilinks (segur, mecànic)?
