# Calculadora de reducción de jornada – FETICO

Web estática preparada para publicarse con **GitHub Pages**.

## Archivos
- `index.html`: calculadora web.
- `assets/logo-fetico.png`: logotipo corporativo.
- `.nojekyll`: evita el procesamiento de Jekyll.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub, por ejemplo `calculadora-reduccion-fetico`.
2. Sube el contenido de esta carpeta (no hace falta subir la carpeta contenedora).
3. En el repositorio, entra en **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/(root)`, y guarda.
6. GitHub mostrará la dirección pública de la web en esa misma sección.

## Actualizar la calculadora
Cuando haya cambios, sustituye `index.html` y/o los recursos de `assets/` y haz commit en la rama publicada.

## Nota
La estructura está preparada para GitHub Pages. Los cálculos y reglas de la calculadora se mantienen como estaban en la versión de trabajo; el cambio de esta entrega es principalmente visual y de empaquetado.
