# Prueba Técnica para Backend con Python

## Descripción General

Se proporcionará un archivo CSV denominado **ventas.csv** que simula datos de ventas de una empresa. El dataset incluye, entre otras, las siguientes columnas:

- **date:** Fecha de la venta.
- **_sale_id** Id unico de la venta.
- **product_id:** Identificador único del producto.
- **category:** Categoría del producto.
- **quantity:** Número de unidades vendidas.
- **unit_price:** Precio por unidad.
- **discount:** Descuento aplicado (formato decimal, por ejemplo, 0.1 equivale a un 10%).
- **country:** País en el que se realizó la venta.
- **payment_method:** Método de pago utilizado.

## Requisitos

- **Documentación y Comentarios:**  
  El código debe estar debidamente documentado y contar con comentarios que expliquen las decisiones adoptadas.

- **Calidad y Eficiencia:**  
  Se evaluará la eficiencia del código, el uso correcto de las librerías de Python y el cumplimiento de buenas prácticas en la manipulación y visualización de datos.

- **Optimización:**  
  En caso de que el dataset supere el millón de registros, se valorará la implementación de técnicas de optimización para el manejo de grandes volúmenes de datos.

## Tareas de Análisis de Datos

1. **Limpieza de Datos:**  
   - Identifica y elimina los registros duplicados, asegurándote de conservar únicamente una instancia de cada dato repetido.

2. **Cálculo de Total de Venta:**  
   - Crea una nueva columna denominada **total_venta**, calculada de la siguiente forma:
     ```
     total_venta = quantity × unit_price × (1 - discount)
     ```

3. **Análisis de Ventas:**  
   - Calcula la media de ventas a nivel diario y mensual.  
   - Determina el país con mayor volumen de ventas.  
   - Identifica la mayor venta registrada en un solo día (récord de venta).  
   - Establece cuál es la categoría de producto que menos se vende y la que más se vende.  
   - Genera un ranking (top 3) de los métodos de pago más utilizados.
   - Genera un ranking (Top 5) productos con mayor demanda.


4. **Visualización de Resultados:**  
    - Muestra los resultados obtenidos en la consola o mediante un informe interactivo. (CSV)

5. **PRUEBA SQL**
 - Crea 2 sentecias SQL de algunos del punto 3
