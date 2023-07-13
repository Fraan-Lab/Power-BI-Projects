# Proyect 1: Bakery sales

<p> [ENG] The dataset downloaded from [Kaggle.com](https://www.kaggle.com/) belongs to a French bakery and provides the daily transaction details of customers from 2021-01-01 to 2022-09-30. This dataset has 234.005 records and 6 fields, these fields are transaction identifier number, order date and time, item name, quantity and price per item. </p>

<p> [ESP] El conjunto de datos descargado de [Kaggle.com](https://www.kaggle.com/) pertenece a una panadería francesa y proporciona los detalles de las transacciones diarias de los clientes desde 2021-01-01 hasta 2022-09-30. Tiene 234.005 registros y 6 campos, estos campos son el número identificador de la transacción, la fecha y hora del pedido, el nombre del artículo, la cantidad y el precio por artículo. </p>

## Data Cleaning

[ENG] First, the first record was transformed in Power Query to be the table header. Then, in the Quantity field, the records with negative values were eliminated. Subsequently, non-numeric characters in the Price field were eliminated by replacing these non-numeric values with empty spaces. Then, the data type in the Price field was changed in order to transform its records to decimal data. Finally, records were eliminated from the Price field where the value was equal to 0.

[ESP] Primeramente, en Power Query se transformó el primer registro para que este sea el encabezado de la tabla. Luego en el campo Cantidad, se eliminaron todos los registros con valores negativos. Posteriormente, se eliminaron caracteres no numéricos en el campo Precio reemplazando dichos valores no numéricos por espacios vacíos. Después  se cambió el tipo de dato en el campo Precio con la finalidad de transformar sus registros a datos de tipo decimal. Finalmente se eliminaron registros del Campo Precio en donde el valor era igual a 0.

## Analysis & Vizualization

[ENG] The cleaned data set was loaded into Power BI Desktop in order to create a bakery sales report comparing transactions between 2021 and 2022. This Dashboard indicates the total sales and orders for each year. Next, a table was created that filters the 7 products with the highest sales in monetary terms and a graph was created that filters the 7 best-selling products in terms of quantity. On the other hand, a graph was created that indicates in which schedules of each year the most sales were made and another graph was also created to summarize in which months the highest sales were recorded.

[ESP] El conjunto de datos limpiados se cargaron a Power BI Desktop con la finalidad de crear un reporte de ventas de la panadería en donde se compara las transacciones entre el año 2021 y 2022. Este Dashboard indica el total de ventas y de pedidos de cada año. Después se creó una tabla que filtra los 7 productos con más ventas en términos monetarios y se creó un gráfico que filtra los 7 productos más vendidos en términos de cantidad. Por otra parte, se creó un gráfico que indica en qué horarios de cada año se realizaron más ventas y también se creó otro gráfico para resumir en qué meses se registraron las mayores ventas.

![image](https://github.com/Fraan-Lab/Power-BI-Portfolio/blob/main/Bakery%20sales/Dashboard%202021%20Bakery_sales.png)
![image](https://github.com/Fraan-Lab/Power-BI-Portfolio/blob/main/Bakery%20sales/Dashboard%202022%20Bakery_sales.png)
