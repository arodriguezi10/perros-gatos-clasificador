---
title: Perros Gatos Clasificador
emoji: 🐢
colorFrom: yellow
colorTo: pink
sdk: docker
pinned: false
---

# Clasificador de perros y gatos

Aplicación FastAPI que clasifica imágenes con cuatro modelos de TensorFlow.

## Desplegar en Render

El repositorio incluye un Blueprint en `render.yaml`. Para crear el servicio:

1. Abre [Render Blueprints](https://dashboard.render.com/blueprints).
2. Conecta `arodriguezi10/perros-gatos-clasificador` si aún no está conectado.
3. Selecciona el repositorio y confirma la creación del servicio.

El servicio usa el plan gratuito y Docker. Render asigna el puerto mediante la
variable `PORT`; la aplicación la detecta automáticamente. Si el servicio se
queda sin memoria al cargar o ejecutar modelos, cambia el plan desde Render a
uno con más memoria.
