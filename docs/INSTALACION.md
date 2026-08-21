# FULLTRACKERCOL
## Hosting
Sube TODO el contenido a public_html. La web pública, registro demo local, dashboard y panel administrativo funcionan como interfaz. Para activar la API PHP, usa la carpeta /api y configura permisos/hosting PHP.
## Producción GPS
Los rastreadores Coban/Teltonika necesitan un servidor/VPS que acepte TCP/UDP. Flujo recomendado: GPS -> Gateway -> API -> PostgreSQL/PostGIS -> WebSocket -> Web/App. No es seguro ni habitual recibir TCP/UDP directamente en hosting compartido.
## Integraciones pendientes de producción
Mapa real y su clave; pasarela de pagos; correo/SMS/WhatsApp; GPS Gateway; streaming Dashcam; proveedor de IA; apps Android/iOS; certificados y monitorización.
