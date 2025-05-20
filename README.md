# Novum RH - Plataforma Web de Gestión de Talento Humano

[![Mantenimiento](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Licencia](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Node.js](https://img.shields.io/badge/Node.js-16.x-brightgreen.svg)
![Express](https://img.shields.io/badge/Express-4.x-blueviolet.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-blue.svg)

## Descripción del Proyecto

**Novum RH** es una aplicación web integral diseñada específicamente para optimizar los procesos de captación y selección de personal en **Novumideas C.A.** Esta plataforma centraliza toda la información relevante del ciclo de vida del talento humano en un único lugar, desde la publicación de vacantes hasta la evaluación de candidatos y la gestión de la información de los empleados.

El objetivo principal de Novum RH es mejorar significativamente la eficiencia en la gestión del talento humano dentro de Novumideas C.A., reduciendo tiempos, minimizando errores y facilitando la toma de decisiones estratégicas basadas en datos precisos y actualizados.

## Funcionalidades Principales

La aplicación Novum RH ofrece las siguientes funcionalidades clave:

* **Gestión de Vacantes:**
    * Creación, edición y publicación de nuevas vacantes con descripción detallada, requisitos y plazos.
    * Seguimiento del estado de cada vacante (abierta, en revisión, cerrada).
    * Integración para la publicación automática en diversos canales (opcional).
* **Gestión de Candidatos:**
    * Recepción y almacenamiento centralizado de currículums y solicitudes.
    * Filtrado y búsqueda avanzada de candidatos por diversas criteria (habilidades, experiencia, etc.).
    * Etiquetado y categorización de candidatos para una mejor organización.
* **Proceso de Selección:**
    * Definición de flujos de trabajo personalizados para cada proceso de selección.
    * Programación y gestión de entrevistas (virtuales y presenciales).
    * Registro y evaluación de resultados de pruebas y entrevistas.
    * Comunicación integrada con los candidatos a través de la plataforma.
* **Base de Datos de Talento:**
    * Creación y mantenimiento de una base de datos centralizada con la información de todos los candidatos y empleados.
    * Historial de postulaciones y evaluaciones de cada individuo.
    * Funcionalidades de búsqueda y generación de informes sobre el talento disponible.
* **Informes y Analíticas:**
    * Generación de informes sobre métricas clave del proceso de captación y selección (tiempo promedio de contratación, fuentes de candidatos más efectivas, etc.).
    * Visualización de datos a través de gráficos y paneles informativos (opcional).
* **Gestión de Usuarios y Permisos:**
    * Sistema de autenticación y autorización para diferentes roles de usuario (RRHH, gerentes, etc.).
    * Control de acceso a las diferentes funcionalidades de la plataforma según el rol.

## Tecnologías Utilizadas

La aplicación Novum RH ha sido desarrollada utilizando las siguientes tecnologías principales:

* **Frontend:**
    * HTML5, CSS3
    * JavaScript (ES6+)
    * Tailwind CSS 3.x
* **Backend:**
    * Node.js 16.x
    * Express 4.x
* **Base de Datos:**
    * [Sistema de Gestión de Base de Datos (ej. PostgreSQL, MySQL, MongoDB)] - *Por favor, especifica cuál utilizaste.*
* **Otros:**
    * [Otras librerías o herramientas relevantes que utilizaste.]

## Instalación

Para ejecutar la aplicación Novum RH en un entorno local, sigue los siguientes pasos:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/sindresorhus/del](https://github.com/sindresorhus/del)
    cd novum-rh
    ```
    *Reemplaza `https://github.com/sindresorhus/del` con la dirección de tu repositorio.*

2.  **Instalar las dependencias del backend (Node.js/Express):**
    ```bash
    npm install
    # o
    yarn install
    ```

3.  **Instalar las dependencias del frontend (Tailwind CSS y otras):**
    *Navega a la carpeta del frontend si está separada.*
    ```bash
    npm install -D tailwindcss postcss autoprefixer
    # o
    yarn add -D tailwindcss postcss autoprefixer
    npx tailwindcss init -p
    ```
    *Configura los archivos de template en `tailwind.config.js`.*

4.  **Configurar la base de datos:**
    * Crea una base de datos según la configuración especificada en el archivo de configuración de tu aplicación (por ejemplo, `.env`).

5.  **Ejecutar las migraciones (si aplica a tu base de datos):**
    ```bash
    # Ejemplo para Sequelize (si lo utilizas con Express)
    npx sequelize-cli db:migrate
    ```

6.  **Ejecutar el servidor de desarrollo:**
    ```bash
    # Ejemplo genérico para Node.js/Express
    npm run dev
    # o
    yarn dev
    # o
    node server.js # o el archivo principal de tu backend
    ```
    * Accede a la aplicación en tu navegador a través de la dirección proporcionada (normalmente `http://localhost:3000` o la configurada en tu backend).*

## Configuración

Describe cualquier configuración adicional que pueda ser necesaria para la aplicación, como variables de entorno (claves de API, configuración de base de datos, etc.), archivos de configuración, etc.

## Uso

Proporciona una breve guía sobre cómo utilizar las funcionalidades principales de la aplicación. Puedes incluir capturas de pantalla si lo consideras útil.

## Contribuciones

Si planeas que otros contribuyan a tu proyecto, explica cómo pueden hacerlo (por ejemplo, a través de pull requests).

## Licencia

Especifica la licencia bajo la cual se distribuye tu aplicación. Por ejemplo: