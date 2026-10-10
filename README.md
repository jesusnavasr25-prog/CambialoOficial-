# Páginas públicas de Cámbialo

Lo que Google Play exige que viva en una URL pública. Hoy es solo la política
de privacidad, en `index.html`.

Se sirve con GitHub Pages desde `main` / raíz:
**https://jesusnavasr25-prog.github.io/CambialoOficial-/**

Esa dirección está pegada en la ficha de Play Console, así que no se mueve ni
se renombra el archivo: si cambia la URL, la ficha queda apuntando al vacío.

## Cuándo hay que tocar esto

Cuando en la app cambie algo de lo que la política afirma:

- Se agrega o se quita un **permiso** de Android.
- Se consulta un **endpoint** nuevo, o se deja de consultar uno de los listados.
- Se empieza a guardar algo que hoy no se guarda, o a mandar algo afuera.

Al editar, se actualiza también la fecha del encabezado. El código vive aparte,
en el repositorio privado de la app.
