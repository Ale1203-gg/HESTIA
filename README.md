# HESTIA
## **HestiaCP: ¿Qué es, para qué se usa y cómo iniciarse?**  

###  ¿Qué es HestiaCP?  
Hestia Control Panel (**HestiaCP**) es un **panel de control de hosting gratuito y de código abierto** que permite administrar servidores web de manera sencilla y eficiente. Se basa en **VestaCP**, pero con mejoras en seguridad, estabilidad y compatibilidad con versiones modernas de software.  

###  ¿Para qué se usa?  
HestiaCP se utiliza para:  
1)  **Administrar sitios web** y dominios.  
2) **Configurar servidores web** con Apache y Nginx.  
3) **Gestionar bases de datos** (MySQL y PostgreSQL).  
4) **Manejar cuentas de correo electrónico**.  
5) **Implementar certificados SSL** de Let’s Encrypt.  
6)  **Configurar FTP, cron jobs y DNS**.  

###  ¿Cómo se usa?  
1️) **Instalación en un servidor** (usualmente en Debian o Ubuntu).  
2️) **Acceder al panel de administración** mediante un navegador.  
3️) **Crear un usuario y dominio** dentro del panel.  
4️) **Configurar los servicios** (web, correo, bases de datos).  
5️) **Administrar recursos** y seguridad del servidor.  

### Primeros pasos para iniciar en HestiaCP  
🔹 Instalar HestiaCP   
Ejecuta los siguientes comandos en tu servidor:  
```bash
wget https://raw.githubusercontent.com/hestiacp/hestiacp/release/install/hst-install.sh  
bash hst-install.sh
```  
🔹  Acceder al Panel de Control  
Después de la instalación, accede a HestiaCP desde tu navegador con la IP del servidor:  
```
https://tu-ip-servidor:8083
```
Inicia sesión con el usuario y contraseña generados.  

🔹 Agregar un dominio y sitio web
- Dentro del panel, selecciona **Web** > **Agregar dominio**.  
- Configura el dominio y elige las opciones necesarias (como SSL).  

🔹  Configurar correos y bases de datos
- Ve a **Correo** para crear cuentas de email.  
- En **Base de Datos**, crea y administra bases de datos MySQL o PostgreSQL.  

🔹 Gestionar Seguridad y Backups  
- Configura **firewall, antivirus y backups** para mantener el servidor seguro.  

###  Cosas importantes a considerar 
*  Compatible con Apache.  
*  **Interfaz simple y ligera**, ideal para servidores pequeños y medianos.  
*  **Seguridad integrada**, con soporte para certificados SSL y firewall.  
*  **Totalmente gratuito**, con una comunidad activa y documentación accesible.  
