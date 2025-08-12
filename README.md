# UrbanNest-Solutions
Technology for smart cities
## Contexto
UrbanNest Solutions busca desarrollar una plataforma web interactiva que conecte a los residentes de una ciudad con micro-eventos y rutas de interés cercanas. La idea es combinar datos de geolocalización, inteligencia comunitaria y visualización en tiempo real para mejorar la experiencia urbana.

El sistema permitirá a los usuarios:

* Explorar un mapa interactivo con eventos comunitarios (mercados locales, conciertos callejeros, ferias, clases gratuitas en parques, etc.).

* Crear y compartir micro-rutas (por ejemplo, "Ruta de murales de arte urbano" o "Caminata gastronómica").

* Ver en tiempo real la actividad y popularidad de cada evento o ruta, usando datos de interacción de otros usuarios.

* Guardar y seguir rutas/eventos favoritos.

* Recibir recomendaciones personalizadas basadas en intereses y ubicación.

## Requerimientos Técnicos
### Frontend (React o Vue)
* Mapa interactivo (puede usar Leaflet o Mapbox).

* Sistema de autenticación y perfil de usuario.

* Feed dinámico de eventos y rutas.

* Panel de creación de rutas con geolocalización de puntos.

* Integración de notificaciones en tiempo real (p.ej., WebSockets).

### Backend (Node.js con Express)
* API REST para gestión de usuarios, eventos y rutas.

* Integración con servicios de mapas y geocodificación (Mapbox, OpenStreetMap).

* WebSockets para actualizaciones en tiempo real (popularidad de un evento, usuarios conectados).

* Recomendador básico de rutas/eventos (puede ser por intereses o ubicación).

### Base de Datos (PostgreSQL con Supabase)
Tablas principales:

* users (usuarios registrados).

* events (eventos con ubicación y detalles).

* routes (rutas creadas por usuarios con puntos geolocalizados).

* favorites (eventos o rutas guardados).

* activity_log (registro de visualizaciones, interacciones y popularidad).

### Extras Innovadores
* Sistema de gamificación: los usuarios ganan puntos por asistir a eventos o crear rutas populares.

* Visualización de "zonas activas" en el mapa con colores según la densidad de eventos.

* Ranking semanal de rutas más visitadas.
