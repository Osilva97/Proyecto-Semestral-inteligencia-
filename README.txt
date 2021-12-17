# Proyecto-Semestral-inteligencia-

primero se cargan las librerias necesarias para poder ejecutar el modelo, que son las siguientes: matplotlib; pandas; numpy; tensorflow y keras.

se carga la base de cifar10 como dataset para validación y entrenamiento, separando en dataset X_train e Y_train, ploteando uno de los elementos contenidos en la base.

Separamos los set de datos X e Y en trainning y validation, mediante skerlean, ademas se realiza el bloque de precesamieto de imagenes.

Se sigue implementado la clase que proporcionara la estructura al modelo ResNet18, creando los bloques correspondientes a la convolucion 2D, batcha normalization, ademas de definir las entradas correspondientes, luego se define la clase que contiene las caracteriticas y parametros del modelo como las capas 2D, los ma pooling , para posteriormente definir sus salidas.

a continuación se define el modelo para la sección entreamiento y validación, en donde se obtienen la cantidad de parametros presente y las dimensiones de la red.

finalemnte se plantea la seccion de entrenamiento, usando el criterio de "earling stopping" importado desde keras, el entrenamiento cuenta con 50 epoch y cada una realiza 156 iteraciones sobre los set de datos, para posteriormente printear la metricas obtenidas y plotear las curva de aprendiaje.

