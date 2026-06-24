

##  ULLOA TATÚ
Ulloa Tatú es un local ubicado en el barrio Villa del Río, dedicado a la venta de accesorios y a la realización de tatuajes y piercings, ofreciendo un servicio seguro, profesional y de calidad.

##  Justificación
Actualmente, el local presenta dificultades en la organización de citas y en el control administrativo. No se lleva un registro completamente claro de las ventas ni de los ingresos económicos, lo que puede generar confusiones y desorden en la gestión diaria. Por esta razón, se propone implementar un sistema de agendación de citas que permita una mejor organización para el dueño, los trabajadores y los clientes, brindando mayor seguridad y claridad al momento de reservar.

Asimismo, se plantea desarrollar una página donde los clientes puedan especificar el tipo de tatuaje o piercing que desean realizarse. Esto permitirá al tatuador revisar con anticipación cada solicitud, preparar los materiales necesarios y optimizar el tiempo de trabajo, mejorando así la eficiencia y el servicio general del local.

##  Características
- Ubicación en el barrio Villa del Río

- Venta de accesorios: piercings, anillos, collares, aretes y expansiones

- Servicio profesional de tatuajes y perforaciones

- Atención personalizada y administración organizada

- Cumplimiento de normas de higiene y bioseguridad

- Materiales y equipos en óptimas condiciones

- Implementación de sistema de agendación de citas

- Mejor control de ventas e ingresos económicos

- Propuesta de página informativa para definir servicios solicitados


##  Stack Tecnológico

### Backend & Web
*   **Lenguaje:** PHP 8.x
*   **Framework:** [Laravel](https://laravel.com/)
*   **Base de Datos:** MySQL
*   **Servidor Local:** Laravel Herd

### Mobile
*   **Lenguaje:** Kotlin
*   **Entorno:** Android Studio
*   **Comunicación:** Volley (Consumo de API REST)
*   **Procesamiento de Imágenes:** Base64 encoding/decoding

---


##  Arquitectura de Comunicación (API REST)
El sistema utiliza una arquitectura desacoplada donde la App Móvil consume servicios expuestos por Laravel:

| Método | Endpoint | Descripción |
| :--- | :--- | :--- |
| `GET` | `/api/caracteristicas` |Lista categorías. |
| `POST` | `/api/producto` | Registrar Producto. |
| `POST` | `/api/ventas` | Registar Venta. |

---


##  Instalación y Configuración

### Requisitos
*   PHP >= 8.1
*   Composer
*   Laravel Herd o XAMPP
*   Android Studio (para la App)

