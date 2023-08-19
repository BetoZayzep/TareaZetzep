# Zetzep - Sistema de Gestión de Eventos

## Resumen Ejecutivo

### Descripción
Zetzep es una plataforma de gestión de eventos que simplifica la planificación, organización y seguimiento de todo tipo de eventos, desde conferencias hasta fiestas privadas. Nuestra solución se centra en proporcionar a los usuarios una experiencia sin complicaciones para garantizar el éxito de sus eventos.

### Problema Identificado
La organización de eventos puede ser una tarea abrumadora, con problemas comunes como la falta de seguimiento de invitados, dificultades en la coordinación y falta de generación de informes efectivos. Zetzep aborda estos problemas al ofrecer una plataforma integral que los gestiona de manera eficiente.

### Solución
Zetzep ofrece una interfaz de usuario intuitiva que permite a los usuarios gestionar sus eventos de manera efectiva. Nuestra plataforma incluye funcionalidades como el registro de invitados, integración continua para pruebas de calidad, estructura de base de datos sólida para la gestión de datos, documentación completa, generación de informes y diseño de marca personalizado.

### Arquitectura
Zetzep se basa en una arquitectura de tres capas: servidor de aplicación, servidor web y base de datos. Esto garantiza una separación eficiente de la lógica de negocio, la interfaz de usuario y los datos, lo que facilita el mantenimiento y la escalabilidad.

## Tabla de Contenidos

- [Requerimientos](#requerimientos)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Uso](#uso)
- [Contribución](#contribución)
- [Roadmap](#roadmap)

## Requerimientos

### Servidores de Aplicación, Web y Base de Datos
- Servidor de Aplicación: Tomcat 9.0
- Servidor Web: Nginx 1.18
- Base de Datos: PostgreSQL 13.3

### Paquetes Adicionales
- Java 11
- Node.js 14.17
- npm 7.24

### Versión de Java
- Java: OpenJDK 11

## Instalación

### Cómo Instalar el Ambiente de Desarrollo
1. Clona este repositorio: `git clone https://github.com/BetoZayzep/TareaZetzep.git`.
2. Navega a la carpeta del proyecto: `cd TareaZetzep`.
3. Instala las dependencias de Java y Node.js: `npm install`.
4. Configura la base de datos PostgreSQL y crea la base de datos `zetzep`.
5. Ejecuta las migraciones de la base de datos: `npm run migrate`.

### Cómo Ejecutar Pruebas Manualmente
1. Asegúrate de que el ambiente de desarrollo esté configurado.
2. Ejecuta pruebas de unidad: `npm test`.
3. Ejecuta pruebas de integración: `npm run test:integration`.

### Cómo Implementar la Solución en Producción
1. Configura un servidor con Tomcat y Nginx.
2. Configura las variables de entorno para producción.
3. Despliega la aplicación en el servidor de aplicación.
4. Configura Nginx para servir la aplicación en producción.

## Configuración

### Configuración del Producto
- El archivo de configuración principal se encuentra en `config/config.json`. Aquí puedes ajustar la configuración de la aplicación.

### Configuración de Requerimientos
- Asegúrate de que los servidores y paquetes mencionados en los requerimientos estén instalados y configurados correctamente.

## Uso

### Para Usuarios Finales
- Consulta nuestro [Manual del Usuario](#link-al-manual-de-usuario) para obtener instrucciones detalladas sobre cómo utilizar Zetzep para tus eventos.

### Para Usuarios Administradores
- Como administrador, puedes acceder a configuraciones avanzadas y funciones de mantenimiento. Consulta nuestra [Guía del Administrador](#link-a-la-guía-del-administrador) para más detalles.

## Contribución

### Guía de Contribución
1. Clona este repositorio: `git clone https://github.com/BetoZayzep/TareaZetzep.git`.
2. Crea un nuevo branch: `git checkout -b nueva-funcionalidad`.
3. Realiza tus cambios y commit: `git commit -m "Agrega nueva funcionalidad"`.
4. Envía un pull request a la rama `develop`.
5. Espera la revisión y la aprobación antes de hacer el merge.

## Roadmap

### Próximas Funcionalidades
- Integración con servicios de pago.
- Mejoras en la generación de informes.
- Funcionalidades de exportación de datos.
