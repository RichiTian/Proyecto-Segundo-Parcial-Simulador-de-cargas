
  # ⚡ Simulador de Cargas Eléctricas — Coulomb Sim

Simulador interactivo de electrostática basado en la Ley de Coulomb. Permite colocar cargas eléctricas positivas y negativas en un plano 1D o 2D, visualizar las fuerzas entre ellas, las líneas de campo y el vector del campo eléctrico en puntos específicos, todo en tiempo real.

---
## Integrantes:
- Carraco Villegas Ricardo Sebastian
- Hernandez Nieves William Kiran
- Perez Vazquez Mauricio
---
##  Descripción

El simulador calcula y dibuja:

- **Fuerzas de Coulomb** entre todas las cargas del sistema (fuerzas individuales y fuerza neta)
- **Líneas de campo eléctrico** trazadas por integración numérica
- **Vectores del campo E** en una cuadrícula y en puntos de evaluación definidos por el usuario
- Soporte para modo **1D** (solo eje X) y **2D** (plano XY)

---

##  Librerías utilizadas

| Librería | Uso | Carga |
|---|---|---|
| **Google Fonts** — Orbitron, Space Mono, Inter | Tipografías de la interfaz | CDN |
| **Canvas API** (nativa del navegador) | Renderizado de la simulación | Nativa |

> El proyecto **no tiene dependencias externas de JavaScript**. Toda la física, el renderizado y la lógica de interfaz están escritos en JS vanilla.

---

##  Instalación

Al ser un archivo HTML autocontenido, no requiere instalación, servidor ni gestor de paquetes.

1. Descarga el archivo `simuladorparticul_comentado2.html`
2. Colócalo en cualquier carpeta de tu equipo

---

##  Ejecución

1. Abre el archivo `.html` directamente en cualquier navegador moderno (Chrome, Firefox, Edge, Safari)
2. El simulador carga de inmediato, sin pasos adicionales

```
# Opción rápida desde terminal (Linux/Mac)
open simuladorparticul_comentado2.html

# En Windows
start simuladorparticul_comentado2.html
```

> **Nota:** se requiere conexión a internet únicamente para cargar las fuentes de Google Fonts. Sin conexión el simulador funciona igual, solo cambia la tipografía.

---

##  Controles

| Acción | Resultado |
|---|---|
| `Doble clic` en el canvas | Agrega una nueva carga |
| `Drag` sobre una carga | Mueve la carga |
| `Drag` en espacio vacío | Panea el viewport |
| `Scroll` | Zoom centrado en el cursor |
| `Click` sobre una carga | La selecciona |
