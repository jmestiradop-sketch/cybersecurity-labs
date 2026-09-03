# 🛡️ Portfolio de Ciberseguridad & Laboratorios Prácticos

## 👤 Perfil Profesional

Entusiasta de la seguridad de la información con sólida experiencia en control de calidad, trazabilidad, gestión de procesos operativos y resolución proactiva de problemas. Comprometido con la protección de datos y el cumplimiento de las normativas vigentes para salvaguardar a las organizaciones frente a amenazas emergentes.

Enfocado en aplicar capacidad analítica y atención al detalle para identificar riesgos de forma temprana, garantizar la continuidad operativa de los entornos tecnológicos y aportar valor en proyectos a largo plazo.

---

## 🛠️ Competencias & Marcos Técnicos

* **Gobernanza, Riesgo y Cumplimiento (GRC):** NIST CSF, PCI DSS, RGPD/GDPR, SOC 1 & 2, ISO 27001.
* **Seguridad Defensiva y Operativa:** Mínimo Privilegio (RBAC), Cifrado (At-Rest / In-Transit), Copias de Seguridad (3-2-1), DRP, IDS/IPS, Firewalls.
* **Gestión de Procesos:** Trazabilidad operativa, auditoría interna de activos, análisis de brechas (*gap analysis*) y mitigación de riesgos.

---

## 📂 Proyectos y Casos Prácticos

### 1. Auditoría de Seguridad, Riesgos y Cumplimiento
* 📋 **[Auditoría Integral y Evaluación de Riesgos - Botium Toys](./Botium_Toys_Auditoria_y_Cumplimiento.md)**
  * **Resumen:** Evaluación exhaustiva del programa de seguridad de una empresa de comercio minorista y electrónico.
  * **Entregables:** Inventario de activos, evaluación de riesgos bajo NIST CSF, listas de verificación de cumplimiento (PCI DSS, RGPD, SOC 1/2) y hoja de ruta de mitigación estructurada en 3 fases.

---

## 📬 Contacto
* **GitHub:** [@jmestiradop-sketch](https://github.com/jmestiradop-sketch)
* **Especialidad:** Seguridad de la Información | Gestión de Riesgos | Auditoría y Procesos

* Análisis del informe de incidentes
* Resumen	Esta mañana, una becaria informó al departamento de TI de que no podía iniciar sesión en su cuenta de la red interna. Los registros de acceso indican que su cuenta ha estado accediendo activamente a registros en la base de datos de clientes, a pesar de que ella tiene bloqueado el acceso a dicha cuenta. La becaria indicó que esta mañana recibió un correo electrónico en el que se le solicitaba acceder a un sitio web externo e iniciar sesión con sus credenciales de la red interna para recuperar un mensaje. Creemos que este fue el método utilizado por un actor malicioso para obtener acceso a nuestra red y a la base de datos de clientes. Otros dos empleados han detectado que faltan varios registros de clientes o que estos contienen datos incorrectos. Todo apunta a que los datos de los clientes no solo quedaron expuestos ante un atacante malicioso, sino que parte de ellos también fueron eliminados o manipulados.
Identificar	El equipo de gestión de incidentes auditó los sistemas, dispositivos y políticas de acceso implicados en el ataque para identificar las brechas de seguridad. El equipo descubrió que el usuario y la contraseña de una becaria fueron obtenidos por un atacante malicioso y utilizados para acceder a datos de nuestra base de datos de clientes. Tras una revisión inicial, parece que parte de los datos de los clientes fueron eliminados de la base de datos.
Proteger	El equipo ha implementado nuevas políticas de autenticación para prevenir futuros ataques: autenticación multifactor (MFA), límite de tres intentos de inicio de sesión y formación para todos los empleados sobre cómo proteger las credenciales de acceso. Además, implementaremos una nueva configuración protectora de firewall e invertiremos en un sistema de prevención de intrusiones (IPS).
Detectar	Para detectar nuevos ataques de acceso no autorizado en el futuro, el equipo utilizará una herramienta de registro de firewall y un sistema de detección de intrusiones (IDS) para monitorizar todo el tráfico entrante desde Internet.
Responder	El equipo deshabilitó la cuenta de red de la becaria. Proporcionamos formación a los becarios y empleados sobre cómo proteger las credenciales de acceso en el futuro. Informamos a la alta dirección de este suceso y ellos se pondrán en contacto con nuestros clientes por correo postal para informarles sobre la brecha de datos. La dirección también deberá notificar a las fuerzas de seguridad y a otros organismos según lo exijan las leyes locales.
Recuperar	El equipo recuperará los datos eliminados restaurando la base de datos a partir de la copia de seguridad completa de anoche. Hemos informado al personal de que cualquier información de clientes introducida o modificada esta mañana no estará registrada en la copia de seguridad. Por lo tanto, deberán volver a introducir esa información en la base de datos una vez que se haya restaurado a partir de la copia de seguridad de la noche anterior.

