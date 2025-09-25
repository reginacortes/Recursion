# Recursion

## Problema 

Un centro de distribucion de Correos de México requiere planificar la recolección de paquetes
que hará un agente postal en diferentes oficinas de correos en diferentes dıas de la semana. Para
esto, cuenta con un mapa de recolección por dıa de la semana y peso de los paquetes a recolectar
en cada oficina. En esta práctica desarrollarás un programa que te indicará las rutas que deberá
tomar el agente para hacer un recorrido optimo y cuanto peso recogera en total para decidir qué
vehıculo utilizar.

  Entrada un archivo de texto con los mapas de las rutas a seguir en cada dia de la semana

Cada lınea representara un mapa en formato de arbol que se explicara en clase en el que las
hojas contaran con el peso a recolectar en cada oficina. El nodo raiz del arbol es el centro
de distribucion y las hojas son oficinas de correos en las que se indicara el peso a recolectar
mediante un numero natural de uno o dos dıgitos.

  El numero de oficinas a visitar esta en el rango de 1 a 255

Salida: Una lınea de texto por cada dıa de las semana que diga: Ruta seguida, numero de calles visitadas y peso total

Implemente dos versiones de este programa: Una version en la que utilice un algoritmo iterativo auxiliandose por una pila.
Una version recursiva. 


## Ejecución

Se utilizará un método recursivo que visite todos los nodos y acumule:
- la ruta
- el número de calles
- el peso total

Por otro lado, se hará uso de un método iterativo con una pila:




