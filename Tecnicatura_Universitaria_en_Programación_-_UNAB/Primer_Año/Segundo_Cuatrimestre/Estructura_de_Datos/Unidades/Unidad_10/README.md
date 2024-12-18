# Unidad 10: Problema del Camino Mínimo

## Contenidos de la Unidad

1. **Estudio de Distintos Casos**  
   - **Grafos pesados** y **no pesados**.  
   - **Grafos dirigidos** y **acíclicos**.  

2. **Algoritmos para el Camino Mínimo**  
   - **Dijkstra**: Resolución del camino mínimo desde un nodo fuente en grafos con pesos positivos.  
   - **Floyd-Warshall**: Resolución del camino mínimo entre todos los pares de nodos en grafos dirigidos y pesados.

3. **Árbol Generador Mínimo (MST)**  
   - Construcción del árbol que conecta todos los vértices con el costo mínimo en grafos no dirigidos.  
   - **Algoritmo de Prim**: Selección de los bordes más cercanos a un conjunto de nodos conectados.  
   - **Algoritmo de Kruskal**: Selección de los bordes más baratos, evitando ciclos.

4. **Análisis del Tiempo de Ejecución**  
   - **Dijkstra**: \(O(V^2)\) con matriz de adyacencia, \(O((V + E) \log V)\) con heap binaria.  
   - **Floyd-Warshall**: \(O(V^3)\).  
   - **Prim**: \(O(V^2)\) con matriz de adyacencia, \(O((V + E) \log V)\) con heap binaria.  
   - **Kruskal**: \(O(E \log E)\), dependiendo del ordenamiento de las aristas.

---

## Objetivo de la Unidad

Estudiar y comprender el **problema del camino mínimo** en grafos de diferentes tipos, y aplicar algoritmos como **Dijkstra** y **Floyd-Warshall**. Analizar el concepto y la construcción de un **árbol generador mínimo** mediante los algoritmos de **Prim** y **Kruskal**. Evaluar la eficiencia de estos algoritmos para determinar su aplicabilidad en problemas reales.
