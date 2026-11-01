# Hornea2

App de Hornea2 para registrar ventas, compras, caja, insumos y la parrilla de contenido.

- Se instala en el iPhone desde Safari con "Añadir a pantalla de inicio".
- Los datos se guardan en Supabase (tabla `estado`), protegidos con inicio de sesión. Solo entran los correos de la tabla `miembros`.
- `config.js` tiene la URL del proyecto y la clave pública de Supabase.
- `seed.json` son los datos iniciales; se suben una sola vez, si la tabla está vacía.
