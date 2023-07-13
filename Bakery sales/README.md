# Proyect 1: Bakery sales

<p> [ENG] The  dataset belongs to a French bakery and provides the daily transaction details of customers from 2021-01-01 to 2022-09-30. This dataset has 234.005 records and 6 fields, these fields are transaction identifier number, order date and time, item name, quantity and price per item. </p>

<p> [ESP] El conjunto de datos pertenece a una panadería francesa y proporciona los detalles de las transacciones diarias de los clientes desde 2021-01-01 hasta 2022-09-30. Tiene 234.005 registros y 6 campos, estos campos son el número identificador de la transacción, la fecha y hora del pedido, el nombre del artículo, la cantidad y el precio por artículo. </p>

## Data Cleaning

[ENG] First, the first record was transformed in Power Query to be the table header. Then, in the Quantity field, the records with negative values were eliminated. Subsequently, non-numeric characters in the Price field were eliminated by replacing these non-numeric values with empty spaces. Then, the data type in the Price field was changed in order to transform its records to decimal data. Finally, records were eliminated from the Price field where the value was equal to 0.

[ESP] Primeramente, en Power Query se transformó el primer registro para que este sea el encabezado de la tabla. Luego en el campo Cantidad, se eliminaron todos los registros con valores negativos. Posteriormente, se eliminaron caracteres no numéricos en el campo Precio reemplazando dichos valores no numéricos por espacios vacíos. Después  se cambió el tipo de dato en el campo Precio con la finalidad de transformar sus registros a datos de tipo decimal. Finalmente se eliminaron registros del Campo Precio en donde el valor era igual a 0.

## Analysis & Vizualization

[ENG] The cleaned data set was loaded into Power BI Desktop in order to create a bakery sales report comparing transactions between 2021 and 2022. This Dashboard indicates the total sales and orders for each year.

[ESP] El conjunto de datos limpiados se cargaron a Power BI Desktop con la finalidad de crear un reporte de ventas de la panadería en donde se compara las transacciones entre el año 2021 y 2022. Este Dashboard indica el total de ventas y de pedidos de cada año.
