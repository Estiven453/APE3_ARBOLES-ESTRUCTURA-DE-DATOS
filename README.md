# Práctica de Estructuras de Datos: Árboles

Este repositorio contiene la solución a diversos problemas de estructuras de datos no lineales, enfocándose en la implementación de árboles N-arios y Binarios tanto en **Java** como en **C++**.

## 🚀 Implementaciones Realizadas

Se han completado los 5 ejercicios propuestos, aplicando conceptos de recursividad y manipulación de punteros/referencias:

### 1. Conteo de Nodos (Árboles N-arios)
* **Objetivo**: Calcular la cantidad total de elementos en un árbol con múltiples hijos por nodo.
* **Lógica**: Se utiliza un recorrido recursivo que suma el nodo raíz actual más el tamaño de todos sus subárboles hijos.

### 2. Inserción en Árbol Binario de Búsqueda (BST)
* **Objetivo**: Construir un árbol organizado donde los datos se clasifican al ingresar.
* **Lógica**: Si el valor es menor a la raíz, se desplaza a la izquierda; si es mayor o igual, se desplaza a la derecha, manteniendo la propiedad de búsqueda.

### 3. Cálculo de Altura
* **Objetivo**: Determinar la profundidad máxima o nivel más alto del árbol.
* **Lógica**: Se obtiene comparando la altura del subárbol izquierdo y derecho, retornando el valor máximo + 1.

### 4. Recorrido In-Order
* **Objetivo**: Listar los elementos del árbol en un orden lógico (ascendente en el caso de un BST).
* **Lógica**: Sigue la secuencia: Visitar subárbol izquierdo -> Procesar raíz -> Visitar subárbol derecho.

### 5. Inversión de Árbol (Espejo)
* **Objetivo**: Transformar la estructura intercambiando sus lados.
* **Lógica**: Intercambia de forma recursiva los hijos izquierdo y derecho de cada nodo en el árbol.

---

## 🛠️ Instrucciones de Ejecución

### Para C++
Navega a la carpeta `cpp/` y utiliza un compilador como g++:
```bash
g++ NombreArchivo.cpp -o programa
./programa

### Para java
# Nota: Algunos ejercicios requieren compilar Ejercicio2_Binario.java por la clase Nodo
javac Ejercicio2_Binario.java NombreArchivo.java
java NombreClase
