# Ecosistema de Automatización IA — Clasificación de Leads VIP

**Curso:** IA Automation — Coderhouse  
**Alumno:** Sebastián Leonel Ríos  
**Fecha:** Julio 2026

## Descripción
Pipeline automatizado de clasificación de leads VIP usando Make, Airtable, Claude API y Gmail/Slack.

## Archivos
- `EntregaFinal_Sebastian Rios.pdf` — Arquitectura completa del sistema
- `blueprint_leads_vip.json` — Blueprint exportado desde Make
- `screenshots/` — Capturas del flujo en ejecución

## Base de datos
[Ver Airtable en modo lectura](https://airtable.com/invite/l?inviteId=invtfx0eMVgGkPCYa&inviteToken=dbbcbdb506629b77050912314f51222ddc289f5382a3c53efc06c2dce1c68df0&utm_medium=email&utm_source=product_team&utm_content=transactional-alerts)
Nota sobre implementación
Este repositorio documenta dos niveles del proyecto:

Arquitectura diseñada (PDF): ecosistema completo con 14 módulos, Slack, segundo trigger de aprobación automática, retry x3 y salida multicanal. Representa el sistema en producción.
MVP implementado (blueprint .json): flujo funcional de 7 módulos que cubre el proceso core end-to-end. Watch Records → Search Records → HTTP Claude → JSON Parse → Router → Gmail HITL → Airtable Update. Todos los requisitos obligatorios del enunciado están implementados y probados.
