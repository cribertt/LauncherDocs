# Cómo subir correctamente a GitHub

## La estructura correcta

```text
tu-repositorio/
├── docs.json
├── README.md
├── en/
├── es/
└── images/
```

## Estructuras incorrectas

```text
tu-repositorio/
└── launcherforge-mintlify-complete/
    └── docs.json
```

```text
tu-repositorio/
└── launcherforge-mintlify-complete-repository.zip
```

## Pasos

1. Descomprime el ZIP.
2. Entra a la carpeta descomprimida.
3. Selecciona `docs.json`, `en`, `es`, `images` y los demás archivos.
4. Súbelos directamente a la raíz del repositorio.
5. Verifica que GitHub muestre `docs.json` al abrir la página principal del repositorio.
6. Conecta la rama correcta en Mintlify.
7. Deja vacío el subdirectorio si `docs.json` está en la raíz.
