# demos-jetracer

* [01_basic_motion.ipynb](01_basic_motion.ipynb): Prueba de motores
* [02_remote_control.ipynb](02_remote_control.ipynb): Control remoto con mando tipo Xbox 360
* [03_video_capture.ipynb](03_video_capture.ipynb): Captura de imágenes
* [04_label.ipynb](04_label.ipynb): Etiquetado de las imágenes capturadas
* [05_train.ipynb.ipynb](05_train.ipynb.ipynb): Entrenamiento de modelo basado en CNN
* [06_mp4_capture.ipynb](06_mp4_capture.ipynb): Ejemplo de captura de vídeo mientras se conduce el coche
* [07_road_follower.ipynb](07_road_follower.ipynb): Conducción automática con el modelo pre-entrenado con opciones de visualización de la predicción en primera persona / grabación de vídeo.

### Problemas con la cámara

Si fallan la inicialización de la cámara, hay que abrir un terminal y:

```
sudo systemctl restart nvargus-daemon
```

### Autocompletado en jupyter lab

```
pip3 install jedi==0.17.2
```
