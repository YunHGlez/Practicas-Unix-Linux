# Instalación de Gparted.
1. Ingresamos al sitio de GParted.

![image](https://github.com/user-attachments/assets/f1d02ddc-d4f9-461a-82e3-f8f77b618e24)

2. Descargamos la última versión estable.
![image](https://github.com/user-attachments/assets/7ae24b04-d8ed-4168-98ae-a643b3d82cdf)
![image](https://github.com/user-attachments/assets/c11b7090-9a3b-4ef4-a1a8-b7792659bdf1)

3. Ejecutamos 'df-h' y 'lsblk' para mostrar el uso del espacio en los discos de los sistemas de archivos montados.
![image](https://github.com/user-attachments/assets/0cda48e8-7383-4e45-95d9-cb0e9dba81ac)

4. Apagamos la máquina virtual.
5. En la parte de CD/DVD seleccionamos la ISO de GParted.
![image](https://github.com/user-attachments/assets/2ead749d-b191-46e8-b007-0c25b5bc3800)

6. Iniciamos la máquina virtual, y cambiamos el orden de booteo para poner primero a CD-ROM Drive.
   ![image](https://github.com/user-attachments/assets/f2294ae0-cf9e-42cb-a2bb-c50e686aaf1e)
   ![image](https://github.com/user-attachments/assets/6b45d2c4-85dc-4a81-84d0-7d22066f41cd)


7. Seleccionamos la primera opción
![image](https://github.com/user-attachments/assets/d7bdcfa2-7103-49bd-9f24-e276975f5a30)

8. Seleccionamos 'Don't touch keymap'
![image](https://github.com/user-attachments/assets/f5e5bf99-3523-4d16-8940-10a6a6bdb47c)

9. Presionamos 'enter' a todas las opciones.

10. Visulizamos la información del disco.
![image](https://github.com/user-attachments/assets/f7df9f18-d91a-4b1b-9ee4-2a05bbe4ff71)

11. Redimensionamos _/dev/sda8_
![image](https://github.com/user-attachments/assets/b6d43351-6040-4b5b-8649-1e4a314b4d1e)

12. Redimensionamos _/dev/sda7, /dev/sda6, /dev/sda5_.
![image](https://github.com/user-attachments/assets/ee592ae9-350a-45a5-9a28-767bf89c63cc)
![image](https://github.com/user-attachments/assets/2e44b51b-7d09-4643-af36-1c70c8a640fd)
![image](https://github.com/user-attachments/assets/79fa734f-67f0-41bd-85f2-232a96b87255)
![image](https://github.com/user-attachments/assets/c510e554-dbf0-4d94-a4c7-86deebe904d3)
Quedando de la siguiente manera
![image](https://github.com/user-attachments/assets/ba4866a8-295a-4ad2-9a40-c6d5311b894c)
13. Rebooteando la máquina con miedo, nos podemos dar cuenta que lo cambios han sido efectivos.
![image](https://github.com/user-attachments/assets/ae13af06-6f27-4c7e-9a76-d1210fbf2d87)

# Configuración de discos con LVM (solo para VMs con LVM)
1. Con la máquina con LVM, hacemos la expansión del disco (10 gb extras)
![image](https://github.com/user-attachments/assets/42691e96-11cf-4a5e-ac61-d17e93f443d2)

2. Ejecutamos los comandos _df -j_ y _lsblk_
![image](https://github.com/user-attachments/assets/5996e646-0041-4f6c-8c17-3b8619f09a7d)

3. Instalamos _parted_ y _resize2fs_ 
![image](https://github.com/user-attachments/assets/6e444376-8758-4c01-9518-6278c5d0e0b1)
![image](https://github.com/user-attachments/assets/8503da3e-68ee-4da5-aabd-28597822350c)
4. Verificamos los dispositivos SCSI
![image](https://github.com/user-attachments/assets/080aab8c-ff7b-460f-aae6-ecb8aa221135)
![image](https://github.com/user-attachments/assets/4d114173-c3c2-4377-af3a-231d603acbcf)


6. Mostramos la tabla de discos
![image](https://github.com/user-attachments/assets/9921d590-02ee-45c6-8115-e76f9b9f6d15)

7. Ahora, reedimensionamos la partición 2
![image](https://github.com/user-attachments/assets/8af37bf7-d89a-47c9-94c3-5926aaf2d05a)

8. Ejecutamos el comando _lvextend_.
![image](https://github.com/user-attachments/assets/1eb250b9-0c3f-412b-8f45-fbf55044d82d)

9. por último, utilizamos _resize2fs_.
![image](https://github.com/user-attachments/assets/878cbad0-a968-400c-96b7-7695602027a9)

10. 
