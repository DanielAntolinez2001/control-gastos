# Control de Gastos

## Integrantes del Grupo
- Daniel Fernando Antolinez
- Sergio Andres Alzate 

## Endpoints Utilizados

### Autenticación
- `POST register`: Registra un nuevo usuario.
- `POST login`: Inicia sesión con un usuario existente.
- `POST /refresh_token`: Refresca el token de autenticación.
- `GET /secret`: Accede a información secreta (requiere autenticación).
- `GET /notsecret`: Accede a información no secreta (no requiere autenticación).

### Ingresos
- `GET /ingresos`: Obtiene una lista de todos los ingresos.
- `GET /ingresos/{id}`: Obtiene información de un ingreso específico.
- `POST /ingresos`: Crea un nuevo ingreso.
- `PUT /ingresos/{id}`: Actualiza información de un ingreso específico.
- `DELETE /ingresos/{id}`: Elimina un ingreso específico.

### Egresos
- `GET /egresos`: Obtiene una lista de todos los egresos.
- `GET /egresos/{id}`: Obtiene información de un egreso específico.
- `POST /egresos`: Crea un nuevo egreso.
- `PUT /egresos/{id}`: Actualiza información de un egreso específico.
- `DELETE /egresos/{id}`: Elimina un egreso específico.

### Reportes
- `GET reporte/simple`: Obtiene un reporte simple de ingresos y egresos.
- `GET /reporte/ampliado`: Obtiene un reporte detallado de ingresos y egresos.
