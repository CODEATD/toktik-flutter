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
Los videos no están incluídos en el repositorio, debido a que son muy pesados y GitHub no lo permite.

Pueden descargar 8 videos de aquí:
[Pexels Free Videos](https://www.pexels.com/search/videos/vertical/)

Renombren esos videos así, ya que es lo que se encuentra en nuestro data source.
```
1.mp4
2.mp4
3.mp4
4.mp4
5.mp4
6.mp4
7.mp4
8.mp4
```
