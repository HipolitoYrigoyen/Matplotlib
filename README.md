# 📊 Visualización de Datos con Matplotlib

![image](https://github.com/user-attachments/assets/bbf3db41-f194-464b-8d43-cccc5a309de5)

## 🗂️ Tipos de Gráficos

1. **Gráficos de Líneas** ✏️
   - Ideal para mostrar tendencias a lo largo del tiempo.
   - Uso: `plt.plot()`

2. **Gráficos de Barras** 📊
   - Útil para comparar cantidades.
   - Uso: `plt.bar()` (vertical) o `plt.barh()` (horizontal)

3. **Gráficos de Dispersión** 🌌
   - Perfectos para mostrar la relación entre dos variables.
   - Uso: `plt.scatter()`

4. **Gráficos de Sectores (Pie Charts)** 🥧
   - Bueno para mostrar proporciones.
   - Uso: `plt.pie()`

5. **Histogramas** 📈
   - Para mostrar la distribución de datos.
   - Uso: `plt.hist()`

6. **Gráficos de Caja (Box Plots)** 📦
   - Útiles para resumir la distribución y detectar outliers.
   - Uso: `plt.boxplot()`

7. **Gráficos de Superficie** 🌐
   - Para visualizar funciones en 3D.
   - Uso: `plot_surface()` con `Axes3D`

## 🎨 Estilos para una Presentación Más Profesional

1. **Estilos Predefinidos** 🎨
   - Usa estilos de Matplotlib con: `plt.style.use()`
   - Ejemplos: `seaborn`, `ggplot`, `fivethirtyeight`, `bmh`

2. **Personalización de Colores** 🌈
   - Elige paletas de colores coherentes usando `seaborn` o `color_palette()`.

3. **Etiquetas y Títulos** 🏷️
   - Asegúrate de que los ejes y títulos sean claros. Usa:
     - `plt.xlabel()`
     - `plt.ylabel()`
     - `plt.title()`

4. **Fuente y Tamaño** 🔤
   - Mejora la legibilidad ajustando fuentes y tamaños con `plt.rcParams`.

5. **Leyendas** 📜
   - Añade leyendas con `plt.legend()` para aclarar tus datos.

6. **Grillas** 🕸️
   - Facilita la lectura añadiendo grillas con `plt.grid()`.

7. **Ajustes de Tamaño** 📏
   - Controla el tamaño de la figura con:
     ```python
     plt.figure(figsize=(ancho, alto))
     ```

8. **Exportación de Gráficos** 💾
   - Guarda tus gráficos en alta calidad:
     ```python
     plt.savefig('nombre.png', dpi=300)
     ```


