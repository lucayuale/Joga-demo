# ALUNA · BOOKING · Publicación estática

Estudio ficticio de VYB. Imágenes originales generadas con IA y perfiles, horarios, precios y testimonios de demostración identificados. Sin contactos reales ni cuenta Setmore conectada. No hay pagos ni procesamiento de membresías. El horario no representa disponibilidad ni cupos.

Extraer el ZIP. Abrir PowerShell en la carpeta extraída:

```powershell
py -m http.server 8100 --bind 127.0.0.1
```

Abrir http://127.0.0.1:8100/ . Detener con Ctrl+C. No ejecutar desde la vista comprimida del ZIP.

Para GitHub Pages subir index.html, styles.css, app.js, config.js, assets/ y .nojekyll directamente a la raíz del repositorio. Settings → Pages → Deploy from a branch → rama correspondiente → / (root). Rutas relativas compatibles con /nombre-repositorio/. No requiere npm ni compilación.

Para personalizar permanentemente usar VYB_YOGA_PILATES.zip, editar clients/<id>/client.json y regenerar. El README del proyecto incluye alta de clientes, activación de disciplinas, configuración de Setmore y pruebas. No se modificó ni publicó ningún repositorio remoto.

Procedencia de imágenes: RECURSOS.md y PROMPTS_IMAGENES.json.
