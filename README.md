# IEM-440 · Laboratorio de Vibraciones

Laboratorio interactivo para el curso de Vibraciones Mecánicas. Cada módulo calcula, anima y grafica un tema del semestre directamente en el navegador, sin instalar nada.

**Abrir el laboratorio:** https://USUARIO.github.io/iem-440-vibraciones/

## Contenido

| Unidad | Módulos |
|---|---|
| 1 · Fundamentos | Movimiento armónico y pulsaciones · Series de Fourier · Elementos elásticos y masa efectiva |
| 2 · Vibración libre | Amortiguamiento viscoso · Fricción de Coulomb · Estimación del amortiguamiento |
| 3 · Excitación armónica | Fuerza armónica · Excitación por la base · Desbalance rotatorio · Instrumentos sísmicos |
| 4 · Excitación general | Pulsos y espectro de choque · Fuerza periódica |
| 5 · Varios grados de libertad | Dos grados de libertad · Cadena de n GDL |
| 6 · Control de vibraciones | Aislamiento · Absorbedor dinámico |
| 7 · Sistemas continuos | Cuerdas, barras, ejes y vigas |

Cada módulo tiene un enlace directo, por ejemplo `#forzada`, `#absorbedor` o `#continuos`.

## Notas técnicas

- Un solo archivo `index.html`, sin compilación ni dependencias locales.
- Las respuestas en el tiempo se integran con Runge–Kutta de 4.º orden; la fricción de Coulomb se resuelve por tramos en forma exacta. Amplitudes, fases y frecuencias usan las expresiones analíticas.
- Las ecuaciones se renderizan con MathJax (cargado desde cdnjs) y las fuentes desde Google Fonts.
- Unidades SI.
