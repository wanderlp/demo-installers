# Demo Installers

**Instaladores demo de los proyectos que voy armando, servidos desde GitHub Releases.**

---

## ¿Qué encontrás acá?

Los instaladores públicos de los proyectos que voy armando. Cada programa
tiene su propia release con su binario listo para descargar — no hay código
fuente en este repo, solo los `.exe` finales.

## Instaladores disponibles

| Programa | Versión | Windows | macOS | Linux |
|---|---|---|---|---|
| [Visor Documentos FEL](./visor-consulta-dte-sat/README.md) | v0.2.1 | [Setup.exe](https://github.com/wanderlp/demo-installers/releases/download/visor-documentos-fel-v0.2.1/VisorDocumentosFEL-Setup-0.2.1.exe) | — | — |
| [MergeMate](https://github.com/wanderlp/mergemate) | v1.0.3 | [Setup.exe](https://github.com/wanderlp/mergemate/releases/download/v1.0.3/MergeMate-Setup.exe) | [DMG](https://github.com/wanderlp/mergemate/releases/download/v1.0.3/MergeMate.dmg) | [AppImage](https://github.com/wanderlp/mergemate/releases/download/v1.0.3/MergeMate.AppImage) |

## Command Gate (`cgate`)

CLI que se registra como MCP server para Claude Code, opencode y Cursor. El
binario se auto-instala al correrlo (se agrega al PATH y se registra con los
clientes IA que encuentre) — no hace falta un wizard separado.

| Versión | Windows | macOS (arm64) | Linux |
|---|---|---|---|
| v0.2.4 | [.exe](https://github.com/wanderlp/command-gate-for-ai-agents/releases/download/v0.2.4/cgate-windows-amd64.exe) | [binario](https://github.com/wanderlp/command-gate-for-ai-agents/releases/download/v0.2.4/cgate-macos-arm64) | [binario](https://github.com/wanderlp/command-gate-for-ai-agents/releases/download/v0.2.4/cgate-linux-x86_64) |

También instalable vía `pipx install command-gate`, Scoop (Windows) o
Homebrew (macOS/Linux) — detalles en el
[repo del proyecto](https://github.com/wanderlp/command-gate-for-ai-agents#get-started).

## ¿Encontraste un problema?

Los instaladores son **builds públicos** generados desde los repos fuente
de cada proyecto. **No abras issues acá** — este repo es solo de binarios,
no se mantiene como issue tracker.

- **MergeMate** → abrí un issue en [wanderlp/mergemate](https://github.com/wanderlp/mergemate/issues)
- **Visor Documentos FEL** → no tiene issue tracker público (el código fuente vive en un repo privado)
- **Command Gate** → abrí un issue en [wanderlp/command-gate-for-ai-agents](https://github.com/wanderlp/command-gate-for-ai-agents/issues)
