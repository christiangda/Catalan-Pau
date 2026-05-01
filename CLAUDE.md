# Catalan-wiki: LLM Wiki

Mode: F (Course/Study) + E (Research)
Purpose: Estudiar para la asignatura de Catalán en la Selectividad (PAU) de Cataluña
Owner: Sebastian
Created: 2026-05-01

## Structure

```
vault/
├── .raw/                  # fuentes inmutables
│   ├── examens-pau/       # exámenes oficiales de años anteriores
│   ├── lectures/          # textos completos de las lecturas obligatorias
│   └── apunts/            # apuntes de clase, materiales del profesor
├── wiki/
│   ├── index.md           # catálogo maestro
│   ├── log.md             # registro cronológico
│   ├── hot.md             # contexto reciente (~500 palabras)
│   ├── overview.md        # resumen ejecutivo
│   ├── gramatica/         # ortografia, morfologia, sintaxi, lèxic
│   ├── literatura/        # moviments, èpoques, gèneres
│   ├── autors/            # un fitxer per autor
│   ├── obres/             # un fitxer per obra de lectura obligatòria
│   ├── vocabulari/        # lèxic clau, frases fetes, locucions
│   ├── examens/           # anàlisi d'exàmens passats per any
│   ├── tecniques/         # comentari de text, redacció, anàlisi
│   ├── sintesi/           # síntesis pròpies, mapes de conceptes
│   ├── meta/              # dashboards, lint reports
│   └── _templates/        # plantilles per cada tipus de nota
```

## Conventions

- Tots els fitxers fan servir frontmatter YAML: type, status, created, updated, tags
- Wikilinks amb format [[Nom de la nota]]: noms únics, sense rutes
- .raw/ conté documents font: mai modificar
- wiki/index.md és el catàleg mestre: actualitzar a cada ingest
- wiki/log.md és append-only: noves entrades a dalt
- Idioma de les notes: català (català per als continguts; castellà o català per a les preguntes/instruccions)

## Operations

- Ingest: deixa la font a .raw/, digues "ingest [filename]"
- Query: pregunta el que sigui — Claude llegeix index.md primer
- Lint: digues "lint the wiki" per fer health check
- Save: digues "save this" per arxivar una conversa important
