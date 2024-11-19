# FalconFitUser

## Descripción del Proyecto

En este proyecto se desarrolará una aplicación móvil Android para que los usuarios de un gimnasio puedan gestionar comodamente sus entrenamientos, comprobando el estado de las máquinas en el gimnasio y creando rutinas y superseries propias. Además, se desarrollará una API en **Strapi** que servirá como backend. Para la persistencia local de la aplicación se utilizará **Room** para que los datos esten disponibles sin conexión a Internet.

### Single Source of Truth

Se utilizará Strapi como la fuente principal de datos. La aplicación sincronizará los datos entre la API y la base de datos local en Room automáticamente, de modo que los usuarios puedan trabajar sin conexión y que los datos se actualicen cuando haya conexión a Internet.

## Tecnologías Que Serán Utilizadas

- **Android**: Para el desarrollo de la aplicación móvil.
- **Room**: Para la persistencia local de datos.
- **Strapi**: Backend API para gestionar entidades y relaciones.
- **Material Design**: Para la interfaz de usuario.

## Próximos Pasos

1. Completar el desarrollo de la API en Strapi.
2. Implementar la base de datos local en Room y comenzar la integración inicial.
3. Desarrollar las pantallas principales de la app y configurar la navegación.
