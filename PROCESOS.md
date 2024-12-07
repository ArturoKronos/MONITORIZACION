# COMANDO PS 
## ps
El comando PS nos muestra imformacion sobre los procesos. 
```bash	
ps a
```
![psa](img/img1.png)
```bash	
ps au
```
![psa](img/img2.png)
```bash	
ps aux
```
![psa](img/img3.png)
 ```bash
 ps -C nano
 ```
![psa](img/img4.png)


Si quieres ver los 5 que mas ocupan memoria, puedes usar 

`ps -eo user,pid,%cpu,%mem,time --sort=-%cpu | head -n 6`
![psa](img/img5.png)

# COMANDO TOP
El comando top permite ver en tiempo real los procesos que están ejecutándose en el sistema. Proporciona información sobre el uso de los recursos del sistema, como la CPU, la memoria y el espacio de intercambio (swap).
## DISTINTAS OPCIONES QUE PODEMOS USAR DE ESTE COMNADO 

`P`: Ordenar los procesos por uso de CPU.

`M`: Ordenar los procesos por uso de memoria.

`T`: Ordenar los procesos por el tiempo de ejecución.

`k`: Matar un proceso. Se necesita el PID del proceso.

`r`: Cambiar la prioridad (renice) de un proceso.

`q`: Salir de top.

`h`: Mostrar la ayuda (teclas y opciones disponibles dentro de top).

`z`: Cambiar la coloración de la interfaz.

`c`: Alternar entre mostrar el comando completo o el nombre del proceso.
