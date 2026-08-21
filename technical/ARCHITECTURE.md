# Arquitectura del ecosistema

## Repositorios principales

| Componente | Responsabilidad |
|---|---|
| `server-engine` | Gamemode, módulos, includes, build y pruebas |
| `server-release` | Preparación y publicación de versiones |
| `server-wiki` | Conocimiento permanente y guías |

## Flujo de información

```text
server-engine
    ├── build y pruebas ──> server-release
    ├── cambios visibles ──> documento maestro
    └── comportamiento validado ──> server-wiki

documento maestro
    ├── foro
    ├── PCU
    └── Discord
```

## Reglas

- El código no se modifica desde la wiki.
- Una release no se deduce a partir de una publicación social.
- La wiki explica la versión vigente y enlaza historial cuando es útil.
- Los datos temporales u operativos pertenecen al PCU o al canal correspondiente.
