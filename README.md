**INFORME DE PRUEBA DE CONTACTO SOBRE LA OPTIMIZACIÓN DE DESCUENTOS**

**Objetivo**
Verificar si la pérdida de margen de ganancias en las ventas de productos puede ser atribuida en parte a una mala o inexistente política de descuentos de la empresa, y sugerir posibles lineamientos para gestionar dichos descuentos de forma alineada con el volumen y el valor de las ventas.

**Análisis**
Se realizaron 6 consultas SQL para extraer datos específicos con el fin de verificar si la hipótesis planteada en el objetivo puede ser considerada correcta:
•	Tasa media de descuento por número de unidades pedidas: Verificamos si los pedidos más grandes reciben mayores descuentos.
•	Tasa media de descuento por importe total de ventas de cada cliente: Analizamos si los descuentos están alineados con el volumen de facturación de los clientes.
•	Tasa de descuento medio por comercial: Evaluamos la consistencia y discrecionalidad en la aplicación de descuentos entre los distintos asesores comerciales.
•	Tasa de descuento medio comparado con el margen medio de cada categoría de productos: Comprobamos si los descuentos aplicados son coherentes con los márgenes reales de los productos.
•	Tasa media de descuento por año y mes: Analizamos la evolución temporal y estacionalidad de los descuentos aplicados.
•	Porcentaje de comisión sobre ventas totales del comercial comparado con el descuento medio que aplica: Estudiamos la relación e impacto entre las comisiones percibidas por los comerciales y los descuentos que deciden otorgar.

**Conclusiones**
Relacionadas con el Cliente (Client related)
•	Descuento sobre el importe total de ventas:
o	Clientes con volúmenes de ventas similares no obtienen los mismos niveles de descuento; por lo tanto, se demuestra que los descuentos no aumentan de forma proporcional al volumen de compra.
•	Descuento según el margen del producto:
o	Los descuentos otorgados no son proporcionales al margen de ganancias que deja cada producto. Los márgenes más altos no siempre están vinculados a los descuentos más bajos, lo que genera ineficiencia.
Relacionadas con el Vendedor (Seller related)
•	Comisión sobre la venta del producto:
o	Vendedores con estructuras de comisiones similares aplican descuentos drásticamente diferentes a la hora de cerrar una venta. No existe una política clara que regule las comisiones en función de los descuentos otorgados en los productos vendidos.
Relacionadas con el Producto (Product related)
•	Margen de ganancia y descuento aplicado por categoría de productos:
o	Existe una desconexión total entre el margen de ganancia de cada categoría y su descuento aplicado. Se detectaron casos críticos donde se aplican descuentos de hasta el 10% a categorías de productos cuyos márgenes de ganancia son inferiores al 10%, absorbiendo por completo la rentabilidad.

**Recomendaciones**
•	Implementar una matriz de descuentos estandarizada: Establecer un sistema de descuentos automatizado que siga criterios estratégicos rígidos basados en el volumen de compra, el valor de las ventas y el margen de ganancia específico de cada producto y/o categoría.
•	Auditoría y alineación de incentivos comerciales: Realizar un seguimiento continuo sobre los descuentos aplicados por la fuerza comercial y reestructurar el esquema de incentivos, asegurando que las comisiones sean directamente proporcionales al volumen de ventas y penalizadas contractualmente por los descuentos excesivos aplicados.

**Recurso Complementario: Acceso al Archivo de Datos en Excel**
En el repositorio se encuentra alojado el archivo Excel con el sustento de las conclusiones y recomendaciones presentadas en este README.
