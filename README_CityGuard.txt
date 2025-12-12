CityGuard — Gestión de Incidencias Municipales

Aplicación Android desarrollada en Kotlin para gestionar incidencias de
un municipio: tráfico, agua, alumbrado y basura.

Funcionalidades principales

-   Listado de incidencias con iconos, dirección, tipo y estado.
-   Detalles de cada incidencia con opción de marcar como resuelta.
-   Diálogo de confirmación (DialogFragment).
-   Notificaciones con canal propio y PendingIntent.
-   Navegación entre actividades con backstack correcto.

Tecnologías

-   Android Studio
-   Kotlin
-   RecyclerView
-   DialogFragment
-   NotificationManagerCompat
-   Repository Pattern

Estructura del proyecto

MainActivity
MyReportsActivity
DetailsActivity
ReportsAdapter
ReportRepository
ConfirmDialogFragment

Permisos

POST_NOTIFICATIONS en Android 13+.

Cómo ejecutar

Abrir el proyecto en Android Studio y ejecutar en un emulador o
dispositivo físico.
