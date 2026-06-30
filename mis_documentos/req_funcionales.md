# Requerimientos Funcionales

| Código | Módulo | Detalle |
|----------|----------|----------|
| RF-01 | Registro de Usuario | • Si el usuario no cuenta con una cuenta registrada, podrá crear una nueva desde la aplicación.<br>• Se solicitarán datos básicos como nombre y correo electrónico.<br>• La contraseña deberá cumplir con estándares mínimos de seguridad.<br>• La contraseña deberá almacenarse de forma cifrada en la base de datos. |
| RF-02 | Autenticación | • El usuario registrado podrá iniciar sesión en el sistema.<br>• Se permitirá un máximo de tres intentos consecutivos con credenciales incorrectas.<br>• Opcionalmente, el sistema podrá proporcionar un token de autenticación al iniciar sesión. |
| RF-03 | Inicio | • El sistema deberá mostrar el listado de notas creadas.<br>• El sistema deberá mostrar la información del usuario autenticado.<br>• El sistema deberá proporcionar un menú de navegación entre los diferentes módulos.<br>• Las notas podrán filtrarse por categoría, prioridad o estado. |
| RF-04 | Creación de Notas | • El usuario podrá crear una cantidad ilimitada de notas.<br>• Las notas creadas deberán visualizarse en el listado principal.<br>• Cada nota deberá mostrar un indicador de estado.<br>• Los estados disponibles serán: Pendiente y Terminada. |
| RF-05 | Edición de Notas | • El usuario podrá modificar el contenido de una nota existente. |
| RF-06 | Eliminación de Notas | • El usuario podrá eliminar una nota únicamente si es el autor de la misma.<br>• Antes de eliminar una nota, el sistema deberá solicitar una confirmación. |
| RF-07 | Recordatorios | • El usuario podrá asociar una fecha y hora de recordatorio a una nota. |
| RF-08 | Creación de Categorías/Grupos | • El usuario podrá crear categorías o grupos para organizar sus notas.<br>• Una o varias notas podrán asociarse a una misma categoría. |
| RF-09 | Nivel de Prioridad | • El usuario podrá asignar un nivel de prioridad a una nota.<br>• El nivel de prioridad podrá representarse mediante un valor numérico. |
| RF-10 | Creación de Grupos de Trabajo | • Los usuarios podrán crear grupos para colaborar en la creación y administración de notas.<br>• El creador del grupo será considerado administrador del mismo. |
| RF-11 | Compartir Notas | • El usuario podrá compartir notas con otros usuarios.<br>• Una nota podrá compartirse individualmente o con un grupo previamente creado.<br>• Los usuarios con acceso compartido podrán administrar la nota según los permisos establecidos. |
| RF-12 | Notas Flotantes | • El usuario podrá marcar notas como notas flotantes.<br>• Las notas flotantes podrán superponerse sobre otras aplicaciones.<br>• Las notas se mostrarán como un botón flotante ubicado en el borde izquierdo o derecho de la pantalla. |
