Vídeos aprobados de Cuaderno de vuelo.

- Cada MP4 está aquí solo mientras Metricool lo publica en TikTok; después se borra del árbol (sigue en el historial).
- `catalogo.json` y las portadas (`.jpg`) se quedan. La sección «Vídeos» de https://cascos.online/preparacion-air-europa/videos.html lee el catálogo y saca del historial el vídeo y la portada de cada entrada.
- El catálogo lo mantiene `herramientas/catalogo_web.py` del repo `cuaderno-de-vuelo`.
- Al hacer push, un webhook avisa al servidor (`/preparacion-air-europa/api/videos-hook`).
