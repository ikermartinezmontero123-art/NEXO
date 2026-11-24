# NEXO para iPhone

Aplicación web instalable (PWA) con diseño móvil, almacenamiento local y chat conectado de forma segura a OpenAI mediante un backend de Vercel.

## Publicarla
1. Crea una cuenta en Vercel y pulsa **Add New > Project**.
2. Sube esta carpeta a un repositorio de GitHub e importa el repositorio en Vercel.
3. En **Settings > Environment Variables**, añade `OPENAI_API_KEY`.
4. Opcional: `OPENAI_MODEL=gpt-5.5` y `ENABLE_WEB_SEARCH=true`.
5. Pulsa **Deploy** y abre la URL HTTPS que genera Vercel.

## Instalarla en iPhone
1. Abre la URL con Safari.
2. Pulsa Compartir.
3. Pulsa **Añadir a pantalla de inicio**.
4. Activa **Abrir como app** y pulsa **Añadir**.

## Seguridad
Nunca escribas la clave API dentro de app.js o index.html. La clave debe estar solo en las variables de entorno de Vercel. El uso de la API tiene coste según el modelo y consumo.
