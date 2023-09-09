# WhisperGUI

![imagen](https://user-images.githubusercontent.com/106337749/221340883-4b437d03-97fc-42ee-821e-dd04096323fe.png)

> Este proyecto es una interfaz gráfica de usuario (GUI) Whisper que creé en dos horas, junto con un paquete de instalación rápida. Permite operar rápidamente con Whisper sin necesidad de usar comandos, y facilita a quienes no quieren instalar muchas cosas manualmente (aunque Python y FFmpeg deben instalarse por separado).

> Actualización del 30 de marzo de 2023: Recientemente, alguien informó un problema para detectar la GPU, y actualmente se sospecha que puede estar relacionado con el Toolkit de CUDA. Si no tienes instalado el Toolkit de CUDA, puedes intentar instalar primero el Toolkit de CUDA de Nvidia. Si ya lo tienes instalado pero aún no se muestra la GPU, intenta ajustar la línea 22 del archivo Bat, cambiando la versión de CUDA de Torch a la misma que tiene tu Toolkit de CUDA.

> Actualización del 12 de agosto de 2023: He probado a empaquetar este proyecto como un archivo ejecutable. No es necesario ejecutar setup.bat para crear un entorno virtual, simplemente descárgalo, descomprímelo y ejecuta **main.exe** para usarlo. Puedes descargarlo en la sección de releases y probarlo.

[OpenAI Whisper](https://github.com/openai/whisper)

## Propósito del Proyecto

El propósito de este proyecto es proporcionar un entorno de ejecución de Whisper preconfigurado para facilitar su uso, permitiendo a la mayoría de los usuarios operar a través de esta interfaz gráfica sin necesidad de utilizar comandos.

## Funcionalidades

Actualmente, admite las siguientes funciones de Whisper:
1. Seleccionar múltiples archivos de audio.
2. Elegir la ubicación de salida.
3. Elegir el modelo a utilizar.
4. Seleccionar el idioma de reconocimiento.
5. Elegir el dispositivo de uso (CPU, tarjeta gráfica específica).
6. Traducir subtítulos al inglés.

## Capturas de Pantalla

> Guía de operación: Seleccionar archivo > Seleccionar dispositivo para ejecutar el modelo > Completado

![Seleccionar modelo](https://user-images.githubusercontent.com/106337749/218459288-0fd24ee4-4ed6-49c9-a3f4-1fd97976a89d.png)
![Seleccionar dispositivo](https://user-images.githubusercontent.com/106337749/218459323-faaf2d8d-0a68-4bfc-a6e3-62e45b94ad0f.png)
![Operación completada](https://user-images.githubusercontent.com/106337749/218460468-a801fe68-0f01-479d-a4bd-4f04eea1af41.png)

## Instalación

> Por favor, asegúrate de tener instalado Python 3.7 o superior, así como FFmpeg.

A continuación, se detalla cómo ejecutar este proyecto en tu computadora.

### Obtén el Proyecto

```bash
git clone git@github.com/ADT109119/WhisperGUI.git
```

**O descárgalo directamente como ZIP desde la página de GitHub.**

### Verifica la Presencia de Python y FFmpeg en tu Computadora

```bash
python --version
ffmpeg -version
```

### Ejecuta setup.bat

Simplemente ejecuta setup.bat en la carpeta y espera a que se configure el entorno virtual.

### Ejecuta el Proyecto

Simplemente ejecuta run.bat en la carpeta y, si no hay errores, verás la interfaz gráfica.

## Descripción de Carpetas

- model - Ubicación de los modelos.
- output - Carpeta de salida predeterminada.
- venv - Carpeta del entorno virtual.
...

## Tecnologías del Proyecto

- Python
- tkinter
- ttkbootstrap

## Contacta al Autor

Puedes ponerte en contacto conmigo a través de los siguientes medios:

- [Email: 2.jerry32262686@gmail.com](mailto:2.jerry32262686@gmail.com)
...

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta [LICENSE](https://github.com/ADT109119/WhisperGUI/blob/main/LICENSE) para más detalles.
