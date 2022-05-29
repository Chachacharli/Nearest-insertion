# Nearest-insertion
Algoritmo que resuelve TSP con Nearest insertion (Algoritmo de inserción mas cercana). 5,48 y 101 nodos.

# Descripción del algoritmo. 
 <p>Consiste en comenzar construyendo ciclos que visiten únicamente un subtour, formado por 2
        nodos (Uno inicial y el nodo más cercano al inicial), para posteriormente extenderlos insertando 
        los vértices restantes.</p>
    <ol>

        <li value="1">Encuentra un nodo k que no esté en el subtour, que este lo mas cercano posible a 
            cualquier nodo del subtour. </li>
        
        <li>Encuentra un arco (i,j) del subtour para el cual la inserción de k da el menor incremento 
            de longitud (∆f)</li>
        
        <li> Este será el 22. Y así sucesivamente. </li>
        <li>Modifique el subtour mediante la inserción de k entre i y j.
        </li>
        
        <li> Vaya al paso 3 hasta que se haya formado un tour TSP (Un tour TSP es cuando se 
            completa el viaje y el viajero vuelve al nodo de inicio).</li>
        
    </ol>
