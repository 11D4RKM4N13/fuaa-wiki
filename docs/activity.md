---
sidebar_position: 2
title: Desarrollo de la actividad
---

# Identificación de la problemática
El principal problema es la necesidad de contar con un sistema de información seguro y eficiente para gestionar inmuebles en alquiler, propietarios e inquilinos en una agencia inmobiliaria con presencia en varias ciudades de Colombia.
Dentro del problema principal también se encuentran otros problemas como:

* Gestión integral del proceso de alquiler: desde la oferta hasta la firma del contrato.
* Automatización de la comunicación con clientes mediante correo y WhatsApp.
* Creación de un sitio web para mostrar inmuebles disponibles con actualizaciones frecuentes.
* Sincronización diaria entre la base de datos y el sitio web.
* Seguridad en el manejo de datos personales y financieros.


# Esquematización del problema

Como ingenieros recomendamos crear un diagrama que refleje la relación entre los diferentes actores del sistema y los procesos involucrados, por ejemplo:

* **Usuarios**: administradores, propietarios, inquilinos
* **Módulos**: gestión de inmuebles, gestión de contratos, gestión de usuarios, comunicación.

# Análisis de riesgos

|Riesgo|Impacto|Probabilidad|Mitigación|
|------|-------|------------|----------|
| Perdida de datos | Alto | Medio | Respaldo frecuentes, almacenamiento en la nube |
| Acceso no autorizado | Alto | Alto | Autenticación de dos factores, control de roles |
| Vulnerabilidades web | Alto | Medio | Pruebas de seguridad, HTTPS, Validación de entradas |
| Fallos en la sincronización web | Medio | Medio | Monitoreo de procesos y alertas automáticas |
| Errores en la automatización de notificaciones | Bajo | Medio | Logs y pruebas previas al despliegue |

# Plan de acción

| Acción | Descripción |
|--------|-------------|
| Autenticación segura | Implementar JWT y autenticación de dos factores |
| Control de acceso | Definición de roles y permisos |
| Monitoreo y auditoría | Logs de actividad y alertas de seguridad |
| Pruebas de seguridad periodicas | Pentesting y revisiones de código |
| Cifrado de datos sensibles | Uso de algortimos de cifrado como AES-256 y encriptación en tránsito con HTTPS |

# Recomendaciones de Ciberseguridad

1. Actualizar constantemente las dependencias del sistemas.
2. Aplicar políticas de contraseñas seguras.
3. Implementar Firewalls y protección contra ataques DDoS
4. Uso de VPN y protocolos seguros para acceso remoto
5. Realizar capacitaciones de seguridad para los empleados de la agencia

# Conclusiones

El desarrollo del sistema de información para la agencia inmobiliaria representa un desafío técnico y de seguridad que hemos abordado mediante un enfoque estructurado y basado en buenas prácticas de ingeniería de software. A lo largo del proyecto, identificamos los principales riesgos asociados, como la pérdida de datos, el acceso no autorizado y las vulnerabilidades web, proponiendo estrategias de mitigación efectivas, incluyendo autenticación segura, cifrado de datos y pruebas de seguridad periódicas.
Asimismo, implementamos un plan de acción orientado a garantizar la disponibilidad, integridad y confidencialidad de la información, asegurando un sistema eficiente, escalable y alineado con las necesidades del negocio. La automatización de la comunicación con clientes y la integración de un sitio web actualizado refuerzan la operatividad del sistema y mejoran la experiencia del usuario.
Finalmente, destacamos la importancia de adoptar medidas de ciberseguridad continuas, como la actualización de dependencias, el uso de firewalls y VPNs, y la capacitación del personal en buenas prácticas de seguridad. Con esta solución, no solo optimizamos la gestión inmobiliaria, sino que también garantizamos un entorno confiable para todos los actores involucrados en el proceso.
