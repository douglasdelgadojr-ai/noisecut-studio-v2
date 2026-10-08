# NoiseCut Studio
1. Sube esta carpeta a un repositorio de GitHub y abre la pestaña **Actions**.
2. Ejecuta **Construir NoiseCut Studio para Windows** con **Run workflow** o sube un cambio.
3. Al terminar, abre la ejecución y descarga el archivo **NoiseCutStudio-Windows** en Artifacts.
4. Descomprime el ZIP y abre `NoiseCutStudio.exe`.
5. Pulsa **Importar**, elige videos, audios o imágenes y añádelos a la línea de tiempo.
6. Selecciona un clip para recortarlo, ajustar imagen, transiciones o efectos.
7. En Audio, ajusta volumen y reducción de ruido; también puedes grabar voz en off.
8. Exporta el video; en Ajustes puedes elegir lienzo, calidad, MP3 o GIF.
9. Los subtítulos Whisper y quitar fondo usan modelos locales opcionales: `pip install -r requirements-ai.txt`.
10. Whisper descarga modelos tiny (~75 MB), base (~145 MB) o small (~460 MB); U²-NetP ocupa unos pocos MB.
11. Las IA se descargan al usarlas; no se incluyen en el instalador. Quitar fondo procesa cada cuadro y puede tardar.
12. El ZIP de Windows incluye FFmpeg GPL de BtbN; redistribuirlo exige cumplir la licencia GPL y sus avisos.
13. Los proyectos guardan rutas de medios; conserva los archivos originales en el mismo lugar para volver a abrirlos.
