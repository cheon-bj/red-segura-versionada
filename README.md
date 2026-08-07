# Red segura versionada

Proyecto colaborativo para documentar una red escolar, analizar riesgos básicos y aplicar versionamiento con Git y GitHub.

## Integrantes

- Integrante 1:Brandon Jesús Vite Vite
- Integrante 2:Alex Fernando Bautista Hernándes 
- Integrante 3:Uriel Epifanio Bautista 

## Objetivo

Aplicar Git y GitHub para controlar cambios en documentación técnica de redes y ciberseguridad.

# Red segura versionada

## Descripción

Este proyecto documenta una red escolar simulada y sus controles básicos de seguridad.

## Objetivo técnico

Registrar cambios en configuraciones, inventarios y recomendaciones de seguridad usando Git y GitHub.

## Alcance

La práctica se realiza con datos simulados. No se utilizan IP públicas reales ni credenciales.

## Flujo de trabajo

1. Crear una rama.
2. Realizar cambios.
3. Crear commits.
4. Subir la rama a GitHub.
5. Crear un pull request.
6. Solicitar revisión.
7. Fusionar cambios aprobados.

## Estructura del repositorio

El proyecto está organizado en los siguientes archivos para facilitar la documentación y el control de versiones:

- **README.md:** Contiene la descripción general del proyecto, su objetivo, alcance y flujo de trabajo.
- **inventario_red.md:** Documenta los dispositivos de la red, direcciones IP simuladas y servicios principales.
- **reglas_firewall.md:** Incluye las reglas básicas de firewall propuestas para proteger la red.
- **hardening_servidores.md:** Destinado a documentar recomendaciones de endurecimiento de servidores.
- **incidente_seguridad.md:** Registra un incidente de seguridad simulado y las acciones de mitigación recomendadas.
- **RED-SEGURA-VERSIONADA**: Carpeta donde se almacenan las capturas y evidencias de la práctica.

## Reflexión final

Durante esta práctica aprendimos que Git y GitHub son herramientas útiles no solamente para desarrollar software, sino también para administrar y documentar proyectos de redes y ciberseguridad. El uso del control de versiones nos permitió mantener un historial de los cambios realizados, identificar las modificaciones y trabajar de manera organizada entre los integrantes del equipo.

Trabajar con ramas nos permitió que cada integrante pudiera realizar sus actividades de forma independiente sin modificar directamente la rama principal. Esto facilita la colaboración y reduce el riesgo de afectar información que ya se encuentra establecida en el proyecto.

También comprendimos la importancia de revisar los cambios antes de fusionarlos. Los Pull Requests permiten que otro integrante analice el contenido, realice observaciones y solicite correcciones antes de integrar los cambios en `main`. De esta manera, se mejora la calidad de la documentación y se reducen posibles errores técnicos.

En el área de redes y ciberseguridad, modificar una configuración de firewall, un inventario o una recomendación de seguridad sin conservar un historial podría dificultar la identificación de quién realizó el cambio, qué información fue modificada y cuál era la configuración anterior. Esto puede complicar la solución de problemas, las auditorías y la recuperación ante errores.

Finalmente, aprendimos que GitHub debe utilizarse teniendo en cuenta la seguridad. No se deben subir contraseñas, claves privadas, tokens, credenciales, direcciones IP públicas reales, información personal ni configuraciones sensibles de instituciones. Durante esta práctica utilizamos información simulada para comprender el proceso sin exponer datos reales.

En conclusión, la práctica nos permitió comprender la importancia del control de cambios, la colaboración y la trazabilidad en proyectos tecnológicos. Estos conocimientos pueden aplicarse directamente en la administración de redes, documentación de infraestructura, gestión de configuraciones y procesos de ciberseguridad.
