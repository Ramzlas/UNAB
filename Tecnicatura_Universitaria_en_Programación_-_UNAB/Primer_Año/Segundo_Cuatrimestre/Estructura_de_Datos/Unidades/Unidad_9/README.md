# Unidad 9: Ordenamiento Topológico

## Contenidos de la Unidad

1. **Definición**  
   - El **ordenamiento topológico** es una secuencia lineal de los nodos de un grafo dirigido acíclico (DAG) tal que para cada arista \((u, v)\), el nodo \(u\) aparece antes que \(v\) en la secuencia.

2. **Ejemplos de Aplicación**  
   - Planificación de tareas con dependencias.  
   - Resolución de sistemas de ecuaciones lineales en dependencia.  
   - Compilación de módulos en lenguajes de programación.  
   - Modelado y análisis de circuitos dirigidos.

3. **Distintas Implementaciones**  
   - **DFS (Depth First Search)**:  
     - Utiliza el recorrido en profundidad para encontrar el orden topológico.  
   - **Kahn's Algorithm**:  
     - Utiliza una cola para procesar los nodos con grado de entrada cero de forma iterativa.  

4. **Análisis de Eficiencia**  
   - Complejidad de **DFS**: \(O(V + E)\), donde \(V\) es el número de vértices y \(E\) el número de aristas.  
   - Complejidad de **Kahn's Algorithm**: \(O(V + E)\).  
   - Comparación de las ventajas y desventajas de cada enfoque dependiendo del tamaño del grafo y el uso de memoria.

---

## Objetivo de la Unidad

Comprender el concepto y las aplicaciones del **ordenamiento topológico** en grafos dirigidos acíclicos (DAG). Aprender las implementaciones basadas en **DFS** y el **algoritmo de Kahn**, y analizar la eficiencia de cada uno para determinar su idoneidad en distintos contextos prácticos.
