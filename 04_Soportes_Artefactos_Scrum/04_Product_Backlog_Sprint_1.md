# Product Backlog implementado con IA – Sprint 1

**Proyecto:** SISFV – Argelia, Cauca  
**Horizonte del Sprint:** 2 semanas  
**Enfoque:** lote piloto de 12 viviendas priorizadas

## Criterios de priorización usados por el Product Owner
1. Viabilidad logística del lote.
2. Disponibilidad de kits fotovoltaicos.
3. Capacidad del equipo para cerrar instalaciones con evidencia completa.
4. Riesgo técnico y social.
5. Impacto en cobertura energética y aprendizaje del piloto.

## Evidencia de uso de IA para regeneración de historias
**Prompt utilizado:**
> Redacta historias de usuario para un proyecto SISFV rural en Argelia, Cauca. Organiza un Sprint piloto de 12 viviendas e incluye criterios de aceptación, dependencias, riesgos y prioridad.

**Resultado aplicado por el equipo:**
La IA ayudó a estandarizar la redacción de PBIs, proponer criterios de aceptación medibles y anticipar dependencias de logística, actas comunitarias, instalación y cierre documental.

## Backlog priorizado del Sprint 1
| ID | Historia de usuario | Prioridad | Puntos | Responsable principal | Dependencias | Riesgo principal | Criterio de aceptación |
|---|---|---:|---:|---|---|---|---|
| PBI-01 | Como Product Owner, quiero confirmar el lote piloto de 12 viviendas elegibles para asegurar un Sprint ejecutable. | Alta | 3 | Libardo | Listado de usuarios ZNI, validación local | Selección incompleta | Lote validado y aprobado para Sprint 1 |
| PBI-02 | Como equipo Scrum, queremos realizar concertación comunitaria para garantizar acceso, aceptación y coordinación local. | Alta | 5 | Diego | PBI-01 | Baja participación comunitaria | Acta de concertación diligenciada |
| PBI-03 | Como Developer técnico, quiero ejecutar replanteo de obra en 12 viviendas para verificar condiciones de instalación. | Alta | 8 | Julio | PBI-01, PBI-02 | Hallazgos técnicos en sitio | Replanteo cerrado para las 12 viviendas |
| PBI-04 | Como equipo de planificación, queremos alistar y despachar 12 kits para iniciar instalación sin quiebres de inventario. | Alta | 5 | Annie | PBI-03 | Faltantes de materiales | Kits listos y asignados a cada vivienda |
| PBI-05 | Como equipo técnico, queremos instalar los sistemas de las viviendas 1-4 para entregar primeras soluciones funcionales. | Alta | 13 | Julio | PBI-04 | Clima o acceso | 4 sistemas instalados y energizados |
| PBI-06 | Como equipo técnico, queremos instalar los sistemas de las viviendas 5-8 para mantener flujo de entrega dentro del Sprint. | Alta | 13 | Julio | PBI-04 | Retrasos operativos | 4 sistemas instalados y energizados |
| PBI-07 | Como equipo técnico, queremos instalar los sistemas de las viviendas 9-12 para completar el lote piloto. | Alta | 13 | Julio | PBI-04 | Sobrecarga de cuadrilla | 4 sistemas instalados y energizados |
| PBI-08 | Como equipo, queremos ejecutar instalaciones internas y pruebas funcionales para validar seguridad y operación. | Alta | 8 | Julio | PBI-05,06,07 | Reprocesos por cableado o conexión | Checklist técnico aprobado |
| PBI-09 | Como Product Owner, quiero asegurar capacitación básica a usuarios para facilitar uso y sostenibilidad. | Media | 5 | Libardo | PBI-08 | Falta de asistencia | 12 usuarios capacitados o representados |
| PBI-10 | Como equipo, queremos registrar evidencias en Survey123 para soportar trazabilidad y aceptación. | Alta | 8 | Diego | PBI-08 | Evidencia incompleta | Fotos, firmas y checklist cargados |
| PBI-11 | Como Scrum Master, quiero consolidar métricas del Sprint para tomar decisiones de mejora. | Media | 3 | Kevin | Datos diarios del Sprint | Datos inconsistentes | Métricas y análisis disponibles para Review y Retro |
| PBI-12 | Como equipo Scrum, queremos cerrar el Sprint con Review y Retrospective para validar valor y acciones de mejora. | Alta | 3 | Kevin | PBI-09, PBI-10, PBI-11 | Falta de información | Review y Retro documentadas |

## Resultado del refinamiento
Se seleccionaron los PBIs 01 al 12 para el Sprint 1 porque permiten cerrar un lote piloto con aprendizaje técnico, social y documental, en coherencia con la Definition of Done del proyecto.
