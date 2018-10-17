# Stack-y-Queue


Stack y Queue
Las pilas (Stack) y las colas (Queue) son dos colecciones muy similares entre sí ya que solo varia la forma en que guardan y extraen los elementos que contienen. En ciertas cosas estas dos colecciones se parece a un ArrayList, como por ejemplo que soporta el redimensionamiento automático y que los elementos son almacenados como objetos (System.Object). Pero también tienen algunas diferencias, como por ejemplo que no se puede cambiar su capacidad y no se puede acceder a sus elementos a través de índices.
La pila (Stack), es una colección en la que todo nuevo elemento se ingresa al final de la misma, y únicamente es posible extraer el ultimo elemento de la colección. Por este comportamiento, el Stack es conocido como una colección LIFO (Last Input Fisrt Output) ya que siempre el ultimo elemento ingresado a la colección, será el primero en salir.
La cola (Queue), tiene el comportamiento contrario a la pila. Todo nuevo elemento se agrega al principio de la colección y solo se puede extraer el ultimo elemento. Por esta razón, la cola se conoce como una colección FIFO (Fisrt Input First Output) ya que el primer elemento que ingresa a la cola es el primer elemento que sale. 

Las colecciones Stack y Queue se encuentran en el espacio de nombres System.Collections como todas las colecciones no genéricas.
Para implementar cada una de ellas se debe utilizar la clase Stack y Queue respectivamente y utilizar sus métodos que ofrecen la posibilidad de agregar elementos a la colección y extraer elementos según el comportamiento de la colección que se este utilizando.
