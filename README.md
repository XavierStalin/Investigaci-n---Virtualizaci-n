# Contexto General

La virtualización es una tecnología fundamental para la construcción y administración de infraestructura moderna. Permite abstraer recursos físicos como procesamiento, memoria, almacenamiento y red, creando entornos virtuales que pueden ser administrados de forma flexible y eficiente.

En el contexto de los sistemas distribuidos, la virtualización permite desplegar múltiples servidores, servicios, aplicaciones, bases de datos, balanceadores de carga y otros componentes sobre infraestructura física, en la nube o en modelos híbridos. Gracias a esta tecnología, las organizaciones pueden mejorar el uso de sus recursos, facilitar la escalabilidad, aumentar la disponibilidad y simplificar la administración de sus sistemas.

Esta actividad se centrará en la virtualización de servidores e infraestructura para sistemas distribuidos. El grupo deberá investigar conceptos básicos, herramientas actuales y usos reales de esta tecnología en organizaciones o escenarios prácticos.

Se puede utilizar inteligencia artificial como apoyo para organizar ideas, revisar redacción o mejorar la presentación del informe, pero no como reemplazo de la investigación. La información técnica debe provenir de fuentes confiables, como documentación oficial, proveedores cloud, artículos técnicos, manuales o sitios especializados.

Esta investigación no requiere el uso de Scopus AI, ya que el enfoque está orientado a tecnología actual, herramientas de infraestructura y aplicaciones prácticas.

---

# Parte I — Conceptos Fundamentales

## Objetivo

Comprender qué es la virtualización de servidores e infraestructura y cómo se relaciona con los sistemas distribuidos.

## Instrucciones

### Paso 1

Explique con sus propias palabras qué es la virtualización de servidores e infraestructura.

### Paso 2

Describa brevemente los siguientes conceptos:

- Hipervisor.
- Máquina virtual.
- Servidor físico o host.
- Clúster de virtualización.
- Red virtual.
- Almacenamiento virtualizado o compartido.
- Alta disponibilidad.
- Infraestructura como servicio, IaaS.

### Paso 3

Explique cómo la virtualización ayuda al funcionamiento de los sistemas distribuidos. Puede considerar aspectos como despliegue de múltiples servidores, escalabilidad, aislamiento de servicios, ambientes de prueba, recuperación ante fallos y uso eficiente de recursos.

## Entregable de esta parte

Una explicación breve, de entre **400 y 600 palabras**, sobre virtualización de servidores e infraestructura y su relación con los sistemas distribuidos.

---

# Parte II — Herramientas y Soluciones Actuales

## Objetivo

Identificar herramientas actuales de virtualización de infraestructura y comparar sus usos principales.

## Instrucciones

### Paso 1

Seleccionen cuatro herramientas o soluciones relacionadas con virtualización de servidores, infraestructura cloud, contenedores u orquestación.

El grupo debe incluir:

- Al menos una solución on-premise.
- Al menos una solución en la nube.
- Al menos una tecnología relacionada con contenedores u orquestación.

Pueden seleccionar herramientas como:

- VMware vSphere / ESXi.
- Microsoft Hyper-V.
- Proxmox VE.
- KVM / QEMU.
- Nutanix AHV.
- Amazon EC2.
- Azure Virtual Machines.
- Google Compute Engine.
- Docker.
- Kubernetes.

### Paso 2

Para cada herramienta seleccionada, describan brevemente:

- Qué es.
- Si se usa principalmente en modalidad on-premise, nube o híbrida.
- Para qué sirve dentro de una infraestructura distribuida.
- Una ventaja principal.
- Una limitación o desafío.

### Paso 3

Elaboren una **Matriz Comparativa Simplificada**.

| Herramienta o solución | Tipo de tecnología | Modelo de uso | Ventaja principal | Limitación o desafío | Uso recomendado en sistemas distribuidos |
|---|---|---|---|---|---|
| Ejemplo: Proxmox VE | Plataforma de virtualización | On-premise | Permite administrar máquinas virtuales y contenedores en servidores propios | Requiere conocimientos técnicos para administración y mantenimiento | Laboratorios, pequeñas empresas, centros de datos locales |
| Ejemplo: Amazon EC2 | IaaS / máquinas virtuales en la nube | Nube | Permite crear servidores virtuales bajo demanda | Puede generar costos variables si no se controla el consumo | Aplicaciones web, servicios escalables, infraestructura cloud |
| Ejemplo: Docker | Contenedores | On-premise / nube / híbrido | Facilita empaquetar y ejecutar aplicaciones de forma portable | No reemplaza completamente a las máquinas virtuales en todos los casos | Microservicios, desarrollo, pruebas, despliegue de aplicaciones |
| Ejemplo: Kubernetes | Orquestación de contenedores | On-premise / nube / híbrido | Permite administrar aplicaciones distribuidas en contenedores | Puede ser complejo de configurar y operar | Microservicios, aplicaciones escalables, plataformas distribuidas |

## Entregables de esta parte

- Descripción breve de cuatro herramientas o soluciones.
- Matriz Comparativa Simplificada.

---

# Parte III — Usos en Contextos Reales

## Objetivo

Analizar cómo se utiliza la virtualización de infraestructura en contextos reales relacionados con sistemas distribuidos.

## Instrucciones

### Paso 1

Seleccionen dos contextos reales donde la virtualización sea útil para soportar sistemas distribuidos.

Pueden elegir entre los siguientes escenarios:

- Comercio electrónico.
- Centro de datos empresarial.
- Institución financiera.
- Universidad o laboratorio académico.
- Empresa de desarrollo de software.
- Proveedor de servicios cloud.
- Sector salud.
- Gobierno digital.
- Telecomunicaciones.
- Startup tecnológica.

### Paso 2

Para cada contexto seleccionado, expliquen:

- Qué necesidad o problema de infraestructura existe.
- Qué solución o tipo de virtualización podría utilizarse.
- Qué componentes de un sistema distribuido estarían involucrados.
- Qué beneficio aporta la virtualización.
- Qué riesgo o desafío debe considerarse.

### Paso 3

Elaboren una **Tabla de Usos en Contextos Reales**.

| Contexto real | Necesidad principal | Solución aplicable | Componentes distribuidos involucrados | Beneficio principal | Riesgo o desafío |
|---|---|---|---|---|---|
| Comercio electrónico | Soportar alta demanda de usuarios y transacciones | Máquinas virtuales cloud, balanceadores, contenedores | Aplicaciones web, APIs, bases de datos, servicios de pago | Escalabilidad y disponibilidad | Costos variables y dependencia de conectividad |
| Centro de datos empresarial | Consolidar servidores y mejorar disponibilidad | VMware vSphere, Hyper-V, Proxmox VE o KVM | Servidores de aplicación, bases de datos, servicios internos | Mejor uso de recursos y administración centralizada | Complejidad de administración y mantenimiento |

## Entregables de esta parte

- Análisis breve de dos contextos reales.
- Tabla de Usos en Contextos Reales.

---

# Parte IV — Elaboración del Informe Técnico

## Objetivo

Redactar un informe técnico breve, claro y sustentado en fuentes confiables sobre virtualización de infraestructura para sistemas distribuidos.

## Estructura mínima del informe

1. **Portada.** Nombre de los integrantes, asignatura, tema del trabajo, docente y fecha.
2. **Introducción.** Presentación breve del tema y su importancia para los sistemas distribuidos.
3. **Conceptos fundamentales.** Explicación de virtualización de servidores e infraestructura, incluyendo los conceptos solicitados en la Parte I.
4. **Relación con sistemas distribuidos.** Explicación de cómo la virtualización permite desplegar, escalar y administrar servicios distribuidos.
5. **Herramientas y soluciones actuales.** Descripción de las cuatro herramientas seleccionadas.
6. **Matriz Comparativa Simplificada.** Tabla comparativa de herramientas.
7. **Usos en contextos reales.** Análisis de los dos contextos seleccionados.
8. **Tabla de Usos en Contextos Reales.** Tabla resumen de los contextos analizados.
9. **Conclusiones.** Síntesis de lo aprendido y explicación de la utilidad de la virtualización para infraestructura distribuida.
10. **Declaración de Uso de Herramientas de IA.** Indicar qué herramientas de IA se usaron, en qué parte del trabajo y con qué propósito.
11. **Referencias en formato APA 7.** Incluir las fuentes consultadas.

## Extensión sugerida

Entre **1.200 y 1.500 palabras**, sin contar tablas ni referencias.

El informe debe ser claro, concreto y enfocado en análisis técnico básico.

## Fuentes mínimas requeridas

Al menos **cuatro fuentes confiables**.

Se recomienda usar documentación oficial de herramientas, proveedores cloud, artículos técnicos o sitios especializados.

No se acepta bibliografía inventada o generada por IA sin verificación.

## Declaración de Uso de Herramientas de IA

Incluyan al final del informe una declaración donde indiquen si utilizaron herramientas de inteligencia artificial, cuáles fueron y con qué propósito específico. La ausencia de esta declaración se penalizará.

Ejemplo orientativo:

> “En la elaboración de esta tarea utilizamos ChatGPT para apoyar la organización de ideas y revisar la redacción del informe. La investigación de fuentes, selección de herramientas, construcción de las tablas, análisis técnico y conclusiones son de autoría del grupo.”

---

# Restricciones generales

- El informe debe centrarse en virtualización de servidores e infraestructura para sistemas distribuidos.
- No debe centrarse en virtualización de escritorios.
- Debe incluir al menos una solución on-premise y una solución en la nube.
- Debe incluir al menos una tecnología relacionada con contenedores u orquestación.
- Debe relacionar la virtualización con el despliegue, operación, escalabilidad o disponibilidad de sistemas distribuidos.
- Debe incluir usos en contextos reales, no solo ejemplos teóricos.
- Las afirmaciones técnicas relevantes deben estar respaldadas por fuentes confiables.
- La IA puede utilizarse como apoyo, pero no como fuente principal de investigación.

---

# Entregables finales

- Informe técnico breve.
- Matriz Comparativa Simplificada.
- Tabla de Usos en Contextos Reales.
- Conclusiones.
- Declaración de Uso de Herramientas de IA.
- Referencias en formato APA 7.

---

# Rúbrica de Calificación

La calificación se distribuye en dos bloques. El primero evalúa la investigación y comprensión técnica. El segundo evalúa el informe como producto final.

## Bloque A — Investigación y Comprensión Técnica

**50 puntos**

| Dimensión | Criterio | Puntaje |
|---|---|---|
| Conceptos fundamentales | Explica de forma clara la virtualización de servidores e infraestructura y sus conceptos básicos. | 15 pts |
| Relación con sistemas distribuidos | Explica cómo la virtualización apoya el despliegue, escalabilidad, disponibilidad o administración de sistemas distribuidos. | 15 pts |
| Selección de herramientas | Selecciona cuatro herramientas pertinentes, incluyendo solución on-premise, solución en la nube y tecnología de contenedores u orquestación. | 15 pts |
| Uso responsable de IA | Declara de forma clara y honesta el uso de herramientas de IA. | 5 pts |

## Bloque B — Informe Técnico y Aplicación Práctica

**50 puntos**

| Dimensión | Criterio | Puntaje |
|---|---|---|
| Matriz comparativa | Compara las herramientas seleccionadas de forma clara, breve y técnicamente coherente. | 15 pts |
| Usos en contextos reales | Analiza dos contextos reales y explica cómo la virtualización responde a necesidades concretas. | 15 pts |
| Conclusiones | Presenta conclusiones claras sobre la utilidad de la virtualización para sistemas distribuidos. | 10 pts |
| Presentación y redacción | El documento está organizado, redactado con claridad y respeta la estructura mínima solicitada. | 5 pts |
| Referencias | Incluye al menos cuatro fuentes confiables en formato APA 7. | 5 pts |