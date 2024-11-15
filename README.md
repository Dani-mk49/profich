# Registro de Horas y Horarios de Trabajadores

Este proyecto es una herramienta desarrollada en Laravel que permite gestionar el registro de las horas y horarios laborales de los trabajadores. Además, ofrece a los trabajadores la posibilidad de visualizar los días y horarios en los que trabajan.

## 🚀 Características

- **Gestión de horarios:** Permite a los administradores registrar y gestionar las horas trabajadas por cada empleado.
- **Visualización para trabajadores:** Los trabajadores pueden consultar sus horarios y días laborables.
- **Interfaz amigable:** Interfaz intuitiva y fácil de usar.
- **Reportes:** Genera reportes sobre el tiempo trabajado por empleado (opcional, dependiendo del alcance del proyecto).
- **Notificaciones:** Opcionalmente, los trabajadores pueden recibir notificaciones sobre cambios en sus horarios (funcionalidad futura).

## 🛠️ Tecnologías utilizadas

- **Framework principal:** [Laravel](https://laravel.com/) (versión 10.x o superior recomendada).
- **Base de datos:** MySQL / PostgreSQL (configurable).
- **Frontend:** Blade templates, Tailwind CSS o Bootstrap (según preferencia).
- **Autenticación:** Laravel Breeze / Laravel Sanctum (para control de acceso).

## 📋 Requisitos del sistema

- PHP 8.1 o superior
- Composer
- Node.js y npm (para la compilación de activos)
- Servidor web como Apache o Nginx
- Base de datos compatible (MySQL, PostgreSQL, etc.)

## 🔧 Instalación

Sigue estos pasos para configurar y ejecutar el proyecto en tu máquina local.

1. Clona este repositorio:
    ```bash
    git clone https://github.com/tu_usuario/registro-horas-trabajadores.git
    cd registro-horas-trabajadores
    ```

2. Instala las dependencias de PHP con Composer:
    ```bash
    composer install
    ```

3. Copia el archivo de configuración y configura las variables de entorno:
    ```bash
    cp .env.example .env
    ```
    Modifica el archivo `.env` para incluir los datos de tu base de datos y otras configuraciones necesarias.

4. Genera la clave de la aplicación:
    ```bash
    php artisan key:generate
    ```

5. Ejecuta las migraciones para crear las tablas en la base de datos:
    ```bash
    php artisan migrate
    ```

6. (Opcional) Si usas datos de prueba, ejecuta los seeders:
    ```bash
    php artisan db:seed
    ```

7. Instala las dependencias de Node.js y compila los activos:
    ```bash
    npm install
    npm run dev
    ```

8. Inicia el servidor de desarrollo:
    ```bash
    php artisan serve
    ```
    Accede al proyecto en [http://localhost:8000](http://localhost:8000).

## 📘 Uso

1. **Administradores:** 
    - Pueden iniciar sesión y registrar o modificar horarios de los empleados.
    - Consultar reportes de tiempo trabajado.

2. **Trabajadores:**
    - Pueden iniciar sesión para consultar sus horarios asignados.

## 🤝 Contribuciones

¡Contribuciones, problemas y sugerencias son bienvenidas! Para contribuir:

1. Haz un fork del proyecto.
2. Crea una nueva rama con tu funcionalidad o solución de problema:
    ```bash
    git checkout -b feature/nueva-funcionalidad
    ```
3. Realiza los cambios y haz commits descriptivos:
    ```bash
    git commit -m "Añadir nueva funcionalidad"
    ```
4. Sube los cambios a tu fork:
    ```bash
    git push origin feature/nueva-funcionalidad
    ```
5. Abre un pull request en este repositorio.

## 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
