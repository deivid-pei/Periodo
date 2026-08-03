# Ciclo — publicar en GitHub Pages e instalar en iPhone

La app es **un solo archivo**: `index.html`. No necesita servidor, cuenta ni conexión.
Los registros se guardan en el dispositivo y nunca salen de él.

---

> **Sobre la privacidad:** el repositorio es público, pero solo contiene el código de la app — cero datos. Los registros viven únicamente en el iPhone de ella.

---

## Parte 2 · Instalarla en el iPhone

Esto es importante, no es opcional. Hazlo así:

1. Abre la dirección **en Safari** (no en Chrome — solo Safari puede instalar en la pantalla de inicio en iOS).
2. Toca el botón **Compartir** (el cuadrito con la flecha hacia arriba, abajo en el centro).
3. Desliza y elige **Añadir a pantalla de inicio**.
4. Nombre: `Ciclo` → **Añadir**.

Queda el ícono en la pantalla de inicio. Se abre a pantalla completa, sin barra del navegador, y funciona sin internet.

### ⚠️ Lo único que hay que recordar

**Debe usarse siempre ícono de la pantalla de inicio, no la pestaña de Safari.**

Dos razones:

- En iOS, la app instalada y la pestaña de Safari guardan los datos **por separado**. Si registra en una y luego abre la otra, parecerá que se perdieron las fechas.
- Safari borra los datos de sitios web que no se visitan en 7 días. Las apps agregadas a la pantalla de inicio **están exentas** de ese borrado.

Una vez instalada, se puede cerrar la pestaña de Safari.

---

## Parte 3 · Cómo se usa

- Solo se registra **el día en que inicia el periodo**. Nada más.
- Al registrar el siguiente inicio, la app calcula sola la diferencia de días.
- **Último ciclo:** días entre los dos últimos inicios.
- **Promedio:** promedio de todos los ciclos registrados.
- **Día del ciclo:** días transcurridos desde el último inicio (hoy incluido).
- El ícono de papelera borra una fecha, con confirmación.
- No acepta fechas futuras ni repetidas.

---

## Parte 4 · Respaldo (recomendado cada tanto)

Los datos viven en el iPhone. Si cambia de celular o borra la app, se pierden.

**Respaldar:** toca *Respaldar* → se abre el menú de compartir de iOS → **Guardar en Archivos** (elige iCloud Drive) o envíatelo por correo/WhatsApp.

**Restaurar:** en el iPhone nuevo, abre la app instalada → *Restaurar* → **Explorar** → busca el archivo `ciclo-….json` y ábrelo. Las fechas se agregan sin duplicar.

---

## Actualizar la app más adelante

Repositorio → `index.html` → ícono del lápiz o **Upload files** con el archivo nuevo → *Commit changes*. En 1–2 minutos la dirección sirve la versión nueva. **Los datos de ella no se tocan.**
