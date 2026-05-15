⚽ Pose Detector — CR7 vs Lewandowski

Proyecto de reconocimiento de poses en tiempo real utilizando TensorFlow.js y Teachable Machine Pose.
La aplicación detecta si la postura del usuario se parece más a una celebración de Cristiano Ronaldo (CR7) o Robert Lewandowski usando la cámara web.

🚀 Tecnologías utilizadas
HTML5
CSS3
JavaScript
TensorFlow.js
Teachable Machine Pose
PoseNet
📂 Estructura del proyecto
📦 pose-detector
 ┣ 📜 pose.html
 ┣ 📜 model.json
 ┣ 📜 metadata.json
 ┣ 📜 weights.bin
🧠 Clases detectadas

El modelo fue entrenado para reconocer:

CR7
Lewandowski
📸 Características
Detección de poses en tiempo real
Interfaz moderna estilo deportivo
Barras de confianza dinámicas
Visualización de resultados en vivo
Integración con cámara web
Modelo entrenado con Teachable Machine
▶️ Cómo ejecutar el proyecto
1. Clonar el repositorio
git clone https://github.com/tuusuario/pose-detector.git
2. Abrir el proyecto

Puedes abrir directamente:

pose.html

o usar una extensión como Live Server en VS Code.

⚠️ Importante

Por políticas del navegador, algunos navegadores bloquean modelos locales si abres el archivo directamente.

Se recomienda usar un servidor local:

npx serve

o

python -m http.server
🎯 Funcionamiento
El usuario inicia la cámara.
TensorFlow carga el modelo entrenado.
PoseNet detecta puntos corporales.
El modelo clasifica la pose.
Se muestra el jugador con mayor probabilidad.
🏆 Capturas del sistema

Puedes agregar aquí imágenes del proyecto:

![demo](./assets/demo.png)
📚 Modelo

El modelo fue entrenado usando:

Arquitectura: MobileNetV1
Input Resolution: 257
Output Stride: 16
👨‍💻 Autor

Desarrollado por XD XD 🚀
