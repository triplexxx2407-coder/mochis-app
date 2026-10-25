# MOCHI

MOCHI es una app web de red social y marketplace para negocios locales de Los Mochis, Sinaloa, México. La gente publica, sigue a otros, comenta y manda mensajes; los negocios tienen su perfil, sus productos y pedidos para recoger en tienda. La app no cobra pagos.

Es un proyecto en etapa de pruebas cerradas. Todavía no está abierto al público.

## Cómo está hecho

- **`index.html`**: la app completa en un solo archivo (HTML, CSS y JavaScript sin frameworks). Incluye los textos legales.
- **Backend**: Supabase (Postgres, Auth, Storage y Realtime), con Row Level Security en todas las tablas. En la página solo va la llave pública `anon`; ninguna llave secreta está ni debe estar en este repositorio.
- **Publicación**: GitHub Pages, desde la rama `main`. Cada commit a `main` publica el sitio.

## Cómo se despliega

1. Se edita `index.html` en una rama.
2. Se abre un pull request hacia `main` y se revisa.
3. Antes de aceptarlo, se prueba en celular (emulación de iPhone y toques al azar). La estabilidad en celular va antes que cualquier función nueva.
4. Al hacer merge, GitHub Pages publica la nueva versión en unos minutos.

## Documentación

El estado del proyecto, las decisiones, los pendientes y el historial de versiones están en los archivos privados del proyecto (empezando por `ESTADO-DEL-PROYECTO.md`), no en este repositorio.

## Seguridad

Si encuentras un problema de seguridad, no lo publiques en un issue: avisa por mensaje privado al dueño del repositorio.
