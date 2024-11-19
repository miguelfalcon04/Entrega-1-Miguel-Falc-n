# FalconFitUser

## Descripción del Proyecto

Este proyecto consiste en el desarrollo de una aplicación móvil Android que permitirá a los usuarios gestionar entrenamientos personalizados, verificar el estado de las máquinas en el gimnasio y administrar configuraciones relacionadas con sus rutinas. Además, se desarrollará una API en **Strapi** que servirá como backend compartido entre los distintos módulos de la aplicación. La persistencia local en la aplicación será implementada utilizando **Room** para que los datos esten disponibles sin conexión a Internet.

### Single Source of Truth

Se utilizará Strapi como la fuente principal de datos. La aplicación sincronizará los datos entre la API y la base de datos local en Room, de modo que los usuarios puedan trabajar sin conexión y que los datos se actualicen cuando haya conexión a Internet.

## Tecnologías Que Serán Utilizadas

- **Android**: Para el desarrollo de la aplicación móvil.
- **Room**: Para la persistencia local de datos.
- **Strapi**: Backend API para gestionar entidades y relaciones.
- **Material Design**: Para la interfaz de usuario.

## Próximos Pasos

1. Completar el desarrollo de la API en Strapi.
2. Implementar la base de datos local en Room y comenzar la integración inicial.
3. Desarrollar las pantallas principales de la app y configurar la navegación básica.

