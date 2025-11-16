# Sistema-solar


Una visualización interactiva y colorida del Sistema Solar construida con Three.js, mostrando 8 planetas orbitando alrededor del Sol, cada uno con su propia luna.

## Características

- Sol central con rotación
- 8 planetas con diferentes tamaños, colores y velocidades orbitales
- Cada planeta tiene su propia luna orbitando a su alrededor
- Vista desde arriba del sistema solar
- Diseño colorido y minimalista
- Responsive - se adapta a cualquier tamaño de pantalla
- Animaciones suaves con 60 FPS

## Demo

El sistema muestra los planetas en órbitas circulares con velocidades decrecientes según su distancia del Sol, simulando de forma simplificada las leyes de Kepler.

## Tecnologías

- Three.js (r128) - Librería de gráficos 3D
- HTML5 - Estructura
- JavaScript (ES6) - Lógica y animaciones

## Instalación

Clona este repositorio y abre el archivo index.html en tu navegador web favorito.

No requiere instalación de dependencias. Three.js se carga desde CDN.

## Uso

Simplemente abre index.html en tu navegador y disfruta de la animación. La visualización se ejecuta automáticamente.

## Estructura de archivos

El proyecto contiene:
- index.html - Archivo HTML principal
- Main.js - Lógica del sistema solar
- README.md - Este archivo

## Implementación

El proyecto utiliza una clase Planeta que encapsula la lógica de cada planeta y su luna, manejando la órbita alrededor del Sol y la rotación de la luna alrededor del planeta.

Cada planeta tiene propiedades únicas:
- Distancia orbital desde el Sol
- Radio (tamaño)
- Color distintivo
- Velocidad orbital (los más cercanos son más rápidos)
- Luna propia con color personalizado

## Personalización

Puedes personalizar fácilmente los planetas modificando los parámetros: distancia, radio, color, velocidad y color de la luna.

## Características técnicas

- Cámara: Vista cenital (desde arriba) a 600 unidades de altura
- Iluminación: PointLight central simulando el Sol
- Geometría: SphereGeometry para todos los cuerpos celestes
- Materiales: MeshBasicMaterial para colores sólidos y brillantes
- Animación: RequestAnimationFrame para 60 FPS suaves

## Futuras mejoras

- Controles de cámara interactivos
- Texturas realistas para planetas
- Cinturón de asteroides
- Información de cada planeta al hacer clic
- Anillos para planetas como Saturno
- Velocidades orbitales más precisas
- Campo de estrellas de fondo

## Autor

Claudia Lorena Cerquera

