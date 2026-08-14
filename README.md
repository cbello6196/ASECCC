ASECCC Digital

Sistema web desarrollado para la gestión integral de servicios y beneficios de los asociados de la Asociación Solidarista ASECCC. La plataforma permite la administración de préstamos, ahorros, aportes,
beneficios, estados de cuenta y gestión de usuarios mediante una interfaz web moderna y segura.

Descripción

ASECCC Digital es una aplicación web desarrollada con ASP.NET MVC y SQL Server, diseñada para digitalizar y optimizar los procesos administrativos de la asociación,
facilitando el acceso a la información tanto para asociados como para administradores.

Características Principales

Módulo de Asociados
Consulta de estado de cuenta personal.
Consulta de ahorros y aportes.
Consulta de préstamos activos.
Visualización de beneficios y servicios.
Actualización de información personal.
Recuperación de contraseña.

Módulo Administrativo
Administración de usuarios.
Gestión de asociados.
Gestión de préstamos.
Administración de ahorros y aportes.
Control de beneficios y servicios.
Generación de estados de cuenta.
Reportes administrativos.
Gestión de solicitudes.

Seguridad
Autenticación de usuarios.
Control de acceso basado en roles.
Protección de datos sensibles.
Gestión segura de sesiones.
Recuperación de credenciales.

Tecnologías Utilizadas

Backend
ASP.NET MVC 5
C#
Entity Framework
SQL Server

Frontend
HTML5
CSS3
Bootstrap
JavaScript
jQuery
SweetAlert2

Infraestructura
Microsoft Azure App Service
Azure SQL Database
GitHub
GitHub Actions (CI/CD)

Roles del Sistema

Administrador

Permite:
Administración de asociados.
Gestión de préstamos.
Administración de ahorros.
Administración de aportes.
Gestión de beneficios.
Generación de reportes.
Gestión de usuarios.

Asociado

Permite:
Consultar estado de cuenta.
Revisar ahorros.
Consultar préstamos.
Visualizar beneficios.
Actualizar datos personales.
Estado de Cuenta

El sistema permite generar estados de cuenta que integran:

Información general del asociado.
Ahorros acumulados.
Aportes realizados.
Préstamos activos.
Beneficios y servicios.
Saldos y movimientos.

También ofrece exportación a PDF para consulta y respaldo.

Despliegue

El sistema se encuentra preparado para ser desplegado en:

Azure App Service

> **Nota:** Este repositorio es un fork del proyecto original de [Ebrenes22](https://github.com/Ebrenes22/ASECCC-Digital). 
> Participé como parte del equipo de desarrollo, contribuyendo en los módulos detallados a continuación.

## Mi aporte en este proyecto

Como parte del equipo de desarrollo de ASECCC Digital, trabajé principalmente en los siguientes módulos:

**Módulo de Ahorros y Aportes**
- Desarrollo del CRUD de administración de ahorros y aportes (HU15)
- Implementación y ajustes del modelo de Ahorros (`AhorroModel`)
- Corrección de historial de aportes y ahorros
- Consulta de aportes por asociado

**Módulo de Préstamos**
- Desarrollo del controlador de Préstamos para roles de Administrador y Asociado
- Actualización del modelo de Préstamos
- Vistas de consulta de préstamos (Admin y Asociado)

**Módulo de Beneficios y Servicios**
- Implementación del módulo de beneficios (estado activo/inactivo)
- Consulta de beneficios y servicios por asociado
- Ajustes visuales y correcciones

**Reportes y Estados de Cuenta**
- Desarrollo del módulo de reportes y estado de cuenta
- Corrección de diseño responsive en tarjetas de reportes

**Otros**
- Notificaciones para el rol de administrador
- Ajustes visuales generales y validaciones del módulo de ahorro
