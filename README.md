# Launcher Forge Mintlify Documentation

Starter bilingüe basado en el esquema de documentación proporcionado.

## Incluye

- Inglés en `/en`.
- Español en `/es`.
- Tabs: Help Center, Changelog y API Reference.
- API Reference marcada como Coming Soon.
- CLI documentada como interactiva.
- Páginas de prioridad inicial.
- Bloques de capturas reemplazables con `<Frame>`.
- Logos y favicon de reemplazo.

## Agregar fotos

Reemplaza los PNG dentro de:

```text
images/screenshots/
```

Mantén el mismo nombre de archivo y no tendrás que modificar las páginas MDX.

## Vista local

```bash
npm install -g mint
mint dev
```

## Validación

```bash
mint validate
mint broken-links --check-anchors
```

## Antes de publicar

- Reemplaza logos y capturas.
- Confirma URLs definitivas.
- Confirma versiones compatibles de Unreal Engine.
- Confirma planes y límites.
- Actualiza el changelog con cambios reales.
- Mantén API Reference como Coming Soon hasta estabilizar la API externa.
