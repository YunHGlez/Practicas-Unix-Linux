# Asegurar Bootloader

1. Iniciamos la mv.
![image](https://github.com/user-attachments/assets/d81aa3a7-d0a0-4240-806b-76fa3483426f)

2. presionamos en el teclado la letra 'e'
![image](https://github.com/user-attachments/assets/4cdda286-efd0-4386-93a3-eedc9d319dee)

3. agregamos _init=/bin/sh_ en la línea que dice 'linux'.
![image](https://github.com/user-attachments/assets/435f6154-4eca-48d9-9978-045737463a29)
y presionamos f10
![image](https://github.com/user-attachments/assets/526f0b45-a781-43f2-b5a8-284321171b7c)

4. Escribimos el comando mount -o remount,rw / para volver a montar el sistema de archivos raíz / con permisos de lectura y escritura.
![image](https://github.com/user-attachments/assets/676498c8-2ce8-4f77-9bd1-0073163a95bf)

5. cambiamos la contraseña de root con el comando _passwd_
![image](https://github.com/user-attachments/assets/209383a9-dbc9-4dfd-948c-0af58cb089c2)

6. reiniciamos la máquina, y modificamos las opciones avanzadas, sudo nano /etc/grub.d/10_linux
dentro de /etc/grub.d/10_linux, agregamos _--unrestricted_ 
![image](https://github.com/user-attachments/assets/d5760b9a-e4a6-42cf-9a20-1b6a51089b5e)

7. actualizamos el grub
![image](https://github.com/user-attachments/assets/450ecf0b-19f7-4933-80e8-e13ce0cf0a51)

# Protección con Contraseña de GRUB

1. generamos la contraseña
![image](https://github.com/user-attachments/assets/ecae32cf-37e2-49c3-bc1b-fa2bfc1ddcac)

2. en este punto entendí porque fue necesario acceder desde ssh, así que me conecté desde un debian con interfaz gráfica para facilitar copiar y pegar.
![image](https://github.com/user-attachments/assets/215ceb7b-2c46-4e03-9966-b1fc04976ad7)

![image](https://github.com/user-attachments/assets/e52ca2d0-dab3-419b-be03-766660b362fa)
3. Ingresamos de manera normal al sistema 

![image](https://github.com/user-attachments/assets/370fdc7a-46ec-42e3-8a67-dc240391404b)

4. Y efectiavemente, funcionó la protección
![image](https://github.com/user-attachments/assets/fdf0427a-9d15-4888-af5b-347e2bccfcd6)
solamente pude ingresar tras usar la contraseña que configuré

![image](https://github.com/user-attachments/assets/c6f92019-ece8-44bc-a9e8-f99e98a404b5)

