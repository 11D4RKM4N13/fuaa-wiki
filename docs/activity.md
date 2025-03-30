---
sidebar_position: 2
title: Desarrollo de la actividad
---

# Identificación de la problemática
En el mundo moderno la automatización se ha vuelto una necesidad para las empresas. Está demostrado que las organizaciones que implementan sistemas de manera correcta para apoyar en la administración de sus procesos poseen una ventaja competitiva en el mercado (Begnini Domínguez et al., 2022). Para este trabajo la inobiliaria desea automatizar sus procesos de gestión empresarial apoyandose en la implementación de una herramienta que administre de manera automática los inmuebles con los que trabajan. El principal problema es la necesidad de contar con un sistema de información seguro y eficiente para gestionar inmuebles en alquiler, propietarios e inquilinos en varias ciudades de Colombia.

La problematica principal incluye las siguientes necesidades a ser resueltas:

* Gestión integral del proceso de alquiler: desde la oferta hasta la firma del contrato.
* Automatización de la comunicación con clientes mediante correo y WhatsApp.
* Creación de un sitio web para mostrar inmuebles disponibles con actualizaciones frecuentes.
* Sincronización diaria entre la base de datos y el sitio web.
* Seguridad en el manejo de datos personales y financieros.

Las amenazas digitales a las que se enfrenta la inmobiliaria al implementar esta herramienta también deben ser consideradas como una problemática a tener en cuenta. En el mundo interconectado en el que vivimos constantemente estamos expuestos a ser vulnerados por un atacante o virus informático (Romaniz, n.d.). Esta herramienta contruida para la inmobiliaria debe poseer medidas de seguridad adecuadas que garanticen que el flujo de trabajo no va a verse afectado y que la información de los usuarios estará resguardada de manera segura. 


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

# Referencias

Begnini Domínguez, L., Lecaro LAvayen, A., & Shauri Romero, J. (2022, Julio 15). Ventajas de la automatización de la gestión por procesos. Dialnet. https://dialnet.unirioja.es/descarga/articulo/9043001.pdf

Romaniz, S. C. (n.d.). Seguridad de aplicaciones web: vulnerabilidades en los controles de acceso. Sedici. Retrieved marzo 30, 2025, from https://sedici.unlp.edu.ar/bitstream/handle/10915/21581/1927+-+Seguridad+de+aplicaciones+web+vulnerabilidades+en+los+controles+de+acceso.pdf?sequence=1

