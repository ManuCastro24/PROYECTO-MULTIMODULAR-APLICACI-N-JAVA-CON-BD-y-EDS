# PROYECTO-MULTIMODULAR-APLICACI-N-JAVA-CON-BD-y-EDS

Introducción :
Este manual describe el funcionamiento de la aplicación para gestionar un colegio.

El funcionamiento básico de la aplicación implica la creación y gestión de cursos, así como la matriculación de alumnos y la asignación de profesores a los cursos. A continuación se describen algunas de las operaciones principales:

Crear un Curso: Para crear un curso, con los parámetros adecuados, como el idCurso, el nombre del curso, la capacidad máxima de estudiantes y otros detalles específicos del tipo de curso.

Agregar Alumnos y Profesores: Una vez creado un curso, se pueden agregar alumnos y profesores utilizando los métodos agregarAlumno y agregarProfesor, respectivamente. Estos métodos aseguran que no se exceda la capacidad máxima del curso.

Eliminar un Curso: Cuando un curso ya no es válido o se ha completado, se puede eliminar utilizando el método EliminarCurso, que cambia el estado del curso a "Inactivo" y libera los recursos asociados

Consultar Información: Se pueden consultar detalles sobre los cursos, alumnos y profesores utilizando los métodos toString proporcionados por cada clase, así como otros métodos específicos para obtener información detallada.

La base de datos del colegio proporciona una estructura flexible para gestionar información sobre los cursos, alumnos y profesores. Con las clases y relaciones definidas, es posible llevar a cabo operaciones como la creación de cursos, la matriculación de alumnos y la asignación de profesores de manera eficiente y organizada.
