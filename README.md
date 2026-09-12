# PortafolioDEV

Portafolio interactivo de **Walter Zuñiga Lineros** — ingeniero de software y datos en
AgTech: plataformas full-stack en planta y campo, y arquitectura analítica end-to-end para
la agroindustria exportadora chilena.

Está construido como una revista serializada (*zasshi*): tipografía de titular condensada,
bordes gruesos, sombras duras y una portada que se hojea con las flechas del teclado. Trae
paleta de comandos (`Ctrl+P`), una terminal que responde comandos (`ayuda` los lista) y dos
temas — tinta y papel.

Se abre `index.html` en cualquier navegador, sin servidor y sin instalar nada. Solo las
tipografías se cargan desde Google Fonts; sin conexión el sitio funciona igual con las
tipografías del sistema.

## Qué hay adentro

| Página | Contenido |
|---|---|
| `portada` | Presentación, métricas y accesos rápidos |
| `tomos` | Línea de tiempo por etapas, de INACAP a Ranco Cherries |
| `capitulos` | Nueve proyectos filtrables por tecnología, con su decisión clave |
| `personaje` | Ficha profesional, stack por área y método de trabajo |
| `logros` | Hitos y certificaciones con fecha |
| `contacto` | Datos de contacto y qué tipo de rol busco |

Cada página y cada proyecto tienen su propio enlace: `index.html#tomos` abre la línea de
tiempo e `index.html#micomedor` abre ese capítulo directamente.

## Proyectos personales

**MiComedor** — El comedor de planta planificado, servido y medido desde una sola
aplicación. Una PWA donde el comensal arma su mes desde el teléfono, la cocina valida cada
retiro por QR y el supervisor planifica la minuta, opera el día y mide la adhesión.
Landing en [`micomedor/`](micomedor/index.html).

**MixTape** — Las partes buenas de YouTube, guardadas y escuchadas juntas. Una biblioteca
personal de momentos: se guarda un video, se marcan los pedazos que importan con precisión
de segundo y suenan todos seguidos, como una cinta continua. Incluye descarga del clip
exacto, ya recortado, sin recodificar. Landing en [`mixtape/`](mixtape/index.html).

## Estructura

```
index.html      portafolio completo — estilos y lógica en el mismo archivo
assets/         capturas de MiComedor y MixTape
micomedor/      landing de MiComedor
mixtape/        landing de MixTape
```

## Cómo verlo

```bash
git clone https://github.com/walterbzl/PortafolioDEV.git
```

Y abrir `index.html`.
