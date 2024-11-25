# Commpilar Kernel
1.  Ejecutamos el comando _apt install build-essential libncurses-dev bison flex libssl-dev libelf-dev bc_
![image](https://github.com/user-attachments/assets/570f5cd3-e2a5-4c70-8a1a-0e4b2015f932)

2. Descargamos la última versión del kernel.
![image](https://github.com/user-attachments/assets/c2ece3f8-19af-4dc8-aeff-6dd0bd2dc10c)

3. Lo extraemos
![image](https://github.com/user-attachments/assets/9a5e9f94-3fba-4a43-a8ad-ebb01efb7e5c)

4. Lo configuramos
![image](https://github.com/user-attachments/assets/e7dde08c-7197-477a-b3c8-329c825cf22a)
![image](https://github.com/user-attachments/assets/0ccaca98-a0c9-46f0-bf15-8a76662ec81e)

![image](https://github.com/user-attachments/assets/fac3e03a-2187-4282-822a-e32bae5d14c8)

![image](https://github.com/user-attachments/assets/971dc244-7e8a-40a4-9eb0-57118bbb7fbd)

5. Compilamos el kernel
![image](https://github.com/user-attachments/assets/fc56fc5d-7724-4c70-95fd-a61148fd250c)

6. Obtuve el siguiente error durante la compilación
![image](https://github.com/user-attachments/assets/0936e3f4-65b3-4a63-83f2-b39c1560cb75)

7.Instalando pahole 

![image](https://github.com/user-attachments/assets/22c79739-cc97-4b8a-bc9c-05d554851e17)

8. Re intentamos compilar el kernel
![image](https://github.com/user-attachments/assets/4514069e-3e64-485d-9b53-f88b849423e4)

9. Después de esperar, ha terminado de compilar
![image](https://github.com/user-attachments/assets/2e11f55c-5a71-423f-bfd1-d1538c8d8ba3)

10. Ahora, instalamos los módulos
![image](https://github.com/user-attachments/assets/c0e64e0e-1580-46e0-890a-1483f609a108)
![image](https://github.com/user-attachments/assets/44036364-ed2d-4838-9fda-d75436b1935c)

11. Entonces instalamos el kernel
![image](https://github.com/user-attachments/assets/72bb180f-de5f-4042-83b0-984198e5add5)
![image](https://github.com/user-attachments/assets/6ecd7930-0d01-40c3-96ae-52eac80412b0)

12. Actualizamos el grub
![image](https://github.com/user-attachments/assets/27b99de7-63ba-4e64-98cd-c398ba02122e)

13. Tras reiniciar la máquina, verificanos la versión del kernel
![image](https://github.com/user-attachments/assets/0d3b48ba-8454-48bb-b4cb-4bfcd687822e)
