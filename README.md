# Mars Photos 🪐🛰️

![Mars Photos App Screenshot](./captura/Screenshot_20250705_213500.png)

**Mars Photos** es una aplicación de demostración para Android que muestra imágenes reales de la superficie de Marte. Estas fotos son capturadas por los rovers de la NASA y se obtienen a través de un servicio web REST.

## ✨ Características

- Muestra una cuadrícula de fotos de Marte.
- Carga de imágenes asíncrona desde una API remota.
- Interfaz de usuario limpia y moderna construida con Jetpack Compose.
- Manejo de estados de carga, éxito y error.

## 🛠️ Construido con

- [Kotlin](https://kotlinlang.org/) - Lenguaje de programación principal.
- [Jetpack Compose](https://developer.android.com/jetpack/compose) - Kit de herramientas de UI moderno para Android.
- [Retrofit](https://square.github.io/retrofit/) - Cliente HTTP para realizar solicitudes a la API REST.
- [kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) - Para deserializar la respuesta JSON.
- [Coil](https://coil-kt.github.io/coil/) - Para la carga de imágenes.
- [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Para gestionar los datos relacionados con la UI.
- [Coroutines](https://kotlinlang.org/docs/coroutines-overview.html) - Para el manejo de tareas asíncronas.

## 🚀 Empezando

Sigue estos pasos para tener una copia del proyecto funcionando en tu máquina local.

### Prerrequisitos

- [Android Studio](https://developer.android.com/studio) (versión Hedgehog o superior recomendada).
- Conocimientos básicos de desarrollo en Android con Kotlin y Jetpack Compose.

### Instalación

1. Clona el repositorio:
   ```sh
   git clone https://github.com/your-username/mars-photos.git
   ```
2. Abre el proyecto en Android Studio.
3. Construye y ejecuta la aplicación.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si tienes alguna idea, sugerencia o encuentras un error, por favor abre un *issue* o envía un *pull request*.

## 📄 Licencia

Este proyecto está bajo la Licencia Apache 2.0 - mira el archivo [LICENSE](LICENSE) para más detalles.

## Codelabs Relacionados

Este proyecto es la base de varios codelabs de Android Basics con Compose. Puedes encontrarlos aquí:

- [Obtener datos de internet](https://developer.android.com/codelabs/basic-android-kotlin-compose-getting-data-internet)
- [Agregar repositorio e Inyección de Dependencias Manual](https://developer.android.com/codelabs/basic-android-kotlin-compose-add-repository)
- [Cargar y mostrar imágenes de internet](https://developer.android.com/codelabs/basic-android-kotlin-compose-load-images)
