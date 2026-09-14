# Reglamento de uso de IA — Universidad de Boyacá

Resumen navegable por rol de los Acuerdos **1904 de 2025** (Reglamento) y
**1944 de 2026** (formato FOR-IA-001 y límites porcentuales).

## Cómo está armado

```
index.html      todo el sitio (HTML + CSS + JS en un archivo)
img/            logos de la UdeB y del IEF
citas/          89 recortes exactos de los PDF originales
```

Cada afirmación va con **la cita textual** y debajo **el recorte del acuerdo**,
con página y artículo. El recorte es la fuente autorizada: si la transcripción
y la imagen discreparan, manda la imagen.

## Cómo publicarlo en GitHub Pages

1. Subir el contenido de esta carpeta a la raíz del repositorio.
2. Settings → Pages → Source: `main` / `root`.
3. El enlace queda en `https://<organización>.github.io/<repo>/`.

## Cómo hacer cambios

El sitio se genera desde Claude. Para cambios de texto se puede editar
`index.html` directamente y hacer push a `main`. Para cambios estructurales
conviene regenerarlo, porque las tarjetas se construyen desde los JSON de citas.

## Pendientes

- Enlace del **Acuerdo 1944** en Drive (el recibido apuntaba al mismo archivo que el 1904).
- Verificar los ítems marcados en `PENDIENTES.md`.
