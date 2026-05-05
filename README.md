# Mi portfolio — Taller de IA

Bienvenido/a al taller. Este repo va a evolucionar contigo durante 60 - 90 minutos. Cada nivel
añade una herramienta nueva de IA y debes hacer un commit. Al final tendrás una web personal
desplegada en GitHub Pages y un puñado de ideas claras sobre cómo se usa bien la IA.

Tacha cada nivel cuando lo termines. Si te atascas, levanta la mano.

## Niveles

- [ ] **Nivel 0 — Prompt ingenuo**
  Pide a OpenCode `crea una página de portfolio para mí` sin nada más. Mira lo malo que es.
  Commit: `nivel-0: portfolio genérico sin contexto`.

- [ ] **Nivel 1 — AGENTS.md**
  Rellena `AGENTS.md` con tus datos reales. Vuelve a pedirle a OpenCode el portfolio.
  Compara la diferencia.
  Commit: `nivel-1: AGENTS.md con contexto personal`.

- [ ] **Nivel 2 — design.md (Google Labs)**
  Rellena `design.md` con tus colores, tu tipografía y tu sistema de espaciado.
  Pide: *"aplica el sistema de diseño definido en design.md a la web. No inventes valores nuevos."*
  Commit: `nivel-2: design.md con identidad visual del portfolio`.

- [ ] **Nivel 3 — Slash command**
  Crea `.opencode/command/nuevo-proyecto.md`. Invócalo con `/nuevo-proyecto "Pong en JS" "HTML, CSS, JavaScript"`.
  Commit: `nivel-3: slash command /nuevo-proyecto`.

- [ ] **Nivel 4 — Skill instalada (skills.sh)**
  En la terminal, en la raíz del repo: `npx skills add anthropics/skills -a opencode`.
  Luego pide: *"mejora visualmente la página: jerarquía, ritmo, sistema tipográfico, espaciados. Hazla pro."*
  Commit: `nivel-4: skill frontend-design instalada desde skills.sh`.

- [ ] **Nivel 5 — MCP de GitHub**
  Comprueba que `opencode.json` tiene el MCP de GitHub configurado. Pide al agente que
  cree 3 repos en tu cuenta sobre tu afición y los enlace desde la sección "Proyectos".
  Commit: `nivel-5: MCP oficial de GitHub creando repos y poblando portfolio`.

- [ ] **Nivel 6 — Subagentes especializados**
  Crea `.opencode/agent/a11y-auditor.md` y `.opencode/agent/seo-auditor.md`.
  Llama `@a11y-auditor audita la web`, luego `@seo-auditor audita la web`,
  y por último pide al agente principal aplicar las correcciones de ambos informes.
  Commit: `nivel-6: subagentes a11y-auditor + seo-auditor + auditoría aplicada`.

- [ ] **Cierre — GitHub Pages**
  Settings del repo → Pages → activar desde main. Apunta tu URL pública aquí:
  `https://_____________.github.io/portfolio-taller-ia/`

## Recordatorio rápido

- **Slash command** = lo lanzas tú (`/nombre`).
- **Skill** = la lanza la IA sola cuando ve que aplica. La instalas (`npx skills add ...`).
- **Subagente** = un especialista que tú defines y llamas con `@nombre`.
- **MCP** = puente para que la IA toque sistemas externos (GitHub, navegador, APIs).
