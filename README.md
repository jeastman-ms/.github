# Microservicios

En esta Organiazión se agrupa un conjunto de repositorios con los recursos necesarios para desplegar un proyecto desarrollado en microservicios para un Sistema Minimalista (API RESTful) de Facturación.

## Requisitos Técnicos
* Cada Microservicio tendrá su propia base de datos independiente
* Cada Microservicio deberá contener su proprio Dockerfile para poder desplegarse en un orquestador Docker tipo Kubernetes o similar
* Deberá existir un repositorio con el docker-compose.yaml para orquestar todos los microservicios, Base de Datos y demás artefactos requeridos
* Debe existir un servicio Proxy Inverso con nginx para todos los microservicios

El proyecto en general estará integrado por los Microservicios:

* Usuarios
* Categorías
* Productos
* Ventas

**Usuario:** Este micro servicio servirá para gestionar los usuarios, los permisos y autoizaciones de los usuarios.
**Categorías:** Este micro servicio servirá para gestionar las categorías de los productos.
**Productos:** Este micro servicio servirá para gestionar los productos.
**Ventas:** Este micro servicio servirá para gestionar las ventas.

