# Tareas_Progra_III_2.0
En este repositorio de adjuntaran las tareas y trabajos que se realizaran a lo largo del curso de progra III

<h1>Tarea No.1</h1>
<h2>Realizacion de pasos en Hithub</h2>

<p>Para poder realizar el proyecto de manera colabortativa en Githubb se realizaron los siguientes pasos:
1) Primero se realizo la creacion de un repositorio en Github wed al cual se le asigno un nombre de acuerdo a la utilidadn y se le asigno una descripción 
2) Luego se hizo Marquen la opción "Initialize this repository with a README" para crear un archivo README.md inicial.
3) Se crearon las dos ramas, una con el nombe de cada perosna del proyecto para poder trabajar individualmente y de esta menara poder fusionar ambas ramas
y juntar el trabajo de ambos colaboradores
4) Para agregar a un colaborador nos fuimos a opciones y luego a colaboradores para ahi ingresar el nombre del colaborador de deseamos agregar y enviamos 
una solicitud por correo para poder agregar al colaborador 
5)Se fue a la seccion de codigo para clonar el repositorio del gidhub web al guthub de escritorio
6) Una vez clonado el repositorio de selecciono la rama en la que se desea trabajar y realizo la creacion del proyecto en el ide de ECLIPCE 
7) Para la creacion del proyecto en ECLIPSE se selecciono como ruta de guardado la ruta de la carpeta con Github con el proyecto en el que vamos a trabajar 
8) Una vez creado y realizado el proyecto en Eclipse se veran los cambios automaticamente en Github de escritorio y una vez teniendo eso se realizo un commit
9) En el commit se le asigno un titulo y una descripcion para luego realizar un push y cargar la información hecha en el IDE hacia el Guthub web
10) Como paso fina se realizo un pull para enlazar las ramas individuales con la rama Principla "Main"</p>

<h2>Listas simples En ECLIPCE</h2>
<h2>Introducción</h2>
<p>El proyecto de listas simples se creo con el fin de practicar los conceptos de estructuras de datos y programación orientada a objetos en Java.

En este proyecto, se desarrolla la implementación de una lista enlazada simple. Una lista enlazada es una estructura de datos dinámica que se compone de nodos enlazados secuencialmente, donde cada nodo contiene un valor y una referencia al siguiente nodo en la secuencia.

Para ello, se ha creado la clase Nodo, que representa los nodos individuales en la lista enlazada. Cada nodo almacena un valor entero. Además, se ha implementado la clase ListaSimplementeEnlazada, la cual proporciona métodos para llevar a cabo diversas operaciones en la lista enlazada, como inserción, eliminación, búsqueda e impresión de elementos.
</p>

<h2>Funcionalidad</h2>
<p> A continuacion se mostrara un diccionario con la funcionalidad tecnica de los codigos utilizados en el IDE:

1) ### Clase Nodo:
   
Funcionalidad:
La clase `Nodo` representa un nodo individual en una lista enlazada simple. Cada nodo contiene un valor (`dato`) y una referencia al siguiente nodo en la lista (`siguiente`).

Diccionario:
dato: Variable que almacena el valor del nodo.
siguiente: Referencia al siguiente nodo en la lista.
Constructor: Inicializa un nodo con un valor dado y establece la referencia al siguiente nodo como `null` inicialmente.

2) ### Clase `ListaSimplementeEnlazada`:
   
Funcionalidad:
La clase `ListaSimplementeEnlazada` implementa una lista enlazada simple. Proporciona métodos para insertar nodos al inicio o al final de la lista, insertar en una posición específica, eliminar nodos, buscar elementos y mostrar la lista.

Diccionario:
cabeza: Referencia al primer nodo de la lista.Constructor: Inicializa la lista como vacía.
insertarAlInicio(int dato): Inserta un nuevo nodo con el valor `dato` al inicio de la lista.
insertarAlFinal(int dato): Inserta un nuevo nodo con el valor `dato` al final de la lista.
insertarEnPosicion(int dato, int posicion): Inserta un nuevo nodo con el valor `dato` en una posición específica de la lista.
eliminarPrimero(): Elimina el primer nodo de la lista.
eliminarUltimo(): Elimina el último nodo de la lista.
eliminarEnPosicion(int posicion): Elimina el nodo en una posición específica de la lista.
buscar(int dato): Busca un elemento con el valor `dato` en la lista.
imprimirLista(): Imprime los elementos de la lista.

3) ### Clase Main:
   
Funcionalidad: 
La clase Main contiene el método main, que es el punto de entrada del programa. En este método, se crea un objeto Scanner para recibir la entrada del usuario y un objeto ListaSimplementeEnlazada para manipular la lista enlazada. Luego, se muestra un menú interactivo que permite al usuario realizar diversas operaciones en la lista, como inserción, eliminación, búsqueda e impresión de elementos.

Diccionario:
main(String[] args): Método principal del programa.
Scanner scanner: Objeto Scanner para recibir la entrada del usuario.
ListaSimplementeEnlazada lista: Objeto ListaSimplementeEnlazada para manipular la lista enlazada.
Bucle while (true): Bucle infinito que muestra el menú interactivo y procesa las opciones del usuario.
Menú interactivo: Muestra opciones para insertar elementos al inicio o al final de la lista, insertar en una posición específica, eliminar elementos, buscar elementos y mostrar la lista completa.
Switch-case: Maneja las diferentes opciones seleccionadas por el usuario y llama a los métodos correspondientes de la clase ListaSimplementeEnlazada.
</p>

