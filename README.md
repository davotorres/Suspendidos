# Suspendidos
Simulación de sistema con paginación y suspendidos

Cumpliendo con los requisitos de las practicas anteriores esta actividad deberá agregar la opción de enviar un proceso a suspendidos, lo que quiere decir que el alumno deberá agregar funciones en las cuales, si el usuario Al presionar la tecla “S” el primero en la cola de bloqueados saldrá de memoria principal e ira a estado suspendido, es decir a disco. Debe generar un archivo con los datos de los procesos suspendidos. Si no hay procesos bloqueados no aplica.
De igual manera Si el usuario presiona la tecla “R” el primero en la cola de suspendidos regresara a memoria principal siempre y cuando haya espacio. Si no hay procesos suspendidos no aplica.
Todo el tiempo se deberá desplegar el numero de proceso que esta en estado de “Suspendido”, Del proceso que esta por regresar a memoria, su Id y su tamaño.
El programa finalizara cuando no haya ningún proceso en el sistema.

Al igual que en todos los programas realizados en este curso, se utilizo el lenguaje de JavaScript para realizar la lógica del programa y HTML con CSS para realizar la parte visual del sistema.
Lo principal que hay que destacar en esta actividad es que se agregaron las siguientes tablas: 
![image](https://user-images.githubusercontent.com/71399810/168396092-68f1f9c1-19ea-4b9a-bf94-7fa61f1757fa.png)

En las cuales se desplegará ya sea la cantidad de procesos nuevos que están en espera, cual es el proceso siguiente que será llevado a procesos listos y el tamaño de cada proceso, al igual con procesos suspendidos y también se mostrara en todo momento el tamaño de la memoria.
Al igual se agregaron dos funciones más para la tecla” S” y la tecla “R”, si el usuario presiona la tecla S un proceso ira a procesos suspendidos siempre y tanto dicho proceso provenga de procesos bloqueados, de caso contrario no será posible dicha acción.

![image](https://user-images.githubusercontent.com/71399810/168396109-2acceddc-df80-4af6-bac2-9e910c40e9ef.png)

Cuando el usuario presione la tecla “R”  este se encargará de sacar procesos suspendidos y llevarlos a procesos listos para ser atendidos, esto será posible siempre y tanto haya espacio en la memoria para dicho proceso de caso contrario será necesario esperar que se libere espacio.

![image](https://user-images.githubusercontent.com/71399810/168396136-60d6d6a5-af5f-4b1c-a682-6c2973d11f42.png)
