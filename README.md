# Análisis de Tarifas de Megaline

## Descripción del Proyecto

¡Felicidades por completar la sección de Análisis Estadístico de Datos! En este proyecto, actuarás como analista para Megaline, un operador de telecomunicaciones. El objetivo es determinar qué tarifa prepago genera más ingresos para la empresa: Surf o Ultimate.

Trabajarás con un conjunto de datos de 500 clientes que incluye información sobre llamadas, mensajes de texto y datos de navegación durante el año 2018. Tu tarea es analizar estos datos para evaluar el comportamiento de los clientes y determinar cuál tarifa aporta más ingresos. Además, realizarás pruebas estadísticas para comparar el ingreso promedio de los usuarios en diferentes tarifas y regiones.

## Descripción de las Tarifas

- **Surf**: 
  - Pago mensual: $20
  - Incluye: 500 minutos, 50 SMS, 15 GB de datos
  - Excedentes: 
    - Minuto: $0.03
    - SMS: $0.03
    - GB de datos: $10

- **Ultimate**: 
  - Pago mensual: $70
  - Incluye: 3000 minutos, 1000 SMS, 30 GB de datos
  - Excedentes:
    - Minuto: $0.01
    - SMS: $0.01
    - GB de datos: $7

## Diccionario de Datos

- **users**: Datos sobre los usuarios
  - `user_id`: Identificador único del usuario
  - `first_name`: Nombre del usuario
  - `last_name`: Apellido del usuario
  - `age`: Edad del usuario
  - `reg_date`: Fecha de suscripción
  - `churn_date`: Fecha de cancelación
  - `city`: Ciudad de residencia
  - `plan`: Nombre de la tarifa

- **calls**: Datos sobre las llamadas
  - `id`: Identificador único de la llamada
  - `call_date`: Fecha de la llamada
  - `duration`: Duración de la llamada (en minutos)
  - `user_id`: Identificador del usuario

- **messages**: Datos sobre los SMS
  - `id`: Identificador único del SMS
  - `message_date`: Fecha del SMS
  - `user_id`: Identificador del usuario

- **internet**: Datos sobre las sesiones web
  - `id`: Identificador único de la sesión
  - `mb_used`: Volumen de datos gastados (en megabytes)
  - `session_date`: Fecha de la sesión web
  - `user_id`: Identificador del usuario

- **plans**: Datos sobre las tarifas
  - `plan_name`: Nombre de la tarifa
  - `usd_monthly_fee`: Pago mensual
  - `minutes_included`: Minutos incluidos al mes
  - `messages_included`: SMS incluidos al mes
  - `mb_per_month_included`: Datos incluidos al mes (en megabytes)
  - `usd_per_minute`: Precio por minuto extra
  - `usd_per_message`: Precio por SMS extra
  - `usd_per_gb`: Precio por GB de datos extra

## Instrucciones

### Paso 1: Exploración de Datos
- Abre los archivos de datos (`/datasets/megaline_calls.csv`, `/datasets/megaline_internet.csv`, `/datasets/megaline_messages.csv`, `/datasets/megaline_plans.csv`, `/datasets/megaline_users.csv`).
- Examina la información general de cada tabla.

### Paso 2: Preparación de Datos
- Convierte los datos a los tipos adecuados.
- Identifica y corrige errores en los datos.
- Calcula el número de llamadas, SMS, y datos por mes para cada usuario.
- Calcula los ingresos mensuales para cada usuario.

### Paso 3: Análisis de Datos
- Describe el comportamiento de los usuarios de cada tarifa.
- Calcula la media, varianza y desviación estándar.
- Traza histogramas y describe las distribuciones.

### Paso 4: Pruebas de Hipótesis
- Comparar el ingreso promedio entre tarifas Ultimate y Surf.
- Comparar el ingreso promedio entre usuarios de Nueva York-Nueva Jersey y otras regiones.
- Formula hipótesis nula y alternativa y explica los métodos utilizados para probarlas.

### Paso 5: Conclusión General
- Resume los hallazgos y conclusiones del análisis.

## Archivos del Proyecto

- `/datasets/megaline_calls.csv`
- `/datasets/megaline_internet.csv`
- `/datasets/megaline_messages.csv`
- `/datasets/megaline_plans.csv`
- `/datasets/megaline_users.csv`
