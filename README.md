# NOTUS
Aplicación web progresiva que centraliza la vida académica del estudiante universitario: tareas, calendario, horario de clases y notas, con funcionamiento offline-first.l

| Capa | Tecnología |
|---|---|
| Frontend | HTML, CSS (Vanilla version)|
| PWA | Service Worker + `manifest.webmanifest` |
| Almacenamiento local | IndexedDB vía Dexie |

## Estructura

```
notus/
├── pulic/
├── src/
│   └── assets/        # Vanilla PWA
│   └── counter.js
│   └── main.ts
│   └── index.html
├── sw.js

## Puesta en marcha

Requisitos: Node ≥ 22
```bash
npm install                 
npm run dev                 # API en :3000 y web en :4200
``
