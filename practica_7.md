# Práctica 7

## Fail2ban
1. Actualizamos aptitude
![image](https://github.com/user-attachments/assets/eef24834-4af2-4474-a471-924557c64eb8)

2. Instalamos fail2ban
![image](https://github.com/user-attachments/assets/5bfae102-5c34-4b57-be0e-78ff01cc62ce)

3. Modificamos el archivo jail.local
![image](https://github.com/user-attachments/assets/77fd97b9-51b3-432d-9b51-c73eacac21a2)

4. Verificamos que fail2ban funciona
![image](https://github.com/user-attachments/assets/c9b1d440-38df-4c7c-bc16-3f382a354362)

5. Consultamos los filtros.
![image](https://github.com/user-attachments/assets/766f8d5b-acac-465e-ad60-6c561dc91d57)

6. Revisamos el status del cliente
![image](https://github.com/user-attachments/assets/dd61f05c-56eb-42b1-ae6b-c1e53838a5e2)


## ClamaV

1. Instalamos clamav
![image](https://github.com/user-attachments/assets/8518ee8b-abbe-4b69-a0fd-76c9066b192b)

2. Lo podemos configurar automaticamente o manualmente
![image](https://github.com/user-attachments/assets/b56d9d55-018c-4060-a849-f480294203d4)

3. Activamos clamav-freshclam.service
![image](https://github.com/user-attachments/assets/65f15dec-898d-4c92-a05c-75b9b1db9f88)

4. Generamos un script de tareas diarias
![image](https://github.com/user-attachments/assets/cf572cce-cf88-4e6c-915d-5ad68f501f8d)

5. Lo configuramos para que se ejecute diario
![image](https://github.com/user-attachments/assets/e282843d-7c38-4e42-99e1-aa0da6b3e91e)

## Postfix y Logwatch

1. Instalamos Postfix y Logwatch
![image](https://github.com/user-attachments/assets/da6973a0-0d02-4343-9010-e7306c2aaff6)

2. Modificamos el archivo /etc/aliases
![image](https://github.com/user-attachments/assets/0476972c-e3b9-4c8c-b112-1f7ad7dac0d8)

3. Ajustamos las configuraciones en el archivo logwatch.conf, ahora se permite enviar informes mediante el mail
![image](https://github.com/user-attachments/assets/ded6f675-992c-45c4-80d6-b2746ebc5d4f)

4. Mostramos el contenido del correo del root
![image](https://github.com/user-attachments/assets/9ad1038a-a743-48f2-89e0-2d3cf8c169ad)

5. Generamos un reporte diario de sshd
![image](https://github.com/user-attachments/assets/12d12993-7555-4585-9acf-679a8581bd8e)
 
