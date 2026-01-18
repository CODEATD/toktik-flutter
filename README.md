# TokTik - Flutter Video App Clone

Proyecto desarrollado como parte del curso **Flutter: De cero a experto** de Fernando Herrera. Una aplicación inspirada en TikTok para la visualización de videos cortos con scroll infinito.

## Descripción

TokTik es una aplicación móvil construida con Flutter que permite la reproducción de videos locales mediante un scroll vertical. El proyecto aplica patrones de arquitectura limpia y manejo de estado robusto.

## Conceptos Aprendidos y Aplicados

- **Arquitectura DDD (Domain-Driven Design)**: Separación clara de responsabilidades en capas:
  - **Domain**: Entidades (`VideoPost`) que representan el negocio.
  - **Infrastructure**: Modelos (`LocalVideoModel`) y mappers para la transformación de datos.
  - **Presentation**: Pantallas, widgets y providers.
- **State Management**: Uso de **Provider** para la gestión del estado global y la carga de datos.
- **Mappers**: Implementación de lógica para transformar modelos de infraestructura a entidades de dominio.
- **Custom Widgets**: Creación de componentes reutilizables como `VideoPlayer`, `VideoButtons` y `FullVideoPlayer`.
- **Manejo de Video**: Integración del paquete `video_player` y gestión de su ciclo de vida (inicialización/dispose).
- **Animaciones**: Uso de `animate_do` para mejorar la experiencia de usuario con micro-interacciones.
- **Scroll Infinito**: Implementación de listas con comportamiento de scroll vertical fluido.

## Tecnologías y Paquetes

- **Flutter SDK**
- **Dart**
- **Provider** (Gestión de estado)
- **Video Player** (Reproducción de video)
- **Animate Do** (Animaciones)
- **Intl** (Formateo de números)

## Características

- Scroll vertical tipo TikTok.
- Reproducción automática de videos.
- Botones de interacción con contadores estilizados.
- Gradientes personalizados sobre los videos para legibilidad.

---

> [!IMPORTANT]
> **Nota sobre los activos:** Por motivos de peso y políticas de GitHub, los videos de la carpeta `assets/videos/` no están incluidos en este repositorio. Para ejecutar el proyecto, asegúrate de agregar tus propios videos en esa ruta siguiendo la estructura del curso.
