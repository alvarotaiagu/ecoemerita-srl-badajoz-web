# Clínica Veterinaria Emérita (Mérida)

Web de la clínica, hecha con la plantilla veterinaria «La marca manda».

- **Datos del negocio:** `negocio.json`.
- **Marca** (logo, colores, tipografía): `marca/`.
- **Fotos:** `media/`.
- **Regenerar las páginas:** `node scripts/aplicar.mjs`.
- **Comprobar:** `node scripts/verificar.mjs --rapido`.
- **Ver en local:** `node scripts/servir.mjs` → http://127.0.0.1:4191/

Las páginas (`index.html`, `aviso-legal.html`, `privacidad.html`, `404.html`) se
generan desde `fuente/`: no se editan a mano.

La clínica no publica su horario en su web actual, así que esta versión no lo
muestra: ni la tabla, ni el «abierto ahora». Cuando lo confirme, se pone en
`negocio.json` (`horario`) y se vuelve a aplicar.

Borrador de trabajo: sin indexar (`noindex`).
