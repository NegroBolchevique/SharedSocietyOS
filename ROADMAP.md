# ROADMAP — SharedSocietyProject

Visión: construir una plataforma de coordinación y administración colectiva, modular y escalable, que permita gobernanza distribuida sin dependencia de estados centralizados.

Estado general
- Repositorio: iniciado
- Prioridad inicial: definir MVPs claros y entregables para atraer contribuciones.

Principios de priorización
1. Valor mínimo usable: resolver el caso de uso más crítico con la menor complejidad.
2. Seguridad y privacidad primero.
3. Modularidad: cada componente debe poder desplegarse y probarse independientemente.
4. Transparencia en decisiones (RFCs y propuestas documentadas).

Hitos y objetivos (cronograma orientativo)

MVP-0 (Discovery) — 0–1 mes
- Documentación de la visión (README + ROADMAP).
- Definición de arquitectura y módulos.
- Plantillas de contribución y gobierno.
Criterio de cierre: README + ROADMAP + 3 RFCs básicos aprobados.

MVP-1 (Core primitives) — 1–3 meses
- Autenticación y gestión de identidades (registro, login, roles).
- Módulo de propuestas y votación simple (on-chain-style o DB con auditoría).
- Interfaz mínima (CLI o web simple) para crear propuestas y votar.
Criterios de cierre: despliegue del stack local funcional + pruebas automatizadas básicas.

MVP-2 (Economía interna y gobernanza avanzada) — 3–6 meses
- Módulo económico básico (tokens internos, balances).
- Reglas de votación ponderadas, delegación y quorum.
- Auditoría de seguridad en los módulos críticos.
Criterios de cierre: simulación de votación con múltiples nodos + auditoría de seguridad interna.

MVP-3 (Escalado y resistencia) — 6–12 meses
- Escalado horizontal: diseño para despliegue en múltiples regiones.
- Privacidad mejorada (cifrado en tránsito y en reposo, privacidad de votantes).
- Integraciones: wallets, oráculos, módulos de interoperabilidad.
Criterios de cierre: despliegue multi-región de prueba + pruebas de carga.

Extensiones / Futuro (12+ meses)
- Mecanismos avanzados de gobernanza (curated markets, DAOs interoperables).
- Herramientas de adopción: SDKs, mobile apps, plantillas de despliegue.
- Auditorías de terceros y certificaciones.

Cómo contribuir al roadmap
- Proponer RFCs en /proposals con el formato `RFC-XXXX`.
- Asignar prioridad y owner para propuestas con la etiqueta `roadmap`.
- Si quieres trabajar en un item, abre un issue y referencia el milestone correspondiente.

Milestones y seguimiento
- Cada milestone tendrá un Issue/Milestone en GitHub con subtareas y criterios de aceptación.
- Usaremos milestones para planificar releases y evaluar progreso.

Notas finales
- Fechas y alcance pueden ajustarse según contribuciones y descubrimientos técnicos.
- Para temas sensibles (seguridad, privacidad) aplicar política de divulgación responsable en SECURITY.md.