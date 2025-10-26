# Título del PR
[Tipo] Breve descripción — por ejemplo: feat(auth): añadir login con token

## Descripción
Explica qué cambios introduces y por qué. Relaciona con issues si aplica: `Closes #NN`.

## Tipo de cambio
- [ ] Bugfix (cambio que corrige un bug)
- [ ] Nueva funcionalidad (feature)
- [ ] Cambio que rompe compatibilidad (breaking change)
- [ ] Documentación / docs
- [ ] Infra / CI

## Checklist antes de solicitar revisión
- [ ] He seguido las guías en CONTRIBUTING.md
- [ ] Tests automatizados añadidos / actualizados
- [ ] Linter y formateo ejecutados (ej. `npm run lint`, `go fmt`, `prettier --write`)
- [ ] Documentación actualizada (README / docs / CHANGELOG)
- [ ] No hay secretos ni credenciales en el PR
- [ ] El PR está enfocado y con un solo propósito

## Cómo probar (instrucciones de testing)
Describe los pasos para ejecutar y verificar los cambios localmente:
```bash
# ejemplo
git checkout -b feature/mi-cambio
# comandos para levantar servicio, ejecutar tests
```

## Consideraciones de seguridad
Si el cambio afecta autenticación/autorización o manejo de datos sensibles, detállalo aquí.

## Notas para el revisor
Puntos clave a revisar, decisiones importantes o trade-offs.

## Checklist de merge (mantenedor)
- [ ] PR tiene al menos una aprobación de mantenedor
- [ ] CI pasó en todas las plataformas
- [ ] No hay conflictos con la rama `main`
- [ ] Se añadió changelog si aplica