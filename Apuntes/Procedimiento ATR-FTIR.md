# Procedimiento ATR-FTIR
## ⚗️ Materiales:
- Piseta con alcohol isopropílico (mezcla agua-isopropanol)
- Algodón
- Cuadros de papel encerado
- Cuchara verde de plástico
- Bitácora del Espectrofotómetro IR

## 🔌 Encendido del equipo
1. Retirar el cubrepolvo del equipo.
2. Encender el regulador que está detrás del equipo.
3. Abrir el paso del nitrógeno
	- ⚠️ No se puede medir hasta que el indicador del humedad esté de color azul en lugar de rosado.
4. En la computadora seleccionar el programa OMNIC.
5. Seleccionar método/experimento → GladiATR (segunda opción).
6. Ir a la pestaña `Collect` > `Experiment Setup` para ajustar:
	- Número de Scans (32 ó 100).
	- Formato de lectura (Transmitancia o Absorbancia).

## 📂 Crear carpeta para nuevo análisis
1. Ir a la carpeta `C:\Users\UNAM\Desktop\AULJ` y entrar en la subcarpeta correspondiente al año en curso.
	- En el Escritorio se encuentra un acceso directo a la carpeta "AULJ".
2. Crear una nueva carpeta indicando el número de SIA y el nombre de quien hizo la solicitud de análisis.
	- Ej. `SIA-31 Victor Adrian`.

## 🧪 Leer muestras
1. Limpiar con un algodón y alcohol isopropílico:
	- La base donde se coloca la muestra (el cristal, el círculo adyacente y el resto  de la base).
	- La punta del tornillo que toca la muestra.
	- La espátula de plástico.
2. Seleccionar el botón de `Collect Sample`.
3. Colocar el nombre de la muestra.
	- ℹ️ Conviene seleccionar y copiar el nombre porque después se vuelve a necesitar para guardar los archivos.
4. Seleccionar `Ok` para leer la señal de fondo (background) y esperar a que se complete la barra que aparece en la pantalla.
5. Colocar la muestra sobre la superficie del cristal.
6. Bajar el brazo de la prensa y ajustar el tornillo de soporte de la parte de atrás.
7. Ajustar el tornillo de la prensa hasta el 1er tope, regresar hacia arriba y meter más muestra hacia el cristal (repetir para compactar bien la muestra).
8. Seleccionar `Ok` para leer la muestra.
	- ⚠️ Verificar que no aparezca la banda correspondiente al $CO_2$, la cual se encuentra a $2400-2300~nm^{-1}$.
	- Para eliminar algún espectro, seleccionarlo y hacer click en la opción `Clear`.
9. Guardar con `F12` en formato .spa (spectra) en la carpeta correspondiente a la solicitud de análisis.
10. Guardar con `F12` en formato .csv en la carpeta correspondiente a la solicitud de análisis.
11. Anotarse en la Bitácora del espectrofotómetro IR, indicando el número de muestras leídas y el número total de análisis realizados (aproximado).

>[!IMPORTANT]
>En caso de requerir repetir la muestra no hace falta limpiar la espátula y la punta del tornillo, solamente la base donde se encuentra el cristal.

## 📊 Cálculo de IRSF y %Colágeno
Se realiza sólo en muestras óseas (huesos, molares, esmaltes, etc).
1. Abrir el archivo .spa, de tal forma que sólo haya un espectro en la pantalla.
2. Seleccionar el botón `MACRO Splitting Factor` arriba a la derecha.
3. Hacer click en `Full Sc` (Full scale) para ver el espectro completo.
4. Anotar el valor que aparece como **"SF"** y redondear a 2 cifras después del punto decimal.
5. Seleccionar el botón a la derecha de la pantalla que dice `MACRO Collagen%`
6. Clickear el botón `Replace` que aparece debajo.
7. Seleccionar las áreas de los picos (correspondientes a amidas y fosfatos) como se muestra en la imagen:
	- Para el ajuste de la flecha izquierda: la línea base de integración debe quedar sobre la línea roja del espectro.
	- Para el ajuste de la flecha derecha: debe quedar en el punto más bajo del valle entre los dos picos.

<div align="center">
<img src="https://github.com/ednvp/LGAM_Apuntes/blob/1ec8547eac3427b16fd1ea2b32bdfdf232a2ef4c/Imagenes/Porcentaje%20de%20Col%C3%A1geno.png" alt="Porcentaje de colágeno" width="500">
</div>

8. Anotar el valor que aparece como **"Collagen%"** y redondear a 2 cifras después del punto decimal
9. ⚠️ No volver a guardar porque se sobrescribe.
	- Hacer click en la cruz gris para cerrar el espectro.
	- Seleccionar `No` para no guardar el archivo.

## 🪟 Crear ventanas adicionales
1. Ir a la pestaña `Window` > `New Window` (también se puede usar el atajo Ctrl+N)
2. Ponerle un nombre a la nueva ventana

## 💾 Exportar las imágenes de los espectros
1. Colocar en una misma ventana todos los espectros correspondientes al SIA
2. Revisar que se encuentran todos las muestras (corroborar con la lista de las hojas)
3. Llamar a Ulises para ver si todos están bien o si hay que agregar alguna observación
4. Hacer click en el botón `Stack Spectra`.
5. Hacer click en el botón `Full Spectra`.
6. Revisar que el nombre y el orden está correcto (tal cual como en la solicitud) 
7. Hacer click en la ventana de los espectros, de tal forma que se vea un recuadro con los bordes resaltados (color negro).
8. Usar `Control + C` para copiar la imagen.
9. Abrir un documento de Word para pegar la imagen.
