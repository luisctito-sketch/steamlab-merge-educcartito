# STEAMLab · Educcartito con Merge Cube

## Qué contiene
- `index.html`: portada e instrucciones.
- `visor.html`: visor de realidad aumentada.
- `style.css`: estilos.
- `educcartito.png`: figura de Educcartito usada como holograma.

## Qué necesitas
- Tu Merge Cube.
- El mismo archivo privado `targets.mind` que ya generaste con las seis caras correctas.

## Cómo publicar en GitHub
1. Crea un repositorio nuevo, por ejemplo `steamlab-merge-educcartito`.
2. Sube todos los archivos de esta carpeta a la raíz del repositorio.
3. En **Settings → Pages**, activa **Deploy from a branch**, rama `main`, carpeta `/(root)`.
4. Abre la URL de Pages.

## Cómo probar en el celular
1. Abre `visor.html` desde Chrome.
2. Pulsa **Seleccionar archivo** y elige `targets.mind` desde tu carpeta Descargas.
3. Pulsa **Activar cámara y Educcartito**.
4. Apunta a una cara entrenada del Merge Cube con buena iluminación.
5. Educcartito debería aparecer flotando sobre la cara detectada.

## Observaciones
- `targets.mind` se mantiene local; no hace falta subirlo a GitHub.
- El reconocimiento entre caras sigue siendo experimental, porque MindAR trata cada cara como un objetivo independiente.
- Si Educcartito aparece demasiado pequeño o demasiado grande, más adelante podemos ajustar escala, altura y efectos.

## Corrección de importaciones
Se añadió `three/addons/` al mapa de importaciones para que MindAR pueda resolver `CSS3DRenderer.js`. Sustituye `visor.html` y recarga la página.
