# TP-final-sonus
repositorio del trabajo final de programaciòn I en C


Requisitos Mínimos e Indispensables
El SGM de "Sonus 2.0" debe garantizar la persistencia de los datos. Los datos de
usuarios, artistas, álbumes, canciones y calificaciones deben almacenarse en archivos
binarios separados.

I. Acceso y Roles 🔒
  1. Login y Seguridad: El sistema debe iniciar con un módulo de login que debe
identificar si el usuario es un Artista o un Usuario (cliente) para redirigir al menú
correcto.
  2. Registro: Debe permitir registrar nuevos Usuarios y nuevos Artistas (cada uno
en su archivo correspondiente).

II. Funcionalidades del Artista (Carga de Contenido) 🎤
El menú del Artista debe permitir:
  1. 3a. Agregar / Modificar Álbum: Permite ingresar un nuevo álbum. El
nombreArtista debe coincidir con el del artista logueado.
  2. 3b. Agregar / Modificar Canción: Permite ingresar una nueva canción. El
nombreArtista debe coincidir con el del artista logueado y el nombreAlbum debe
existir previamente en el catálogo.

III. Funcionalidades del Usuario (Consumo e Interacción) ⭐
El menú del Usuario debe permitir:
  1. 3c. Ver Catálogo por Artista: Buscar un artista por nombre y listar todos sus
álbumes y canciones.
  2. 3d. Ver Canciones por Álbum: Buscar un álbum por título y listar todas las
canciones asociadas.
  3. 3e. Ver Info Detallada de Canción: Buscar una canción por título y mostrar toda la
información, incluyendo la calificacionPromedio actual.
  4. 3f. Calificar Canción:
○ El usuario logueado busca una canción por título y le asigna una
puntuacion (1 a 5).
○ Se registra una nueva Calificacion.
○ Actualizar Archivo de Canciones: El sistema debe recalcular y actualizar
el campo calificacionPromedio de la canción, promediando todas las
puntuaciones registradas para ese título.
5. 3g. Ver Mis Calificaciones: Listar todas las canciones que el usuario logueado ha
calificado.

IV. Reportes de la Plataforma (Análisis Global) 📊
Ambos menús (Artista y Usuario) deben tener acceso a los reportes:
  1. 3h. Reporte de Top 10 Canciones: Mostrar las 10 canciones con la
calificacionPromedio más alta en toda la plataforma, ordenadas
descendentemente.
2. 3i. Reporte de Álbumes Recientes: Listar todos los álbumes lanzados en el último
año, ordenados por anioLanzamiento.
3. 3j. Reporte de Artista Más Calificado: Identificar y mostrar el nombreArtista
que tiene la mayor cantidad total de calificaciones en todas sus canciones.
4. 3k. Reporte de Usuarios Activos: Mostrar el nicknameUsuario que ha dejado la
mayor cantidad total de calificaciones hasta la fecha.
Requisito Adicional para Promoción
Para que el grupo de desarrollo pueda optar por la promoción de la materia, deberán
proponer e implementar una funcionalidad clave extra por cada miembro del grupo, que
vaya más allá de los requisitos mínimos y mejore significativamente la operación o el
análisis en "Rueda Veloz". Estas funcionalidades deberán ser propuestas por el equipo y
deberán ser el resultado de un análisis crítico de la problemática.
Nota: La funcionalidad debe ser relevante, compleja (requerir el uso integrado de archivos
y estructuras) y debe ser aprobada previamente por el docente. La documentación de esta
funcionalidad y su código serán clave en la evaluación de la promoción.
