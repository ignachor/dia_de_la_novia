# Carta para vos 💌

Página simple lista para deployar en Vercel.

## Cómo deployar en Vercel

**Opción 1 — Drag & drop (más fácil):**
1. Entrá a https://vercel.com y creá una cuenta (podés usar tu GitHub, Google, etc).
2. Andá a "Add New… > Project" y elegí la opción de subir una carpeta / "Deploy" arrastrando esta carpeta completa (`carta-para-vos`).
3. Vercel la va a detectar como un sitio estático y en segundos te da un link (algo como `carta-para-vos.vercel.app`).

**Opción 2 — Con GitHub:**
1. Subí esta carpeta a un repo nuevo en GitHub.
2. En Vercel: "Add New… > Project" > importá ese repo.
3. Como es HTML puro, no hace falta configurar ningún framework ni build command. Deploy directo.

## Personalizar

- **Cambiar las fotos**: reemplazá los archivos en `images/foto1.jpg`, `foto2.jpg`, `foto3.jpg` (mismo nombre) o cambiá el `src` en `index.html`.
- **Cambiar el mensaje**: buscá `<div class="letter-body">` en `index.html` y editá el texto entre los `<p>`.
- **Cambiar los textos de las fotos**: buscá `class="caption"` en `index.html`.
- **Poner su nombre**: en `<div class="letter-title">Para vos</div>` podés cambiar "vos" por su nombre.
