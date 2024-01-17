# Asset per il catalogo nazionale della semantica dei dati
Questo è il repository INPS per l'alimentazione del National Data Catalog (NDC): https://www.schema.gov.it/.
Esso contiene l'ontologia di INPS che descrive il patrimonio informativo dell'ente relativamente al dominio di _riscatti ricongiunzioni e rendite_ e _lavoratore domestico_.

Il catalogo nazionale della semantica dei dati, o NDC, consente:
> "Ricerca e riuso di asset semantici, tra cui ontologie, schemi dati e vocabolari controllati per supportare lo sviluppo di API semanticamente e sintatticamente interoperabili"

## Organizzazione delle informazioni

I file presenti in questo repository sono organizzati secondo la seguente alberatura:

```bash
┌─ assets/controlled-vocabularies/
│  ├─ tipo_gestione_ricongiunzione
│  │   ├─ latest
│  │   │   ├─ tipo_gestione_ricongiunzione.csv
│  │   │   ├─ tipo_gestione_ricongiunzione.json
│  │   │   └─ tipo_gestione_ricongiunzione.ttl
│  │   ├─ v{version}
│  │   │   ├─ tipo_gestione_ricongiunzione.csv
│  │   │   ├─ tipo_gestione_ricongiunzione.json
│  │   │   └─ tipo_gestione_ricongiunzione.ttl
│  ├─ ...
│  ├─ frame-short.yamlld
│  └─ notes.md
├─ assets/ontologies/
│  ├─ contributions
│  │   ├─ latest
│  │   │   ├─ contributions.n3
│  │   │   ├─ contributions.owl
│  │   │   └─ contributions.ttl
│  │   ├─ v{version}
│  │   │   ├─ contributions.n3
│  │   │   ├─ contributions.owl
│  │   │   └─ contributions.ttl
│  ├─ ...
│  └─ notes.md
├─ assets/schemas/
│  ├─ contratto-di-lavoro
│  │   ├─ latest
│  │   │   └─ contratto-di-lavoro.oas3.yaml
│  │   ├─ v{version}
│  │   │   └─ contratto-di-lavoro.oas3.yaml
│  ├─ ...
│  └─ notes.md
├─ README.md
└─ publiccode.yaml
```

Ontologie e [vocabolari controllati](https://www.agid.gov.it/it/dati/vocabolari-controllati) sono documenti [RDF](https://www.w3.org/RDF/) serializzati in formato [TURTLE](https://www.w3.org/TR/turtle/) mentre gli schemi  [Open Api 3 (OAS3)](https://spec.openapis.org/oas/v3.1.0) sono serializzati in formato [YAML](https://yaml.org/).

