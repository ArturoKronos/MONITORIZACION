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
