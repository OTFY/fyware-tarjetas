# Fyware Tarjetas Digitales

Tarjetas de presentacion digitales del equipo Fyware, pensadas para usarse con un codigo QR en la credencial.

## Tarjetas activas

| Persona | Puesto | URL |
|---|---|---|
| Hector Rodriguez | Business Developer | https://otfy.github.io/fyware-tarjetas/hector/ |
| Jaime Dodero | Business Developer | https://otfy.github.io/fyware-tarjetas/jaime/ |
| Carlos Franco | Founder & CEO | https://otfy.github.io/fyware-tarjetas/carlos/ |

## Como agregar una tarjeta nueva

1. Copia la carpeta `hector/` con otro nombre (ej. `maria/`).
2. Reemplaza `img/hector.png` con la foto de la persona.
3. Edita `index.html`: nombre, puesto, WhatsApp, correo y redes.
4. Regenera el archivo `.vcf` con los datos nuevos.
5. Haz push a `main`. La pagina queda en `https://otfy.github.io/fyware-tarjetas/<carpeta>/`.
6. Genera un QR nuevo que apunte a esa URL.
