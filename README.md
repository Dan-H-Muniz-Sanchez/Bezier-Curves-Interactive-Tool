### Curvas de Bézier Interactivas en Python

Este es un programa interactivo en Python que te permite dibujar y manipular curvas de Bézier. Las curvas de Bézier son una técnica ampliamente utilizada en gráficos por computadora y diseño asistido por computadora para dibujar formas suaves y curvas.

### Curvas de Bézier y Ecuaciones de las SPLINES

Las curvas de Bézier se definen mediante un conjunto de puntos de control. Para una curva de Bézier cúbica, se utilizan cuatro puntos de control $ P_0, P_1, P_2, P_3 $. La ecuación paramétrica para esta curva se define como:

 $$ B(t) = (1-t)^3 \cdot P_0 + 3(1-t)^2 \cdot t \cdot P_1 + 3(1-t) \cdot t^2 \cdot P_2 + t^3 \cdot P_3 $$

Donde \( t \) varía entre 0 y 1.

### Instrucciones de Uso

1. **Descarga del Repositorio:** Descarga todos los archivos del repositorio de GitHub [Curvas de Bézier](https://github.com/tu_usuario/curvas-bezier).

2. **Configuración del Entorno:**
   - Asegúrate de tener Python instalado en tu sistema. Puedes descargarlo desde [python.org](https://www.python.org/downloads/).
   - Se recomienda utilizar un entorno virtual para evitar conflictos con las dependencias del proyecto.

3. **Instalación de Dependencias:**
   - No hay dependencias externas necesarias para este proyecto.

4. **Ejecución del Programa:**
   - Abre una terminal o línea de comandos.
   - Navega hasta el directorio donde descargaste los archivos del repositorio.
   - Ejecuta el archivo `main.py` utilizando Python:
     ```
     python main.py
     ```
   
5. **Interactúa con las Curvas:**
   - Usa el ratón para dibujar puntos de control.
   - El programa conectará automáticamente los puntos de control con curvas de Bézier suaves.
   - Puedes añadir, eliminar y mover puntos de control para ajustar la forma de las curvas.

### Ejemplo de Uso



### Contribuciones y Problemas




