[Volver al índice general](../README.md)

# UD1 – Análisis del entorno y detección de necesidades tecnológicas

## Índice de apartados

- [ ] **1. Análisis del sector tecnológico**
- [ ] **2. Selección de la empresa o contexto de trabajo**
- [ ] **3. Identificación de necesidades tecnológicas**
- [ ] **4. Oportunidades y viabilidad del proyecto**
- [ ] **5. Obligaciones legales y normativas**
- [ ] **6. Guion inicial del proyecto**

## 1. Análisis del sector tecnológico y del entorno

El proyecto se enmarca dentro del **sector agroalimentario**, concretamente en la industria del **aceite y su envasado**, donde se sitúa la empresa Sovena (planta de Brenes). Este sector representa uno de los pilares industriales de España, tanto por volumen de producción como por su peso en exportaciones y empleo. La creciente competencia internacional, la globalización y la necesidad de garantizar altos estándares de calidad y trazabilidad han impulsado una transición progresiva hacia la **modernización tecnológica**.

En este contexto, el sector agroalimentario avanza hacia la adopción de tecnologías de la información orientadas a mejorar la productividad, el control de procesos y la seguridad. Entre las tendencias más destacadas se encuentran la automatización industrial, la digitalización de datos, la integración de sistemas ERP, la trazabilidad informatizada, el control de accesos digital y los sistemas de monitorización en red. Sin embargo, la transformación digital no es uniforme: muchas empresas del sector todavía presentan carencias en áreas como la seguridad de la red interna, la organización del personal, la integración de sistemas o la gestión eficiente de la información.

El análisis del entorno comprende dos dimensiones principales. Por un lado, el **macroentorno**, que incluye factores económicos, tecnológicos, legislativos, sociales y medioambientales que influyen en el funcionamiento del sector. Por otro lado, el **microentorno**, compuesto por elementos propios del sector: proveedores, competencia, regulación alimentaria y sanitaria, logística y la necesidad de maximizar la eficiencia operativa. Dentro de esta dinámica, los factores clave del sector son la mejora continua de procesos, el control exhaustivo de la calidad, la trazabilidad obligatoria, la gestión eficaz del personal y el cumplimiento de estrictas normativas.

La estructura organizativa y operativa de Sovena —con líneas de producción, almacenes, oficinas, sistemas de control de acceso y trabajadores distribuidos en múltiples turnos— refleja fielmente los retos tecnológicos propios del sector. Este entorno permite identificar necesidades tecnológicas relacionadas con la gestión de personal, la coordinación de turnos, la seguridad informática, la integración de sistemas y la mejora de la infraestructura digital. En consecuencia, Sovena constituye un escenario especialmente adecuado para analizar oportunidades de modernización, evaluar la viabilidad de soluciones tecnológicas y plantear mejoras alineadas con las demandas actuales del sector agroalimentario.

## 2. Selección de la empresa y contexto de trabajo

Para el desarrollo del proyecto se ha elegido la empresa Sovena, ubicada en el municipio de Brenes (Sevilla). Se trata de una multinacional portuguesa dedicada a la producción y envasado de aceite, cuya planta en Brenes destaca por su volumen de actividad y su relevancia dentro del sector agroalimentario. La elección de esta empresa se fundamenta tanto en su importancia como en el conocimiento directo del entorno, ya que la experiencia laboral previa en sus instalaciones permite disponer de una visión real y cercana de su funcionamiento interno.

Sovena cuenta con una estructura organizativa compleja que combina oficinas administrativas, zonas de producción automatizada, áreas de almacenamiento y depósitos de aceite, así como un sistema de control de accesos que regula la entrada y salida del personal. La plantilla supera el centenar de trabajadores, divididos entre empleados internos y personal contratado a través de empresas de trabajo temporal. La organización del trabajo se realiza mediante tres turnos rotativos (mañana, tarde y noche), lo que hace que la coordinación entre departamentos, especialmente RRHH, producción y ETT, sea un aspecto fundamental para el funcionamiento diario.

A pesar de ser una empresa con un nivel tecnológico considerable, su tamaño y la naturaleza de sus operaciones generan ciertos desafíos internos que resultan especialmente relevantes para este proyecto. Entre ellos destacan la gestión del personal temporal, los cambios frecuentes en los turnos asignados, la falta de homogeneidad en el uso del sistema de control de accesos y algunas carencias detectables en la red interna, como el uso de servicios accesibles mediante HTTP.

En conjunto, Sovena ofrece un contexto realista y suficientemente amplio para el análisis, ya que combina las características propias de una industria moderna —automatización, procesos intensivos, exigencias de trazabilidad y coordinación de personal— con oportunidades tangibles de mejora tecnológica.

## 3. Identificación de necesidades tecnológicas

A pesar del nivel industrial y tecnológico de Sovena, el análisis del entorno interno revela varias necesidades que afectan al funcionamiento general de la planta, especialmente en lo relacionado con la gestión del personal, la seguridad y la organización de los procesos. Uno de los aspectos más evidentes es la falta de integración y control en la gestión de los trabajadores procedentes de ETT, cuyo flujo de entrada, salida y cambios de turno genera un notable desorden. El sistema actual provoca confusión entre empleados fijos y temporales, con frecuentes modificaciones de horarios que no siempre quedan reflejadas de manera adecuada. Esto afecta a la planificación de la producción, al equilibrio de los turnos y, en ocasiones, a la sobrecarga de determinados equipos de trabajo.

Asimismo, aunque la empresa dispone de un sistema de identificación biométrica por reconocimiento facial para regular el acceso, su uso no es uniforme. El hecho de que parte del personal eventual pueda entrar sin necesidad de identificarse mediante este sistema provoca lagunas en el control real de presencia y reduce la eficacia del propio mecanismo, que deja de cumplir su función principal de trazabilidad y seguridad.

En cuanto a la infraestructura tecnológica, la red interna se basa en una LAN cerrada que cumple con su cometido operativo, pero algunos servicios corporativos siguen funcionando a través de HTTP, lo cual supone un riesgo para la integridad de las comunicaciones y la confidencialidad de la información interna. El tránsito de datos sin cifrado entre terminales, paneles de producción o estaciones de trabajo de oficina representa una vulnerabilidad que debería ser corregida para garantizar estándares mínimos de seguridad.

Por último, la coexistencia de múltiples áreas —oficinas administrativas, control de accesos, naves de producción, almacenes y depósitos— requiere una coordinación tecnológica más homogénea. La variedad de sistemas y procedimientos dificulta la visión global del funcionamiento diario y puede limitar la capacidad de detectar incidencias de manera centralizada.

### Soluciones propuestas

Para abordar estas necesidades se plantean diversas soluciones prácticas basadas en tecnologías ampliamente utilizadas en entornos industriales:

**1. Regularización del sistema de accesos y turnos**
- Implantación de un **ERP con módulo de RRHH** como *SAP SuccessFactors, Oracle PeopleSoft o Odoo Enterprise*, que centralice turnos, personal de ETT y presencia.
- Integración con el sistema biométrico mediante un **middleware de control de accesos** (ZKTeco ZKBioSecurity, ControlID, ActiTIME).
- Uso obligatorio y automatizado del reconocimiento facial para todo el personal, con generación de alertas si alguien accede sin identificación.
- Automatización del cuadrante laboral con sistemas de **gestión de turnos** como *Planday*, *Bizneo HR*, *Factorial* o *Shiftboard*.

**2. Seguridad en la red interna**
- Sustituir HTTP por HTTPS implementando **certificados digitales internos** generados con *OpenSSL*, o una **Autoridad Certificadora interna (CA)**.
- Configuración de servidores web corporativos utilizando **Nginx o Apache** con TLS 1.2/1.3.
- Implantación de políticas de hardening en la LAN y segmentación VLAN por áreas (Oficinas, Producción, Almacenes, Control de accesos).

**3. Integración global de procesos**
- Implementar un ERP industrial completo como *SAP S/4HANA* para centralizar:
  - Producción
  - Trazabilidad de lotes
  - Control de almacenes
  - Mantenimiento industrial (GMAO)
  - Gestión de recursos humanos

**4. Mejora de la supervisión operativa**
- Uso de paneles de control con **Grafana** o **Kibana**, conectados a los sistemas internos para monitorizar:
  - Estado de la producción en tiempo real
  - Presencias y ausencias
  - Incidencias en red o sistemas
  - Alarmas automáticas para fallos en accesos o inconsistencias de personal

 
## 4. Oportunidades y viabilidad del proyecto

El proyecto propuesto presenta claras oportunidades tanto estratégicas como operativas. La implementación de un sistema ERP para la gestión de turnos de trabajadores internos y de ETT permitiría centralizar la información, reducir conflictos, mejorar la planificación de la producción y garantizar la correcta asignación de turnos, incrementando la satisfacción del personal y la eficiencia operativa. Además, la transición de las conexiones internas de HTTP a HTTPS mediante certificados TLS/SSL en los servidores Nginx fortalecería la seguridad de la información, minimizando riesgos de interceptación y cumpliendo con buenas prácticas de ciberseguridad industrial. La integración de software SCADA o MES para el monitoreo de la producción, naves de almacenamiento y depósitos de aceite aportaría visibilidad en tiempo real de los procesos, permitiendo detectar incidencias, optimizar recursos y asegurar la trazabilidad de los productos.

Desde el punto de vista económico y técnico, la viabilidad del proyecto es alta. Sovena cuenta con infraestructura de red robusta, personal capacitado para la adopción de nuevas herramientas y sistemas existentes que pueden integrarse con soluciones ERP y MES modernas. La inversión necesaria se justifica por los beneficios tangibles en eficiencia, reducción de errores y mejora en la gestión del personal y la producción. Adicionalmente, la alineación con las tendencias de digitalización del sector agroalimentario aumenta la competitividad de la empresa, asegurando que los procesos internos se ajusten a estándares modernos de calidad, seguridad y trazabilidad. 

Por último, el proyecto permite generar un impacto medible a corto y medio plazo: reducción de incidencias en la planificación de turnos, mayor seguridad en las comunicaciones de datos internos, y optimización de la producción y almacenamiento. Esto refuerza la sostenibilidad del proyecto y su adaptación a las necesidades tecnológicas de una empresa industrial de gran tamaño como Sovena, consolidando oportunidades de mejora continuada y escalabilidad futura de las soluciones implementadas.

## 5. Obligaciones legales y normativas

La implementación de mejoras tecnológicas en Sovena debe cumplir con un conjunto de obligaciones legales y normativas tanto a nivel laboral como en materia de protección de datos y seguridad industrial. En primer lugar, la gestión de turnos y control de personal mediante ERP requiere respetar la normativa laboral vigente, especialmente la Ley del Estatuto de los Trabajadores, que regula horarios, descansos, turnos y condiciones de trabajo, así como las obligaciones específicas para empleados temporales (ETT). La correcta planificación y registro digital de turnos ayuda a garantizar que la empresa cumpla con estas exigencias, evitando conflictos legales y sanciones.

En cuanto a la seguridad de la información, la transición de HTTP a HTTPS mediante certificados TLS/SSL debe alinearse con el **Reglamento General de Protección de Datos (RGPD)**, asegurando que la información de los empleados y datos de producción se almacene, transmita y gestione de manera segura y confidencial. Los sistemas de control de acceso, monitorización de la producción y almacenamiento de datos también deben cumplir con la normativa de seguridad industrial, así como con estándares internos de la compañía para la trazabilidad de productos y la integridad de los procesos.

Por otra parte, cualquier implementación tecnológica en las instalaciones físicas, como servidores, redes o terminales de control, debe respetar las normas de prevención de riesgos laborales (PRL), asegurando que el personal pueda operar de manera segura sin riesgos eléctricos, de caídas o de manipulación de equipos informáticos y de producción. Asimismo, se deben considerar las certificaciones y normativas del sector agroalimentario, como ISO 22000 para seguridad alimentaria y buenas prácticas de manufactura, garantizando que la digitalización no afecte la calidad ni la trazabilidad del aceite producido.

## 6. Guion inicial del proyecto

El proyecto para Sovena se plantea como una iniciativa de mejora tecnológica centrada en optimizar la gestión de turnos, reforzar la seguridad de las comunicaciones internas y supervisar de manera más eficiente los procesos de producción y almacenamiento. La primera fase consistirá en un **análisis detallado de los sistemas existentes**, evaluando la infraestructura de red, los servidores Nginx, los puestos de trabajo, la identificación facial de empleados y los procesos actuales de gestión de turnos y producción. Este diagnóstico permitirá identificar los puntos críticos y definir las prioridades de intervención.

La segunda fase se enfocará en **la implementación de soluciones concretas**: la instalación de certificados TLS/SSL en todos los servidores internos para garantizar conexiones HTTPS seguras; la integración de un ERP, como Odoo o SAP Business One, para centralizar la planificación de turnos, controlar accesos y automatizar registros de empleados internos y de ETT; y la puesta en marcha de software SCADA o MES para el monitoreo en tiempo real de la producción, almacenes y depósitos de aceite, asegurando trazabilidad y eficiencia operativa.

La tercera fase consistirá en **la capacitación del personal y pruebas piloto**, permitiendo que empleados internos y responsables de planta se familiaricen con las nuevas herramientas, se validen los flujos de trabajo y se ajusten los parámetros del ERP y del sistema de monitorización. Se realizarán pruebas controladas para asegurar la correcta integración de los sistemas y minimizar cualquier interrupción en la producción.

Finalmente, la cuarta fase contempla **la evaluación de resultados y la documentación del proyecto**, midiendo mejoras en la gestión de turnos, seguridad de datos, eficiencia de la producción y trazabilidad. Se elaborará un informe final que recoja las incidencias detectadas, las soluciones aplicadas, los beneficios obtenidos y las recomendaciones para futuras ampliaciones o mejoras continuas, garantizando que el proyecto se mantenga sostenible y adaptable a las necesidades cambiantes de la empresa.

## Enlaces a recursos de la unidad

- [Documentos de la unidad](./documentos/)
- [Diagramas e imágenes](./img/)

  ## Bibliografía / Webgrafía 
- AINIA. “Cómo están abordando las empresas del sector agroalimentario la Transformación Digital” (2023). [https://www.ainia.com/ainia-news/empresas-sector-agroalimentario-transformacion-digital-sector/](https://www.ainia.com/ainia-news/empresas-sector-agroalimentario-transformacion-digital-sector/)  
- Industria alimentaria en España. Wikipedia. [https://es.wikipedia.org/wiki/Industria_alimentaria_en_Espa%C3%B1a](https://es.wikipedia.org/wiki/Industria_alimentaria_en_Espa%C3%B1a)  
- Reglamento General de Protección de Datos (RGPD). [https://eur-lex.europa.eu/legal-content/ES/TXT/?uri=CELEX%3A32016R0679](https://eur-lex.europa.eu/legal-content/ES/TXT/?uri=CELEX%3A32016R0679)  
- ISO 22000 – Seguridad alimentaria. [https://www.iso.org/standard/65464.html](https://www.iso.org/standard/65464.html)

