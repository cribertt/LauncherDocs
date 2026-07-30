# Launcher Forge - Mintlify documentation

Repositorio completo bilingüe basado en el esquema de documentación proporcionado.

## Importante

El ZIP fue creado para que `docs.json` quede directamente en la raíz al descomprimirlo.

Estructura:

```text
docs.json
README.md
en/
es/
images/
```

No subas una carpeta contenedora adicional a GitHub.

## Contenido

- 41 páginas en inglés.
- 41 páginas en español.
- Help Center / Centro de ayuda.
- Changelog / Novedades.
- API Reference / Referencia API.
- Todas las carpetas del esquema.
- CLI documentada como interactiva.
- Unity marcada como Beta.
- Godot, Service Status y API marcados como Coming Soon.
- Áreas reemplazables para capturas.

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

## GitHub

Sube directamente el contenido de esta carpeta a la raíz del repositorio:

```text
repository/
├── docs.json
├── en/
├── es/
└── images/
```
