# java-evaluacion-final
Tomado de la aplicación gráfica del ejercicio del banco

# Descripción del ejercicio
Tomando la aplicación gráfica del banco, simule el comportamiento de las actividades de un banco mediante hilos. La problemática es la siguiente:
    a) El usuario presiona el botón de Inicio y comenzará un reloj a las 9:00 hrs a incrementarse cada minuto.b)
    b) Habrá solo una cajera al inicio de la aplicación
    c) Los clientes empezarán a llegar e irán haciendo una fila en dirección a la cajera activa. Todas las cajeras comienza con un nivel de energía de 100%
    d) Al momento de llegar un cliente con la cajera, este podrá ejecutar: retirar, depositar o hacer transferencias entre el mismo banco u otros. Estos cantidades oscilan entre 5000 a 35,000 pesos.
    e) El sistema generará un tiempo aleatorio de atención de 500ms a 2 min por cliente (despues se ese tiempo de espera, el cliente se retira de la sucursal bancaria). Dependiendo el tiempo de espera, representará el gaste de energía de la cajera, es decir, de 500ms - 1000ms => -10%, 1001ms - 1500ms => 20% y > 1501 ms => 30%. Cuando el nivel de energía de la cajera, sea 30%, atenderá al último cliente y cerrará la caja por 2 minutos y su regreso su nivel de energía estará lleno nuevamente.
    f) Cada 300 ms llega un nuevo cliente
    g) SI el número de clientes en espera son 6, llegará otra cajera. Y se distribuirán en forma equitativa, lo más posible, los clientes para ambas cajeras.
    h) Si el monto de dinero por cada cajera, supera los 9,000.00 pesos, se hará un corte de caja y se deja 500 pesos en caja
    i) Si un cliente desea retirar una cantidad de dinero, que no cuenta la cajera en su caja, esta ira a la bodega y tomara el dinero para completar el monto solicitado por el cliente. El monto límite de la bodega es de 20,000.
    j) El proceso se detiene, cuando no haya más dinero en la bodega o cuando el usuario desee terminar el juego.
    k) En todo momento, debe de observarse el monto de dinero que posee cada cajera y la bodega, asi como el numero de clientes atendidos.
    l) Si un cliente tarda más de 3.5 minutos en no ser atendido, sera puntos malos para el banco. Se descuenta 2 puntos por cada cliente que se vaya del banco, sin realizar su operación bancaria.
    m) Debe estar en archivo o cuadro de texto, en donde se coloquen los montos, nombres de transacciones y dinero disponible por cada cajera y bodega.

- Es un trabajo grupal, máximo 3 mínimo 3
- Copias similares serán anuladas
- Se evaluará la lógica citada, la interfaz gráfica de la aplicación y la concurrencia de procesos
