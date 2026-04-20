# ComparadorImagenes
Prototipo de comparador de imágenes para el curso Automatización del pregrado Creación Digital UdeA (HTML + iframe). Desarrollado con IA
Herramienta simple en HTML, CSS y JavaScript puro para comparar dos imágenes mediante un efecto de crossfade controlado con un slider.

##Funcionalidad
Superposición de dos imágenes
Control de opacidad de la imagen superior mediante slider
Rango:
Izquierda: opacidad 0
Derecha: opacidad 1
Tamaño base: 500x500 (responsive)
Integración mediante iframe

##Estructura
crossfade.html: archivo principal del visor

##Uso
###1. Configurar imágenes

Editar dentro de crossfade.html:

<img src="imagen1.jpg">
<img src="imagen2.jpg">

Se pueden usar rutas locales o URLs.

###2. Integrar con iframe
<iframe 
  src="crossfade.html" 
  width="520" 
  height="580" 
  style="border:none;">
</iframe>

##Características técnicas
Sin dependencias externas
Compatible con navegadores modernos
Código encapsulado para evitar conflictos
Uso de aspect-ratio para mantener proporción
📌 Uso pedagógico

Permite analizar visualmente diferencias entre dos imágenes (arte, fotografía, restauración, etc.) mediante transición progresiva.
