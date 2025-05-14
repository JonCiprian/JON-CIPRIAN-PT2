# Creació de la màquina d'IsardVDI

Escritorio nuevo arriba a la derecha. 

![Captura de pantalla de 2025-05-14 13-05-37](https://github.com/user-attachments/assets/961d7866-8673-4fbf-8755-ddebaef095e6)

Y seleccionamos esta máquina.

![Captura de pantalla de 2025-05-14 13-05-40](https://github.com/user-attachments/assets/a5a50e1d-4854-4fd6-a693-c57415d2f98c)

![Captura de pantalla de 2025-05-14 13-05-46](https://github.com/user-attachments/assets/5b67e29a-18f4-4cc2-a6f9-83b222dfedc6)

# Instalación de aplicaciones web

## Instal·lació d'apache2, mysql

Antes de instalar el apache2 y el mysql, actualiza la máquina con estos dos comandos.

![Captura de pantalla de 2025-05-14 13-01-46](https://github.com/user-attachments/assets/873aa02f-9997-4f32-a541-a9e9688a46cb)

![Captura de pantalla de 2025-05-14 13-02-16](https://github.com/user-attachments/assets/63033a5c-6723-490a-8c6d-c4e060f5d28d)

Una vez actualizada, instalamos el Apache2 y MySQL, primero Apache2 con estos comandos:

![Captura de pantalla de 2025-05-14 13-02-33](https://github.com/user-attachments/assets/af8af7c3-c59e-4cad-af5f-6f0f8c6356c1)

![Captura de pantalla de 2025-05-14 13-02-43](https://github.com/user-attachments/assets/10def5d1-e462-4f24-83fb-0571a26efc29)

![Captura de pantalla de 2025-05-14 13-02-51](https://github.com/user-attachments/assets/5962ee36-3ea6-4f67-9aea-2298299963ee)

![Captura de pantalla de 2025-05-14 13-02-58](https://github.com/user-attachments/assets/a93d5107-47fa-4426-ba12-297f46662f36)

Y al acabar reiniciamos y pasamos a instalar MySQL.

![Captura de pantalla de 2025-05-14 13-03-05](https://github.com/user-attachments/assets/8a155904-5f70-4805-8b9e-f16adcc45430)

![Captura de pantalla de 2025-05-14 13-03-12](https://github.com/user-attachments/assets/ea93125f-c774-4978-ab8e-4ed3c92203e0)

![Captura de pantalla de 2025-05-14 13-03-19](https://github.com/user-attachments/assets/7d1aa529-6aba-43f0-a026-7fb2983d7f1d)

![Captura de pantalla de 2025-05-14 13-03-44](https://github.com/user-attachments/assets/f0c9e042-91c6-4348-8ad3-082be73b0cb3)

![Captura de pantalla de 2025-05-14 13-03-50](https://github.com/user-attachments/assets/2384a977-abee-454b-a367-96dadb7f2436)

![Captura de pantalla de 2025-05-14 13-04-04](https://github.com/user-attachments/assets/0b6a926e-1736-483c-98d7-dad551dec033)

![Captura de pantalla de 2025-05-14 13-04-13](https://github.com/user-attachments/assets/0733ba59-667a-4ed0-a707-d972a1bebd72)

## Descarreguem els fitxers de l'aplicació web.

Una vez instaladas las dos cosas, pasamos con la instalación de los archivos de la aplicación web. Antes de comenzar con los comandos, nos debemos instalar el archivo de la aplicación que queremos.

Y una vez lo tengamos, hacemos el siguiente comando, cambiando el archivo de la captura por el nuestro.

![Captura de pantalla de 2025-05-14 13-04-18](https://github.com/user-attachments/assets/d9c8ec2e-b32b-4144-8c83-5b19ae38f63f)

Luego entramos al directorio `/var/www/html`

![Captura de pantalla de 2025-05-14 13-04-24](https://github.com/user-attachments/assets/685be104-35d4-4567-8592-855f1422558b)

Y descomprimimos nuestro archivo con ```console sudo unzip app-web.zip``` cambiando 'app-web.zip' por el nombre de nuestro archivo.

![Captura de pantalla de 2025-05-14 13-04-30](https://github.com/user-attachments/assets/2ea62aa7-7e6c-4132-96e1-9be499ccf91d)

Luego aplicamos los siguientes comandos, cambiando 'owncloud' por el nombre de nuestra carpeta siempre.

![Captura de pantalla de 2025-05-14 13-04-40](https://github.com/user-attachments/assets/05a6adea-1d89-41c5-b48a-6ba7caab801d)

![Captura de pantalla de 2025-05-14 13-04-45](https://github.com/user-attachments/assets/ff1a8c4f-8db2-41b1-b5d9-e3c662d78424)

![Captura de pantalla de 2025-05-14 13-04-53](https://github.com/user-attachments/assets/84da56ad-8228-4e58-ad28-e54368d8f055)

Y aquí se puede comprobar cómo funciona, y entramos a localhost y nos entra a OwnCloud e iniciamos sesión con la información de la captura y de contraseña "password".

![Captura de pantalla de 2025-05-14 13-05-54](https://github.com/user-attachments/assets/40a41655-eca1-4585-b59e-2c263d99e67d)
![Captura de pantalla de 2025-05-14 13-05-23](https://github.com/user-attachments/assets/b95ba767-0a90-4cee-8ca4-3efde7c5f3d6)
![Captura de pantalla de 2025-05-14 13-05-29](https://github.com/user-attachments/assets/3a967454-884e-4dba-a6ef-1264d942593e)

