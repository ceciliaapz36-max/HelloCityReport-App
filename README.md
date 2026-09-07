# Hello CityReport

Proyecto de la materia de Programación (2027-1).

## Equipo
- Angeles Martinez Cecilia Nayeli
- Ramos Hernandez Carlos Eduardo
- Torres Moreno David Isai

## Pila Tecnológica (Tech Stack)

| Componente | Tecnología / Herramienta | Versión / Detalle |
|---|---|---|
| Lenguaje principal | Kotlin | - |
| Plataforma | Android | Min SDK: 24 (Android 7.0) |
| Arquitectura UI | Jetpack Compose | Declarativa, sin XML |
| Construcción | Gradle (Kotlin DSL) | build.gradle.kts |
| Control de Versiones | Git & GitHub | Repositorio remoto del equipo |

## Estructura de Directorios

## Componentes Clave de la Arquitectura

- **MainActivity.kt**: Extiende de `ComponentActivity`. Es responsable de llamar a `setContent { }`, el punto donde se define toda la interfaz de usuario en código Kotlin.
- **Composables (`@Composable`)**: Funciones como `Greeting()` que describen la UI de forma declarativa — no existen archivos XML de layout, todo el diseño vive en el código Kotlin.
- **Scaffold**: Componente de Compose que estructura la pantalla, usado como contenedor principal de la app.
- **HelloCityReportTheme**: Define el tema visual de la app (colores, tipografía) aplicado a todos los Composables dentro de `setContent`.
- **Modifier**: Sistema de Compose para aplicar tamaño, padding y comportamiento a los elementos de la UI.
