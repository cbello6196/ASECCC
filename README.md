# ASECCC Digital

> **Este repositorio es un fork** del proyecto original de [Ebrenes22](https://github.com/Ebrenes22/ASECCC-Digital), quien lidera y mantiene el desarrollo activo de la plataforma.
> Participé como parte del equipo durante el desarrollo, aportando en los módulos detallados abajo.

## Mi aporte en este proyecto

Como parte del equipo de desarrollo de ASECCC Digital, trabajé principalmente en:

- **Módulo de Ahorros y Aportes:** CRUD de administración (HU15), modelo de Ahorros, corrección de historial, consulta de aportes por asociado.
- **Módulo de Préstamos:** controlador para roles Administrador y Asociado, actualización del modelo, vistas de consulta.
- **Módulo de Beneficios y Servicios:** implementación de estado activo/inactivo, consulta por asociado, ajustes visuales.
- **Reportes y Estados de Cuenta:** desarrollo del módulo de reportes, corrección de diseño responsive.
- **Otros:** notificaciones para administrador, ajustes visuales y validaciones del módulo de ahorro.

---

Sistema web desarrollado para la gestión integral de servicios y beneficios de los asociados de la Asociación Solidarista ASECCC. La plataforma permite la administración de préstamos, ahorros, aportes,
beneficios, estados de cuenta y gestión de usuarios mediante una interfaz web moderna y segura.

## Descripción
ASECCC Digital es una aplicación web desarrollada con ASP.NET MVC y SQL Server, diseñada para digitalizar y optimizar los procesos administrativos de la asociación,
facilitando el acceso a la información tanto para asociados como para administradores.

## Características Principales

### Módulo de Asociados
- Consulta de estado de cuenta personal.
- Consulta de ahorros y aportes.
- Consulta de préstamos activos.
- Visualización de beneficios y servicios.
- Actualización de información personal.
- Recuperación de contraseña.

### Módulo Administrativo
- Administración de usuarios.
- Gestión de asociados.
- Gestión de préstamos.
- Administración de ahorros y aportes.
- Control de beneficios y servicios.
- Generación de estados de cuenta.
- Reportes administrativos.
- Gestión de solicitudes.

## Seguridad
- Autenticación de usuarios.
- Control de acceso basado en roles.
- Protección de datos sensibles.
- Gestión segura de sesiones.
- Recuperación de credenciales.

## Tecnologías Utilizadas

### Backend
- ASP.NET MVC 5
- C#
- Entity Framework
- SQL Server

### Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript
- jQuery
- SweetAlert2

### Infraestructura
- Microsoft Azure App Service
- Azure SQL Database
- GitHub
- GitHub Actions (CI/CD)

## Roles del Sistema

### Administrador
Permite:
- Administración de asociados.
- Gestión de préstamos.
- Administración de ahorros.
- Administración de aportes.
- Gestión de beneficios.
- Generación de reportes.
- Gestión de usuarios.

### Asociado
Permite:
- Consultar estado de cuenta.
- Revisar ahorros.
- Consultar préstamos.
- Visualizar beneficios.
- Actualizar datos personales.

## Estado de Cuenta
El sistema permite generar estados de cuenta que integran:
- Información general del asociado.
- Ahorros acumulados.
- Aportes realizados.
- Préstamos activos.
- Beneficios y servicios.
- Saldos y movimientos.

También ofrece exportación a PDF para consulta y respaldo.

## Despliegue
El sistema se encuentra preparado para ser desplegado en:
- Azure App Service
