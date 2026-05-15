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
<img width="1920" height="1032" alt="Captura de pantalla 2026-05-15 165733" src="https://github.com/user-attachments/assets/9a50789c-6bd4-4ac1-94f9-db83ac093b71" />
<img width="1920" height="1032" alt="Captura de pantalla 2026-05-15 165747" src="https://github.com/user-attachments/assets/e8f16c72-5a6d-40eb-907e-e2ce1676f899" />

 Autores:

Luis Bertiz — Líder del proyecto / Coordinador general
Encargado de organizar tareas, supervisar avances y coordinar la integración final del proyecto.

Joseph Cordoba — Desarrollador de IA y entrenamiento del modelo
Responsable del entrenamiento en Teachable Machine y ajuste del modelo de reconocimiento de poses.

Camilo Herrera — Diseñador UI/UX y Frontend
Encargado del diseño visual de la interfaz HTML/CSS y experiencia de usuario del sistema.

Breiner Ramirez — Desarrollador e integrador del sistema
Responsable de conectar cámara, modelo IA, lógica en JavaScript y pruebas funcionales del detector. 🚀
