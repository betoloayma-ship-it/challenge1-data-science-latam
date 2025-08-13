Análisis de Rendimiento de Tiendas Alura Store

🎯 Objetivo del Proyecto
El presente análisis tiene como objetivo evaluar el rendimiento de las cuatro tiendas de la cadena Alura Store para identificar la de menor eficiencia. La finalidad es proporcionar al Sr. Juan una recomendación basada en datos sobre qué tienda debería vender para obtener capital para un nuevo emprendimiento.

🛠️ Metodología
Para lograr este objetivo, se siguieron los siguientes pasos utilizando Python con las librerías Pandas, Matplotlib y Seaborn en un entorno de Google Colab:

Carga y Consolidación de Datos: Se cargaron los datos de ventas de las 4 tiendas desde archivos CSV alojados en GitHub.

Limpieza y Preparación: Se unificaron los datos en un solo DataFrame, se estandarizaron los nombres de las columnas, se ajustaron los tipos de datos (numéricos y fechas) y se manejaron los valores nulos para garantizar la calidad del análisis.

Análisis de Métricas Clave: Se calcularon y compararon los siguientes indicadores de rendimiento para cada tienda:

Facturación total (Ingresos).

Calificación promedio de los clientes.

Categorías de productos más vendidas.

Costo de envío promedio.

Visualización de Datos: Se crearon gráficos para presentar los resultados de forma clara, permitiendo una comparación visual directa entre las tiendas.

📊 Hallazgos y Visualizaciones
El análisis arrojó diferencias significativas en el rendimiento de las tiendas, especialmente en dos áreas clave: ingresos y satisfacción del cliente.

Indicadores Principales
Tienda

Facturación Total (Ingresos)

Calificación Promedio (1-5)

Tienda 4

$ 111,048,100

4.05

Tienda 1

$ 108,189,400

3.99

Tienda 2

$ 104,874,500

3.96

Tienda 3

$ 80,681,100

3.08

Gráfico 1: Facturación Total por Tienda
Este gráfico de barras compara los ingresos totales generados por cada tienda. Se observa claramente que la Tienda 3 tiene la facturación más baja, con una diferencia considerable respecto a las demás.

<img width="937" height="555" alt="image" src="https://github.com/user-attachments/assets/1179c258-947b-4e6e-a32d-689531ef23c8" />


Gráfico 2: Calificación Promedio por Tienda
Este gráfico muestra la calificación promedio otorgada por los clientes. Nuevamente, la Tienda 3 destaca por tener la peor valoración, lo que indica problemas de fondo en el servicio o la calidad de los productos.

(Inserta aquí la imagen de tu gráfico de calificaciones)
<img width="837" height="555" alt="image" src="https://github.com/user-attachments/assets/8f272d9f-4222-4fbb-911b-3f4e35699da8" />


📜 Recomendación Final
Basado en los hallazgos, se presenta la siguiente recomendación estratégica:

Estimado Sr. Juan,

Tras un análisis detallado del rendimiento de sus cuatro locales de Alura Store, he llegado a una conclusión clara sobre el mejor curso de acción para facilitar el capital que necesita para su nuevo emprendimiento.

La recomendación es proceder con la venta de la Tienda 3, ya que los datos la señalan consistentemente como el activo de menor rendimiento en su portafolio. Esta decisión se fundamenta en dos pilares críticos que revelan los gráficos de nuestro análisis:

Rendimiento Financiero Deficiente: El gráfico de facturación total demuestra que los ingresos de la Tienda 3 presentan un rezago significativo frente a las demás. Esta brecha en las ventas limita no solo su rentabilidad actual, sino también su potencial de crecimiento futuro.

Baja Satisfacción del Cliente: Este problema de ingresos se ve agravado por una clara insatisfacción del cliente. Como lo confirma el gráfico de calificaciones, la Tienda 3 posee la valoración promedio más baja, una señal de alerta que sugiere problemas subyacentes en la experiencia de compra o en la calidad del servicio que podrían requerir inversiones adicionales para ser solucionados.

En resumen, la combinación de ser la tienda que menos vende y la que más insatisface a los clientes hace de la Tienda 3 la candidata ideal para la venta. Desinvertir en este local es la decisión más lógica, pues le permitirá liquidar el activo menos eficiente de su cadena para inyectar ese capital directamente en su nuevo y prometedor proyecto.

🚀 Cómo Replicar el Análisis
Para ejecutar este análisis, puedes utilizar el cuaderno de Google Colab AluraStoreLatam.ipynb disponible en este repositorio. El cuaderno está configurado para cargar los datos directamente desde las URLs de los archivos CSV y contiene todo el código necesario para la limpieza, análisis y visualización de los datos.
