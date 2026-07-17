Game-Engine-Core-Sample
Build with Vite, "controller logic" extracted out of the UI view components into isolated TypeScript/JavaScript modules (like React Hooks or Vue Composables). This separates data fetching, validation, and business logic from presentation.

Landing (/) — Marketing hero with the REDPARSON brand, crimson/orange gradient, animated feature cards

Dashboard (/dashboard) — Project stats, FPS gauge, performance chart, recent projects — all live data

3D Editor (/editor) — Three.js WebGL viewport with OrbitControls, drag-and-drop objects (cube/sphere/light), physics simulation, Web Audio API collision sounds (frequency mapped from impact intensity), real-time FPS/draw calls/triangle counters, material editor (color, roughness, metalness, wireframe), performance logging to the API

Asset Library (/assets) — Searchable/filterable grid by type (texture/mesh/audio/material/script/prefab)

AI Generation Lab (/ai-lab) — Prompt input with pluggable provider selector (GPT-4o, Claude, Gemini, Custom), Mode Picker (code/shader/scene/material/level), simulated streaming output in a terminal-style block, generation history CI/CD Pipeline (/pipeline) — Visual flowchart of the full architectural grid (CI/CD → Sandbox Zones → Asset Registry → Safety Bounds → Safe Render → Active Viewport), kanban sprint board, workflow import/export Backend: Express API with PostgreSQL, all route groups, modular AI provider registry, physics-audio sync, 4K resolution support — seeded with 3 projects, 10 assets, 2 scenes, 15 performance logs.
