MiniTareaFinal

Funcionalidades principales
1. Interfaz base y layout (Minitarea 1)

Activity principal con:

Título

Campo EditText para nombre de planta

Botones de acción

Uso de ConstraintLayout

Se añade un ScrollView para adaptarse a pantallas pequeñas.

2. Toast y Snackbar (Minitarea 2)

Botón Guardar → muestra un Toast:
"Planta guardada correctamente"

Botón Mostrar aviso → muestra un Snackbar con acción Deshacer

Acción Deshacer → muestra un Toast:
"Acción cancelada"

3. Notificación del sistema (Minitarea 3)

Botón Enviar notificación crea una notificación con:

Canal propio CANAL_RIEGO

Título: Smart Garden

Texto: "Riego automático activado a las 20:00"

Hace que la app se abra al pulsarla

Solicitud de permiso POST_NOTIFICATIONS en Android 13+

4. Diálogos (DialogFragment) y callbacks (Minitarea 4)

Al pulsar Guardar, se abre un ConfirmDialog con:

Texto: "¿Deseas guardar los datos de esta planta?"

Si el usuario pulsa Aceptar → Snackbar
"Datos guardados"

Si pulsa Cancelar → Toast
"Operación cancelada"

5. Menú de navegación (Minitarea 5)

Clase base BaseMenuActivity que contiene el menú común.

Incluye:

Home

Settings

Cerrar sesión

Opción Cerrar sesión → muestra Snackbar:
"Sesión cerrada correctamente."

Navegación entre pantallas mediante startActivity.

6. Proyecto final integrado (Minitarea 6)

Se integran:

Layout con ScrollView

Botones funcionales

Notificaciones

Snackbars y Toasts

Diálogo de confirmación

Menú y navegación

Botón extra Cerrar sesión visible en la pantalla principal

Diferencias entre Toast, Snackbar y Notificación
--> Toast

Mensaje corto y temporal.

No permite acciones.

Desaparece solo.

No pertenece a una vista.

Uso: avisos rápidos e informales.

--> Snackbar

Similar a Toast, pero:

Puede contener acciones

Se muestra en la parte inferior de la vista

Pertenece a un layout (necesita una View)

Mejor para feedback contextual.

--> Notificación

Persisten en la barra de notificaciones.

Pueden incluir:

Acciones

Iconos

Tocar para abrir la app

Para eventos importantes o que requieren interacción del usuario.
