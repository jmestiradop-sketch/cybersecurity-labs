# 🛡️ Portfolio de Ciberseguridad & Laboratorios Prácticos

## 👤 Perfil Profesional

Entusiasta de la seguridad de la información con sólida experiencia en control de calidad, trazabilidad, gestión de procesos operativos y resolución proactiva de problemas. Comprometido con la protección de datos y el cumplimiento de las normativas vigentes para salvaguardar a las organizaciones frente a amenazas emergentes.

Enfocado en aplicar capacidad analítica y atención al detalle para identificar riesgos de forma temprana, garantizar la continuidad operativa de los entornos tecnológicos y aportar valor en proyectos a largo plazo.

---

## 🛠️ Competencias & Marcos Técnicos

* **Gobernanza, Riesgo y Cumplimiento (GRC):** NIST CSF, PCI DSS, RGPD/GDPR, SOC 1 & 2, ISO 27001.
* **Seguridad Defensiva y Operativa:** Mínimo Privilegio (RBAC), Cifrado (At-Rest / In-Transit), Copias de Seguridad (3-2-1), DRP, IDS/IPS, Firewalls.
* **Gestión de Procesos:** Trazabilidad operativa, auditoría interna de activos, análisis de brechas (*gap analysis*) y mitigación de riesgos.

## 📬 Contacto
* **GitHub:** [@jmestiradop-sketch](https://github.com/jmestiradop-sketch)
* **Especialidad:** Seguridad de la Información | Gestión de Riesgos | Auditoría y Procesos
---

* ## 📂 Proyectos y Casos Prácticos

### 1. Auditoría de Seguridad, Riesgos y Cumplimiento
* 📋 **[Auditoría Integral y Evaluación de Riesgos - Botium Toys](Botium_Toys_Evaluacion_de_Riesgos.pdf)**
  * **Resumen:** Evaluación exhaustiva del programa de seguridad de una empresa de comercio minorista y electrónico.
  * **Entregables:** Inventario de activos, evaluación de riesgos bajo NIST CSF, listas de verificación de cumplimiento (PCI DSS, RGPD, SOC 1/2) y hoja de ruta de mitigación estructurada en 3 fases.


* 🐧 **[Gestión y Auditoría de Permisos de Archivo en Linux](Utilizar%20los%20comandos%20de%20Linux%20para%20gestionar%20los%20permisos%20de%20archivo.pdf)**
  * **Resumen:** Auditoría técnica y corrección de permisos de acceso en entornos Linux (CLI) aplicando el principio de mínimo privilegio en el directorio `/home/researcher2/projects`.
  * **Entregables:** Inspección de cadenas de permisos y ficheros ocultos (`ls -la`, `ls -ld`), revocación de permisos no autorizados en archivos confidenciales (`chmod`), y restricción de privilegios de ejecución en directorios para mitigar riesgos de modificación o fuga de datos.


* 📄 **[Marco de ciberseguridad del NIST](Analisis_del_informe_de_incidentes.pdf)**
  * **Resumen:** Análisis y respuesta a incidentes de seguridad estructurados bajo las directrices del marco NIST CSF.

### 2. Seguridad Operativa y Análisis de Registros (Logs)
* 🔍 **[Aplicar Filtros a Consultas SQL - Investigación de Incidentes e Inventario](Aplicar_filtros_a_consultas_SQL_PORTFOLIO.pdf)**
  * **Resumen:** Análisis de eventos de seguridad y gestión del inventario de dispositivos mediante consultas SQL en MariaDB para investigar actividades sospechosas de inicio de sesión y planificar despliegues de parches[cite: 13, 15].
  * **Entregables:**
    * **Filtrado tras horario laboral:** Detección de 19 intentos fallidos después de las 18:00 mediante `login_time > '18:00' AND success = FALSE`[cite: 15].
    * **Auditoría temporal:** Identificación de conexiones sospechosas en fechas específicas combinando operadores condicionales `login_date = '2022-05-09' OR login_date = '2022-05-08'`[cite: 15].
    * **Exclusión geográfica:** Aislamiento de accesos internacionales fuera de México empleando coincidencia por patrones con `country NOT LIKE 'MEX%'`[cite: 15].
    * **Gestión de actualizaciones en endpoints:** Segmentación de equipos por departamento y edificio (`Marketing AND office LIKE 'East-%'`), agrupación interdepartamental (`Finance OR Sales`) y selección del personal excluyendo a TI (`NOT department = 'Information Technology'`)[cite: 13, 15].
