# Proyecto_de_Clase_DS
En este proyecto se realizó un analisis de un Dataset con datos sobre la contaminación del aire en una ciudad de Italia, con los metodos vistos en clase
Primero se realizó una limpieza del DataSet pues tenía varios valores nulos y alguno con el valor "-200" que indicaba que el valor no se había registrado, para esto se sustituyó con el valor medio
Después se realizaron gráficas de la contaminación de cada sustancia a lo largo de los días, para esto se sumarón los datos de un solo día y se eliminó la columna hora
Una vez hecho esto se realizó una comparación de la correlación de cada variable y se procedió a aplicar modelos de machine learning para predecir la humedad relativa, se usaron modelos de regresión lineal y de random Forest
