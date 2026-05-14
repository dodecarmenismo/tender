# tender

Experiencia sonora participativa para directo.
Interfaz orgánica táctil — el público dispara samples de voz sobre un set en vivo.

## Estructura

```
tender/
├── index.html          # App principal
├── assets/
│   ├── videos/         # Cápsulas orgánicas en loop (Leonardo AI)
│   ├── audio/          # 12 samples de voz (ElevenLabs)
│   └── images/         # Recursos visuales
└── README.md
```

## Concepto

4 zonas táctiles (cápsulas orgánicas) sobre fondo shader WebGL.
Pool de 12 samples — cada usuario recibe 4 aleatorios al cargar.
Sin sincronización a tempo — voces habladas flotando sobre el mix.

## Stack

- WebGL / GLSL shaders
- HTML / CSS / JS vanilla
- ElevenLabs (generación de voz)
- Leonardo AI (cápsulas visuales)

## Assets pendientes

- [ ] 4 videos loop (cápsulas orgánicas) → assets/videos/
- [ ] 12 samples de voz → assets/audio/
