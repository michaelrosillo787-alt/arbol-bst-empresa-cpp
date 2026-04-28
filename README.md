# Sistema de Árbol Binario de Búsqueda (BST) Empresarial

## 1. Descripción

El presente proyecto consiste en el desarrollo de una aplicación en lenguaje C++ que implementa un Árbol Binario de Búsqueda (BST) para la gestión de información de empleados en un entorno empresarial.

El sistema permite almacenar, organizar y consultar registros utilizando como clave principal el código del empleado, garantizando un acceso eficiente a los datos mediante las propiedades del BST.

La interacción con el usuario se realiza a través de un menú en consola que facilita la ejecución de las diferentes operaciones disponibles.

---

## 2. Objetivos

### 2.1 Objetivo General

Desarrollar una aplicación en C++ que implemente un Árbol Binario de Búsqueda para la gestión de empleados.

### 2.2 Objetivos Específicos

* Implementar la estructura de nodos para el almacenamiento de datos.
* Desarrollar las operaciones fundamentales del BST:

  * Inserción de nodos
  * Búsqueda de información
  * Recorridos del árbol
* Determinar propiedades del árbol como altura y nodos hoja.
* Aplicar principios de programación estructurada u orientada a objetos, según el diseño implementado.

---

## 3. Funcionalidades del Sistema

El sistema ofrece las siguientes opciones:

1. Insertar empleado
2. Buscar empleado
3. Mostrar raíz
4. Recorrido inorden
5. Recorrido preorden
6. Recorrido postorden
7. Mostrar altura del árbol
8. Mostrar nodos hoja
9. Cargar datos de prueba
10. Salir

---

## 4. Estructura del Programa

El programa se organiza en los siguientes componentes:

* Nodo:

  * Código del empleado
  * Nombre
  * Cargo
  * Referencias a los nodos hijos (izquierdo y derecho)

* Árbol Binario de Búsqueda:

  * Nodo raíz
  * Métodos para inserción, búsqueda y recorridos

---

## 5. Tecnologías Utilizadas

* Lenguaje de programación: C++
* Compilador: MinGW (g++)
* Entorno de desarrollo: Visual Studio Code

---

## 6. Instrucciones de Ejecución

1. Compilar el programa:

```bash id="t4ykqb"
g++ Deber1.cpp -o programa
```

2. Ejecutar el programa:

```bash id="x3sp04"
.\programa
```

---

## 7. Pruebas Realizadas

Se llevaron a cabo las siguientes pruebas para verificar el correcto funcionamiento del sistema:

* Ejecución del menú principal
* Inserción de registros de empleados
* Búsqueda de elementos existentes y no existentes
* Recorridos del árbol (inorden, preorden y postorden)
* Cálculo de la altura del árbol
* Identificación de nodos hoja
* Carga automática de datos de prueba

Los resultados obtenidos evidencian el cumplimiento de los requisitos funcionales establecidos.

---

## 8. Datos de Prueba

| Código | Nombre           | Cargo        |
| ------ | ---------------- | ------------ |
| 50     | Empresa UTA      | Raíz         |
| 30     | Gerente Ventas   | Nodo interno |
| 70     | Gerente Finanzas | Nodo interno |
| 20     | Empleado 1       | Nodo hoja    |

---

## 9. Conclusiones

* Se implementó correctamente un Árbol Binario de Búsqueda funcional para la gestión de empleados.
* La estructura permite organizar la información de manera eficiente y facilitar su consulta.
* Se reforzaron los conceptos fundamentales relacionados con estructuras de datos jerárquicas.

---

## 10. Recomendaciones

* Implementar árboles balanceados (por ejemplo, AVL) para optimizar el rendimiento en casos de inserciones desbalanceadas.
* Incorporar validaciones de entrada para mejorar la robustez del sistema.
* Considerar el desarrollo de una interfaz gráfica para futuras versiones.

## 11. Capturas

### Inserción

![image alt](https://github.com/michaelrosillo787-alt/arbol-bst-empresa-cpp/blob/64dac101e49e2a5e142064e3f779d44936505751/1.png)

### Búsqueda 

![image alt](https://github.com/michaelrosillo787-alt/arbol-bst-empresa-cpp/blob/64dac101e49e2a5e142064e3f779d44936505751/2.png)

### Mostrar Raíz 

![Raíz](https://github.com/michaelrosillo787-alt/arbol-bst-empresa-cpp/blob/64dac101e49e2a5e142064e3f779d44936505751/3.png)

### Recorrido In-Order

![In-Order](https://github.com/michaelrosillo787-alt/arbol-bst-empresa-cpp/blob/64dac101e49e2a5e142064e3f779d44936505751/4.png)

### Recorrido Pre-Order

![Pre-Order](https://github.com/michaelrosillo787-alt/arbol-bst-empresa-cpp/blob/64dac101e49e2a5e142064e3f779d44936505751/5.png)

### Recorrido Post-Order
  
  ![Post-Order](https://github.com/michaelrosillo787-alt/arbol-bst-empresa-cpp/blob/64dac101e49e2a5e142064e3f779d44936505751/6.png)

### Mostrar altura
  
![Altura](https://github.com/michaelrosillo787-alt/arbol-bst-empresa-cpp/blob/64dac101e49e2a5e142064e3f779d44936505751/7.png)

### Mostrar Hojas

![Hojas](https://github.com/michaelrosillo787-alt/arbol-bst-empresa-cpp/blob/64dac101e49e2a5e142064e3f779d44936505751/8.png)
