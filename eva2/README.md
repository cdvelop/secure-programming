# Instrucciones Evaluación 2 

## repositorio github.com (5 pts)
**Instrucciones:** 
- cree un repositorio en su cuenta github.com con el nombre
eva2-prog-seg ej: *github.com/suNombreCuenta/eva2-prog-seg* (5 pts)
donde subirá de forma manual sus respuestas de los ejercicios que a continuación se mencionan 
informe a su profesor el nombre de su repositorio para agregarlo al listado enviándolo al correo:
- *CESAR.SOLISC@correoaiep.cl*

```go
var students = map[string]string{
    "Benjamin Arturo Uribe Sanhueza":       "https://github.com/benjaminaxl",
    "Catalina Constanza Toledo Mora":       "https://github.com/cataanza",
    "Daniel Esteban Romero Labra":          "https://github.com/98Danny11",
    "Diego Nicolas Gonzalez Fuentes":       "https://github.com/Chicledot",
    "Eslaen Rafael Martorell Segura":       "https://github.com/Eslaen-Jr",
    "Francisco Javier Villa Faundez":       "https://github.com/Villata-dev",
    "Jose Ignacio Chavez Leiva":            "https://github.com/J-Ignacio",
    "Jose Manuel Aylwin Troncoso":          "https://github.com/CivilizedMage",
    "Juan Alirio Beleño":                   "https://github.com/Juanb7737",
    "Luis Gustavo Zañartu Otarola":         "https://github.com/luisgustavoza",
    "Pedro Jose Flores Medina":             "https://github.com/pfloresmed",
    "Sebastian Etienne Olivera Gonzalez":   "https://github.com/sebastian-olivera",
}
```
## 1- OWASP y programación segura (30 pts)
**Instrucciones:** 
- vea y interactué con el contenido owasp del link (semana 2):
https://www.aiepvirtual.cl/bbcswebdav/xid-134337512_1

- lea el documento pdf sobre owasp

https://www.aiepvirtual.cl/ultra/courses/_408987_1/outline/edit/document/_11585377_1?courseId=_408987_1&view=content

- responda con sus propias palabras en un documento markdown con el formato:
nombre-apellido-eva2-owasp.md el siguiente cuestionario con lo que comprendió sobre owasp:

**Preguntas:**

1. ¿Qué es OWASP y cuál es su principal objetivo? (3 pts)

    * OWASP (Open Web Application Security Project) es una organización sin fines de lucro dedicada a mejorar la seguridad del software. Su objetivo es hacer la seguridad del software visible para que individuos y organizaciones tomen decisiones informadas.

2. ¿Qué es el OWASP Top 10 y por qué es importante para los desarrolladores? (4 pts)

    * El OWASP Top 10 es un documento que lista los diez riesgos de seguridad más críticos en aplicaciones web. Es importante porque ayuda a los desarrolladores a comprender y mitigar las vulnerabilidades más comunes.

3. Describe brevemente dos de las vulnerabilidades del OWASP Top 10 2017. (4 pts)

    * (El alumno debe describir dos vulnerabilidades *diferentes*. Ejemplos:)
        * **Inyección:** Ocurre cuando se envían datos no confiables a un intérprete como parte de un comando o consulta.
        * **Pérdida de Autenticación:**  Cuando las funciones de autenticación y gestión de sesiones son implementadas incorrectamente, permitiendo a los atacantes comprometer cuentas de usuario.

        * **Exposición de Datos Sensibles:** Cuando no se protegen adecuadamente datos confidenciales como contraseñas, números de tarjetas de crédito o información personal.
        
        * **Entidades Externas XML (XXE):** Ocurre cuando se procesan documentos XML mal configurados, permitiendo ataques de revelación de datos o denegación de servicio.
        
        * **Control de Acceso Defectuoso:** Cuando las restricciones sobre lo que los usuarios autenticados pueden hacer no se aplican correctamente.
        
        * **Configuración de Seguridad Incorrecta:** Configuraciones predeterminadas inseguras, directorios incompletos o temporales, errores de configuración del servidor.
        
        * **Secuencia de Comandos en Sitios Cruzados (XSS):** Cuando la aplicación incluye datos no confiables sin validación o codificación apropiada.
       
        * **Deserialización Insegura:** Cuando se procesan objetos serializados de fuentes no confiables, permitiendo la ejecución remota de código.
       
        * **Uso de Componentes con Vulnerabilidades Conocidas:** Uso de bibliotecas, frameworks u otros componentes de software con vulnerabilidades conocidas.
        
        * **Registro y Monitoreo Insuficientes:** Falta de monitoreo adecuado y registro de actividades que podrían detectar ataques en progreso.
        

4. ¿Qué es OWASP ASVS y cuáles son sus niveles de verificación? (4 pts)

    * OWASP ASVS (Application Security Verification Standard) es un estándar para verificar la seguridad de las aplicaciones web. Define tres niveles: 1. Oportunista, 2. Estándar, y 3. Avanzado, cada uno con mayor profundidad en la verificación.

5. ¿Cuál es la diferencia entre los niveles 1 y 3 de OWASP ASVS? (4 pts)

    * El Nivel 1 es un nivel básico para cualquier software, mientras que el Nivel 3 es el más alto y se reserva para aplicaciones críticas que requieren la máxima seguridad. El Nivel 3 implica un análisis mucho más exhaustivo.


6. ¿Qué es el modelado de amenazas y cuáles son sus beneficios? (4 pts)

    * Es un proceso para identificar amenazas, ataques, vulnerabilidades y contramedidas que podrían afectar una aplicación.  Ayuda a mejorar el diseño, cumplir objetivos de seguridad y reducir riesgos.


7. Nombra dos metodologías de modelado de amenazas. (3 pts)

    * STRIDE, DREAD, PASTA, VAST, TRIKE, OCTAVA, NIST. (El alumno debe nombrar dos).

8. ¿Qué es el SDL y cómo ayuda a la seguridad del software? (4 pts)
    * SDL (Security Development Lifecycle) es un proceso de Microsoft para integrar la seguridad en el ciclo de vida del desarrollo de software. Ayuda a reducir el número y la gravedad de las vulnerabilidades.


Total: 30 pts


## 2- Vulnerabilidades y exposiciones comunes CVE - CVSS y otros (15 pts)
**Instrucciones:** 
- vea y interactué con el contenido Vulnerabilidades y exposiciones comunes del link (semana 3):
https://www.aiepvirtual.cl/bbcswebdav/xid-135460483_1

- lea el documento descargable pdf sobre  CVE - CVSS y otros (semana 3):

https://www.aiepvirtual.cl/ultra/courses/_408987_1/outline/edit/document/_11585380_1?courseId=_408987_1&view=content

- responda con sus propias palabras en un documento markdown con el formato:
nombre-apellido-eva2-cvss.md el siguiente cuestionario con lo que comprendió:

**Preguntas:**

1. Define vulnerabilidad, amenaza y riesgo en el contexto de la seguridad informática. (2)

    * **Vulnerabilidad:** Debilidad o fallo en un sistema que pone en riesgo la seguridad.
    * **Amenaza:** Acción que aprovecha una vulnerabilidad para atentar contra la seguridad.
    * **Riesgo:** Probabilidad de que se materialice una amenaza.

2. ¿Qué es CVE y cuál es su propósito? (1)

    * CVE (Common Vulnerabilidades and Exposures) es una lista estandarizada de nombres para vulnerabilidades de seguridad conocidas. Su propósito es facilitar la identificación y el intercambio de información sobre vulnerabilidades.

3. Menciona tres ventajas del uso de CVE. (1)

    * Facilita la identificación de vulnerabilidades conocidas.
    * Permite diferenciar vulnerabilidades.
    * Base de datos en constante actualización.

4. ¿Qué es CVSS y para qué se utiliza? (1)

    * CVSS (Common Vulnerability Scoring System) es un sistema para cuantificar la severidad de una vulnerabilidad en una escala de 0 a 10.

5. Describe los tres grupos métricos del CVSS. (1)

    * **Base:** Características intrínsecas de la vulnerabilidad.
    * **Temporal:** Características que cambian en el tiempo (opcional).
    * **Ambiental:** Características específicas del entorno del usuario.

6. Explica el concepto de "componentes con vulnerabilidades conocidas" (OWASP A9:2017). (1)

    * Se refiere al uso de componentes de software (bibliotecas, frameworks) que tienen vulnerabilidades conocidas.  Explotar estas vulnerabilidades puede comprometer la aplicación.

7. ¿Qué es la encriptación y cuál es su objetivo? (1)

    * La encriptación convierte la información en ilegible para protegerla de accesos no autorizados. Su objetivo es asegurar que solo usuarios autorizados puedan acceder a la información.

8. ¿Qué significan las siglas SOAP, WS y XML? (1)
   
    * SOAP: Simple Object Access Protocol.
    * WS: Web Services.
    * XML: Extensible Markup Language.

9. ¿Qué es hardening y cómo se relaciona con la seguridad de sistemas? (2)

    * Hardening es el proceso de asegurar un sistema reduciendo su superficie de vulnerabilidad. Se relaciona con la seguridad al minimizar los puntos de acceso para posibles ataques.

10. Describe 3 acciones comunes de hardening. (2)

        * Mantener el software actualizado, eliminar software innecesario, cerrar puertos no utilizados, configurar firewalls, establecer políticas de contraseñas robustas,  encriptar datos, establecer roles de usuario. (El alumno debe describir tres).

11. ¿Qué es un CAPTCHA y cuál es su función? (1)

    * Un CAPTCHA es un test para distinguir humanos de ordenadores.  Sirve para prevenir el abuso de servicios por parte de bots.

12. ¿Qué se entiende por "autenticación robusta centralizada"? (1)

    * Es un sistema de autenticación que requiere al menos dos factores para verificar la identidad del usuario, aumentando la seguridad.

Total: 15 puntos


## Las Tres Bases de la Seguridad Informática (10 pts)
**Instrucciones:** 

vea el video y responda según lo comprendido en un fichero markdown
con formato:
nombre-apellido-eva2-3bsi.md

https://www.aiepvirtual.cl/ultra/courses/_408987_1/outline/edit/document/_11585384_1?courseId=_408987_1&view=content

**Preguntas:**

1. ¿Cuáles son los tres pilares de la seguridad informática y qué significan? (3 pts)

    * Confidencialidad: Solo personal autorizado accede a la información.
    * Integridad: La información es precisa y no ha sido alterada.
    * Disponibilidad: La información está accesible cuando se necesita.

2. ¿Qué diferencia hay entre datos e información? (1 pts)

    * Datos: Valores en bruto sin procesar (números, texto, etc.).
    * Información: Datos procesados y organizados que tienen significado y utilidad.

3. Describe una medida para garantizar la confidencialidad. (2 pts)

    * Cifrado de la información, autenticación de usuarios, asignación de privilegios.

4. ¿Por qué es importante la integridad de la información? (2 pts)

    * Porque trabajar con información errónea puede llevar a malas decisiones y ser tan perjudicial como perderla.

5. Menciona un ejemplo de cómo se puede ver afectada la disponibilidad de la información. (2 pts)

    * Un ataque DDoS, un fallo de hardware, un error de software,  correo electrónico bloqueado en listas negras.

## PCI DSS (10 pts)
**Instrucciones:** 
vea el Video complementario semana 2: PCI – DSS. Qué es PCI DSS. 12 requisitos de seguridad y la norma. link:
https://www.aiepvirtual.cl/ultra/courses/_408987_1/outline/edit/document/_11585378_1?courseId=_408987_1&view=content

responda las siguientes preguntas con tus propias palabras, explicando lo que ha entendido sobre el tema en un fichero markdown
con formato:
nombre-apellido-eva2-pci-dss.md

**Preguntas:**

1. ¿Qué significa PCI DSS y cuál es su propósito principal? (3 pts)

   * PCI DSS significa Estándar de Seguridad de Datos para la Industria de Tarjetas de Pago. Su propósito principal es proteger los datos de las tarjetas de pago y prevenir el fraude, estableciendo un conjunto de estándares de seguridad para las empresas que manejan esta información.

2. ¿A qué tipo de empresas afecta PCI DSS? (2 pts)

    *  Afecta a *cualquier* empresa que procesa, almacena o transmite datos de tarjetas de pago. Esto incluye bancos, comercios online, y cualquier otra empresa involucrada en el manejo de estos datos, sin importar el tamaño o el método de almacenamiento (local o en la nube).

3. Menciona tres ejemplos de datos que PCI DSS busca proteger. (2 pts)

    * Número de tarjeta, fecha de vencimiento, código de seguridad (CVV), nombre del titular,  y cualquier información sensible de autenticación.

4. ¿Por qué es importante la certificación PCI DSS para las empresas? (1 pts)

    * Demuestra el compromiso de la empresa con la seguridad de los datos de los clientes, genera confianza y  evita posibles sanciones, multas y la pérdida de permisos para procesar pagos con tarjeta.

5. Describe brevemente tres de los doce requisitos de PCI DSS. (2 pts)

   1. **Firewall:** Instalar, configurar y mantener un firewall para proteger el entorno donde se almacenan los datos de las tarjetas.

   2. **Contraseñas:** No usar contraseñas predeterminadas de fábrica en los sistemas.

   3. **Protección de datos almacenados:** Proteger los sistemas que almacenan datos de tarjetas.

   4. **Cifrado de transmisiones:** Cifrar la transmisión de datos de tarjetas a través de redes públicas.

   5. **Antivirus y Anti-malware:** Utilizar y mantener actualizados software antivirus y anti-malware.

   6. **Desarrollo seguro de sistemas:** Desarrollar y mantener sistemas seguros.

   7. **Control de acceso:** Restringir el acceso a los datos a las personas autorizadas y registrar todos los accesos.

   8. **Autenticación única:** Implementar credenciales de acceso únicas para cada usuario.

   9. **Acceso físico:** Restringir el acceso físico a los datos de las tarjetas.

   10. **Monitorización y rastreo:** Monitorizar y rastrear el acceso a la red y a los datos de las tarjetas.

   11. **Pruebas de seguridad:** Realizar pruebas de seguridad regulares.

   12. **Política de seguridad:** Mantener una política de seguridad de la información para toda la empresa.

Total: 10 pts


# RESTRICCIONES
- puede subir el contenido como fecha limite lunes 11 de noviembre 11:59:59 a su repositorio

NOTAS EVA2:
https://docs.google.com/spreadsheets/d/17nGYcb7Q2C3TTYVD1sqMlB4HhRsKCEBsJNtX-QYWQQA/edit?usp=sharing
