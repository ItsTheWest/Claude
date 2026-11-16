# Claude: skills de diseño y configuración

Este repositorio contiene las skills, el comando `/diseño` y la configuración del MCP de Figma para usar desde Claude Code (computadora, web o teléfono).

## Qué incluye
- `.claude/skills/`: skills de diseño (emil-design-eng, animate, choreograph, gestures, impeccable, taste-skill, etc.).
- `.claude/commands/diseño.md`: comando `/diseño`.
- `.mcp.json`: servidor MCP de Figma (remoto).

## Cómo usarlo
1. Abre Claude Code con este repositorio como carpeta de trabajo, o conéctalo en la sesión web/app.
2. Escribe `/mcp`, elige **figma** y pulsa **Authenticate**. Inicia sesión en Figma y acepta los permisos. Esto se hace una vez por dispositivo.
3. Usa `/diseño` para cargar el modo diseño antes de pedir algo.

## Nota
Las credenciales no están en el repositorio. Cada dispositivo se autentica por separado.
