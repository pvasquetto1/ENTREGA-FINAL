# Radar Inteligente de Licitaciones Biomédicas

Entrega final - Curso AI Automation

Automatización con **n8n + Airtable + Google Gemini + HITL (Human-in-the-Loop)** que detecta licitaciones públicas de equipamiento médico, las analiza con IA y arma un flujo de aprobación humana antes de avanzar comercialmente.

**Autora:** Paula Vasquetto

---

## Objetivo
Busca licitaciones públicas de equipamiento médico (diagnóstico por imágenes, respiradores, monitores, bombas de infusión, insumos hospitalarios, mantenimiento/calibración), y para cada una la IA extrae automáticamente:

- Organismo comprador
- Equipo solicitado
- Cantidad
- Presupuesto
- Provincia
- Fecha límite de presentación
- Requisitos técnicos / certificaciones
- Prioridad de compatibilidad comercial (Alta / Media / Baja)

El sistema solo notifica cuando hay una oportunidad relevante para la empresa configurada, evitando que un humano tenga que revisar manualmente cada publicación.

**Empresa de referencia (datos ficticios para la demo):** BioTecMed Argentina S.A., distribuidora de equipamiento médico (monitores multiparamétricos, bombas de infusión, desfibriladores, ecógrafos, equipos de anestesia, insumos y accesorios quirúrgicos, autoclaves, camas hospitalarias).

---

## 3. Entregables

| Entregable | Archivo |
|---|---|
| Arquitectura del pipeline | [arquitectura.html](./arquitectura.html) |
| Manual de datos | *pendiente* |
| Matriz de costos | *pendiente* |
| Malla de Seguridad, Privacidad y Resiliencia | [Malla de Seguridad Privacidad y Resiliencia.pdf](./Malla%20de%20Seguridad%20Privacidad%20y%20Resiliencia.pdf) |
| Test de estrés (5 corridas + camino infeliz) | [Test de estrés.pdf](./Test%20de%20estrés.pdf) |
| Dashboard de KPIs | *pendiente* |
| Archivo JSON del flujo (exportado de n8n) | [Radar Licitaciones Biomédicas.json](./Radar%20Licitaciones%20Biomédicas.json) |

## Entregables
- [Mapa de arquitectura](./Mapa%20de%20arquitectura.pdf)
- [Manual Operativo de Estructuras de Datos](./Manual%20Operativo%20de%20Estructuras%20de%20Datos.pdf)
- [Estrategia de Optimización de Costos y Recursos](./Estrategia%20de%20Optimización%20de%20Costos%20y%20Recursos.pdf)
- [Malla de Seguridad, Privacidad y Resiliencia]
- [Dashboard de control (Airtable)](https://airtable.com/appS7QAfwS4H9xLt0/shrD3x3TuWBFb0AfC)
- [Test de estrés]
- [Video demo](https://drive.google.com/file/d/1Ofy55J5bRki-MDJr4WK-i7bWD2KVXGN4/view?usp=sharing)
- [Archivo JSON del flujo]
  
## Base de datos
- [Tabla Licitaciones](https://airtable.com/appS7QAfwS4H9xLt0/shrP1Xgue1dzzTUAw)
- [Tabla Config_Empresa](https://airtable.com/appS7QAfwS4H9xLt0/shraWhwaPRNJCdOV9)
