# Criterios de aceptación — Scriptoria Legal

Estado revisado: 25 de octubre de 2026. **Este repositorio por sí solo no certifica cumplimiento legal ni de la aplicación Android.**

| ID | Criterio | Estado | Evidencia / acción |
|---|---|---|---|
| AC-01 | Una política de privacidad pública, legible, HTTPS y sin inicio de sesión | Pendiente de verificar | Habilitar GitHub Pages y abrir la URL en incógnito |
| AC-02 | Política claramente identificada como de Scriptoria | Cumple en documentos | `privacidad.html` |
| AC-03 | Describir datos, finalidades, proveedores, seguridad y conservación | Documentado, sujeto a verificación | Revisar SDK y backend contra cada afirmación |
| AC-04 | Identificar responsable real y contacto privado de privacidad | **Bloqueado** | Confirmar razón social/nombre público y correo atendido |
| AC-05 | Enlace a política en Play Console y dentro de la app | Pendiente en Android/Play | Verificar navegación sin inicio de sesión |
| AC-06 | Solicitud de eliminación dentro de la app | Pendiente de prueba | Comprobar eliminación real y asociados |
| AC-07 | Solicitud de eliminación fuera de la app | **Bloqueado** | Habilitar mecanismo privado operativo; `eliminacion.html` solo informa hoy |
| AC-08 | Informar datos eliminados y retenciones justificadas | Documentado, sujeto a verificación | Validar backups, plazos, proveedores |
| AC-09 | Consentimiento y revocación GDPR (UMP) | Pendiente en Android | Probar elección y cambio de preferencias |
| AC-10 | Inventario AdMob y tratamiento publicitario coherente | Documentado | Confirmar cinco formatos y bloqueo según consentimiento |
| AC-11 | Términos accesibles y propiedad de las obras respetada | Cumple documentalmente | `terminos.html`; comprobar producto |
| AC-12 | Seguridad de los datos en Google Play coincide con política y SDK | Pendiente en Play Console | Auditar y completar formulario |
| AC-13 | Markdown como fuente editorial y HTML como entrega pública | Cumple en estructura | Tres pares `.md` + `.html`; editar ambos o automatizar conversión |
| AC-14 | Enlaces internos accesibles desde móvil | Pendiente de prueba publicada | Revisar `index.html` y las tres rutas |
| AC-15 | Sin instrucciones internas de despliegue en páginas públicas | Cumple documentalmente | Revisar HTML |
| AC-16 | Inglés cuando se anuncie soporte legal en ese idioma | Pendiente | No presentar traducciones no existentes |

## Validación de lanzamiento

No marcar listo para AdMob/Google Play hasta resolver AC-01, AC-03, AC-04, AC-05, AC-06, AC-07, AC-08, AC-09 y AC-12. Revisar con asesoría jurídica según mercados de distribución.

## Referencias oficiales

- [Política de datos de usuario de Google Play](https://support.google.com/googleplay/android-developer/answer/10144311)
- [Google AdMob — privacidad y mensajes](https://support.google.com/admob/answer/12226986)
