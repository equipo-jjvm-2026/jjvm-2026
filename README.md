# jjvm-2026
1. Descripción del Proyecto
El sistema funciona como un motor de búsqueda y comparación de artículos de consumo masivo. La solución aborda la asimetría de información en el mercado de supermercados, entregando al usuario una visualización comparativa de precios, ofertas vigentes y disponibilidad de stock en distintas cadenas.

2. Arquitectura y Atributos de Calidad
El diseño del software se ha estructurado priorizando los siguientes atributos de calidad para garantizar una experiencia de usuario robusta:

Seguridad (Prioridad Alta): Implementación de un módulo de autenticación centralizado. La integridad de los datos se garantiza mediante el manejo de sesiones y credenciales cifradas para el acceso al perfil de usuario.

Usabilidad: Interfaz diseñada para la eficiencia en la búsqueda. El sistema incluye un motor de sugerencias dinámicas que minimiza la carga cognitiva del usuario al navegar entre categorías de artículos.

Disponibilidad y Consistencia: El core del sistema se enfoca en la entrega de datos precisos sobre el stock por supermercado, asegurando que la información consultada refleje la realidad de las góndolas.

Rendimiento: Optimización de las consultas para permitir que el despliegue de precios de múltiples fuentes se realice con una latencia mínima.

3. Flujo del Usuario
Autenticación: El usuario ingresa mediante un login seguro para personalizar su experiencia y acceder a sugerencias.

Dashboard Principal: Despliegue de artículos destacados y ofertas basadas en algoritmos de relevancia.

Búsqueda y Filtro: El usuario selecciona un artículo general y el sistema procesa la comparación multitienda.

Visualización de Resultados: Presentación de precios, desglose de ofertas y verificación de stock en tiempo real.
