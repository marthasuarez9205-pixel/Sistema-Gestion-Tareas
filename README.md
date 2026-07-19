# Plan de pruebas

## Objetivo

Verificar que el Sistema de Gestión de Tareas funcione correctamente en todas sus funcionalidades.

## Pruebas manuales

- Registro de usuarios
- Inicio de sesión
- Crear tareas
- Editar tareas
- Eliminar tareas
- Buscar tareas
- Cambiar contraseña
- Asignar tareas

## Pruebas automatizadas

- Validación del registro de usuarios
- Validación del inicio de sesión
- Validación de creación de tareas
- Validación de edición
- Validación de eliminación
- Validación del buscador

**Nota:** Estas pruebas automatizadas representan las funcionalidades que se automatizarían una vez el sistema esté completamente desarrollado.

## Casos de prueba

| ID | Funcionalidad | Tipo de prueba | Resultado esperado |
|----|---------------|----------------|--------------------|
| CP-01 | Registro de usuarios | Manual | El usuario se registra correctamente. |
| CP-02 | Inicio de sesión | Manual | El sistema permite el acceso con credenciales válidas. |
| CP-03 | Crear tarea | Manual | La tarea queda almacenada. |
| CP-04 | Editar tarea | Manual | Los cambios se guardan correctamente. |
| CP-05 | Eliminar tarea | Manual | La tarea se elimina del sistema. |
| CP-06 | Validar registro | Automatizada | El proceso de registro funciona sin errores. |
| CP-07 | Validar creación de tareas | Automatizada | La tarea se almacena correctamente. |
| CP-08 | Validar búsqueda | Automatizada | El sistema devuelve los resultados esperados. |
