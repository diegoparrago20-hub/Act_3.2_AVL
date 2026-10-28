# Act_3.2_AVL
Proyecto desarrollado en Java utilizando NetBeans, correspondiente a la actividad de Árbol AVL. Consiste en implementar una estructura de datos de búsqueda que se mantiene balanceada automáticamente al insertar o eliminar empleados.

## Equipo #2
CONTRERAS RODRIGUEZ JANIS ISABEL

LIRA DOMINGUEZ BRYANT

PARRA GONZALEZ DIEGO ALBERTO

# Objetivo
Comprender el funcionamiento de los árboles AVL, el uso de rotaciones para mantener el equilibrio y la organización de los empleados mediante su identificador único.

# Tecnologías utilizadas
Java
Java Swing
NetBeans IDE
GitHub

# Características
Registro de empleados con ID, nombre, puesto, departamento y salario.

Inserción y eliminación de empleados con rebalanceo automático.

Búsqueda de empleados mediante su identificador.

Recorridos inorden, preorden y postorden.

Cálculo de amplitud y profundidad del árbol.

Cálculo de altura y factor de equilibrio de los nodos.

Rotaciones simples y dobles para mantener el balance.

Opción para destruir el árbol y eliminar todos sus nodos.

Interfaz gráfica para realizar las operaciones y mostrar resultados.

# Estructura del proyecto
Clase Empleado: almacena los datos de cada empleado y proporciona métodos getters, setters y toString().

Clase NodoAVL: almacena un empleado, las referencias a sus hijos izquierdo y derecho y la altura del nodo.

Clase ArbolAVL: implementa las operaciones del árbol de búsqueda, incluyendo inserción, eliminación, búsqueda, recorridos y rebalanceo automático mediante rotaciones.

Interfaz gráfica: permite interactuar con el árbol mediante campos de entrada, botones, una tabla y un área de resultados.

# Balanceo del árbol
El árbol AVL mantiene su equilibrio automáticamente después de insertar o eliminar empleados. Para ello, utiliza rotaciones simples a la izquierda o derecha y rotaciones dobles cuando es necesario.

# Interfaz gráfica
La interfaz se desarrolla mediante el editor visual GUI Builder de NetBeans y componentes de Java Swing. Permite registrar empleados, ejecutar operaciones del árbol y consultar información sobre su estructura y equilibrio.
