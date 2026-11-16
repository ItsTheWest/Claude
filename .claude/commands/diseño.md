---
description: Modo diseño web (código y Figma). Carga el contexto y las skills de diseño; NO implementa nada hasta que se indique dónde.
argument-hint: [opcional: tema o contexto del proyecto]
---

# Modo /diseño

Entras en **modo diseño web**. Aplica tanto a desarrollo web en código (HTML/CSS, React, Next.js, Vue, Svelte, Astro, Tailwind) como a diseño en Figma (usando el MCP/skills de Figma: `figma-use`, `figma-generate-design`, `figma-design-to-code`, etc.).

## Regla principal
**Este comando solo carga contexto. NO implementes, crees, edites ni escribas archivos todavía.**
1. Lee con la herramienta Skill las skills base que apliquen: `impeccable`, `taste-skill`, `emil-design-eng`, `apple-design`.
2. Confirma en 3-4 líneas que el modo está activo y pregunta: *"¿Dónde y qué quieres que implemente? (carpeta/proyecto, o archivo de Figma, y la tarea)"*.
3. Espera mi respuesta. Solo entonces trabaja, en el destino que yo indique.

Contexto adicional del usuario: $ARGUMENTS

## Skills disponibles y cuándo usarlas (úsalas según la tarea que defina después)

**Dirección y calidad visual (base)**
- `impeccable`: diseñar, rediseñar, criticar, auditar, pulir y animar frontends (sub-flujos: craft, critique, audit, polish, layout, colorize, bolder, distill, harden, adapt, optimize, etc.).
- `taste-skill`: sitios/landings con nivel profesional, anti "AI-slop"; copy propio, un sistema, fotografía/UI real, checker y finish gate en navegador.
- `emil-design-eng`: filosofía de pulido de UI y detalles invisibles de interacción.
- `apple-design`: diseño fluido y físico estilo Apple, tipografía, materiales.

**Movimiento**
- `animate`, `choreograph`, `gestures`, `animation-performance`, `animation-vocabulary`, `review-animations`, `improve-animations`, `find-animation-opportunities`, `remove-animations`, `animate-expo` (React Native/Expo).

**Proceso y validación**
- `prototype` (varias versiones con selector visual), `break-ui` (datos en el peor caso), `pick-ui-library` (elegir librerías), `mobile-native` (sensación nativa en móvil), `ask-sonner` (toasts), `learn-taste` (convertir correcciones en reglas), `ask-emil` (router: qué skill usar).

**Figma** (si el destino es Figma)
- Carga `figma-use` antes de cualquier `use_figma`; usa `figma-generate-design` para pantallas/páginas, `figma-generate-library` para sistemas de diseño/variables, `figma-design-to-code` para pasar de Figma a código, `figma-code-connect` para mapear componentes.
- Requiere el MCP de Figma autenticado.

## Criterios generales de trabajo
- Responsive (móvil primero), accesibilidad (contraste, foco, `prefers-reduced-motion`), tokens/variables de diseño consistentes, un solo sistema visual.
- Evita estética genérica de plantilla; prioriza jerarquía, espaciado, tipografía y detalle.
- Antes de dar algo por terminado, verifícalo en un navegador real cuando sea código.
- Responde en español.
