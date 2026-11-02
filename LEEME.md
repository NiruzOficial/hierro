# Bitácora de Hierro — instalar en tu celular

Tu app propia: funciona sin internet, guarda todo en tu teléfono y usa la IA gratuita de Google (Gemini) para el coach y las fotos de comida. Todo se puede hacer desde el celular.

## 1. Saca tu clave gratuita de IA (2 min)
1. Entra a https://aistudio.google.com/apikey con tu cuenta de Google.
2. Toca **Create API key** y copia la clave.
3. Guárdala en tus notas: la pegarás dentro de la app.

## 2. Publica la app gratis en GitHub Pages (10 min)
1. Descomprime este .zip en tu celular (en Android: app **Archivos** › toca el zip › **Extraer**).
2. Crea una cuenta en https://github.com (gratis).
3. Toca **+** › **New repository**. Nombre: `hierro`. Déjalo **Public**. Toca **Create repository**.
4. Toca **uploading an existing file** y sube los 6 archivos: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png` y este `LEEME.md`. Toca **Commit changes**.
5. Ve a **Settings** › **Pages**. En *Branch* elige `main` y carpeta `/ (root)`. Toca **Save**.
6. Espera 1–2 minutos. Tu app queda en: `https://TU-USUARIO.github.io/hierro/`

El sitio no contiene datos tuyos: tus registros y tu clave se guardan solo dentro de tu teléfono.

## 3. Instálala (1 min)
1. Abre tu enlace en **Chrome**.
2. Toca **⋮** › **Instalar app** (o *Agregar a la pantalla principal*).
3. Aparece el ícono de Hierro. Ábrela, ve a **Plan › Asistente IA**, pega tu clave, toca **Guardar** y luego **Probar conexión**.

## 4. (Opcional) Generar un APK
1. Entra a https://www.pwabuilder.com y pega tu enlace de GitHub Pages.
2. Toca **Package for stores** › **Android** › **Generate**, y descarga el zip.
3. Dentro está el archivo `.apk`. Ábrelo en el celular y permite *instalar apps desconocidas* para Chrome o Archivos.

La versión instalada desde Chrome (paso 3) ya funciona igual que una app; el APK solo cambia la forma de instalarla.

## Cuidados
- **Respaldo:** en **Plan › Copia de seguridad** descarga un respaldo cada semana y súbelo a Drive. Si borras la app o cambias de celular, lo restauras desde ahí.
- **Límites gratis:** Gemini gratis tiene un límite diario de mensajes. Si aparece “límite alcanzado”, espera unas horas.
- **Privacidad:** en el plan gratuito Google puede usar lo que envías para mejorar sus modelos.
- **Actualizar la app:** si te paso una versión nueva, reemplaza `index.html` en GitHub. Tus datos no se pierden.
