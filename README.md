# 📡Ngrok-2022-WCH📡
🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷
### ¿Que es NGROK? Es una herramienta que utiliza una línea de comandos que le permite acceder a las aplicaciónes web que se ejecutan en su PC local o en su Dispositivo Android.
### Maneja una gran interfaz de usuario incorporada donde puede visualizar todo el tráfico de red que pasa desde su red local o privada.
### Ngrok ofrece un nivel súperior de flexibilidad en la administración y distribución del servidor web, como túneles seguros, subdominios personalizados, webhooks, etc.
### Ngrok genera una dirección web temporal fácil de usar que se puede ver desde cualquier parte del mundo. Su sitio también se puede proteger con una contraseña que permitirá que solo aquellos que conocen la contraseña accedan a su sitio.

🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷 🔷
 
# INSTALACIÓN DE NGROK EN TERMUX 2022
#### Para instalar Ngrok en Termux, recuerda que primero debes crear una cuenta NGROK en el Sitio Web Oficial.
#### Luego debes descargar el archivo ZIP igual del Sitio Web Oficial y luego ejecutarlo en Termux-Android.
#### En el mismo Sitio Web Oficial debe generar el AUTHTOKEN para poder hacer uso de NGROK sin error alguno 

🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐

### Link del Sitio Web Oficial Ngrok
#### https://dashboard.ngrok.com

🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐 🌐

# #1...
#### Hay ay que actualizar los paquetes y binarios a la última versión.
### Eso lo haras Ingresando el siguiente Comando;

### 💲  apt update && apt upgrade 

⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡

# #2...
#### Instale los paquetes requeridos para instalar el paquete Ngrok, También instala el Módulo WGET para descargar archivos del servidor.
### Ahora ingresa el siguiente comando;

### 💲  pkg install zip wget -y 

⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡

# #3...
#### Ahora vamos a instalar Modulos Ngrok--ya se puede descargar e instalar paquetes Ngrok en la terminal Termux.
### A continuación ingresar el Siguiente Comando;

#### 💲  wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-arm.zip

⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡

# #4...
#### Ahora toca Descomprimir los paquetes de Ngrok Arm
### Ahora debe ejecutar el siguiente comando;

### 💲 unzip ngrok-stable-linux-arm.zip

⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡

# #5...
#### Ahora deben dar los permisos necesarios de ejecución
### El Siguiente Comando dara los permisos que les dije

### 💲  chmod +x ngrok

⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡

# #6...
#### El próximo paso es obtener el Token de Autenticación para la cuenta Ngrok.
#### Se puede obtener fácilmente desde el Sitio Web, solamente hay que registrarse 
#### Luego iniciar sesión en el sitio para obtener sus credenciales.

⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡

# #7...
#### El marco Ngrok ahora se ha instalado correctamente en Termux.
#### Si desea exponer su servidor web alojado localmente a la red mundial,
### Ejecute el siguiente comando;

### 💲  ./ngrok authtoken <'Auth_token'>

⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡ ⚡

#### Nota : Reemplace AUTH_TOKEN con el token que obtuvo del portal ngrok ( vea el paso 6 ).

#### Eso es todo ahora el emulador Termux está configurado con el Servicio de Túnel Web Ngrok. Puede servir un servidor web basado en python/php con el terminal.

#### Nota : el módulo Ngrok tiene un comando de ayuda ( ./ngrok help ) que puede ejecutar para ver la documentación dentro de la terminal termux.
