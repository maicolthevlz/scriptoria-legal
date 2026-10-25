# Scriptoria — sitio legal (Android)

Documentos estáticos para GitHub Pages. No contiene aplicación web, backend ni información privada.

## Antes de publicar (obligatorio)

1. Sustituye los marcadores `[NOMBRE LEGAL...]`, `[PAÍS]` y `[CORREO...]` en los `.md` y en los `.html` correspondientes. Si modificas el Markdown, vuelve a generar o actualiza el HTML correspondiente.
2. Revisa con Codex la implementación real de AdMob, UMP, OneSignal, R2, Supabase, análisis remoto, borrado, retención, compras y exportaciones; elimina cualquier afirmación no confirmada.
3. En `eliminacion.html`, publica una dirección real que reciba solicitudes de borrado y comprueba que el proceso funcione de principio a fin.
4. Traduce al inglés si vas a declarar una política en ese idioma; la página incluida se encuentra en español.
5. Considera revisión jurídica en las jurisdicciones de distribución.

## GitHub Pages

1. Crea un repositorio **público** llamado `scriptoria-legal` en GitHub (no publiques secretos).
2. Sube el contenido de esta carpeta a la raíz de la rama `main`.
3. Ve a **Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save**.
4. La URL será `https://TU-USUARIO.github.io/scriptoria-legal/privacidad.html` **solo después de que GitHub Pages publique correctamente el sitio**.
5. Comprueba en modo incógnito HTTPS y que `privacidad.html`, `terminos.html` y `eliminacion.html` abran sin autenticación.
6. Agrega la URL real en AdMob (Privacidad y mensajes), Play Console y Configuración de Scriptoria. Para eliminación, usa la URL real de `eliminacion.html` en Play Console.

## Git local

Se incluye un repositorio Git con un commit inicial. Para añadir remoto:

```bash
git remote add origin https://github.com/TU-USUARIO/scriptoria-legal.git
git branch -M main
git push -u origin main
```

Los identificadores de AdMob **no son necesarios** en este repositorio; deben configurarse en la app Android.
