# Mi página

Buzón de sugerencias para mejorar el clima laboral: cualquier persona del
equipo escribe su observación (nombre y número de empleado son opcionales)
y ve cuántas sugerencias van registradas.

Todo lo que se muestra sale de la tabla `registros` en Supabase, nunca
escrito a mano en el HTML.

**`.claude/agents/revisor-antes-de-publicar.md`**: subagente de solo lectura
que revisa la rama antes de fusionar (llaves filtradas, cambios de más,
calidad del código) y solo reporta, nunca arregla.

## Para continuar
1. Abre una sesión de Claude sobre este repositorio.
2. Pide el cambio en una rama nueva, nunca sobre `main`.
3. Revisa la vista previa de Netlify y fusiona para publicar.

Reglas completas del proyecto en `CLAUDE.md`.
