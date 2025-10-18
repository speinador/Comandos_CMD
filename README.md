# 💻 Comandos CMD de Windows

Guía de comandos más útiles del **Símbolo del Sistema (CMD)** de Windows.  
(descripción y uso)

---

## 📚 Índice

- [🧩 Comandos Básicos de Navegación y Archivos](#-comandos-básicos-de-navegación-y-archivos)
- [⚙️ Comandos del Sistema](#️-comandos-del-sistema)
- [🌐 Comandos de Red](#-comandos-de-red)
- [🔒 Comandos de Usuarios y Seguridad](#-comandos-de-usuarios-y-seguridad)
- [🧰 Comandos de Diagnóstico y Mantenimiento](#-comandos-de-diagnóstico-y-mantenimiento)
- [💽 Comandos de Disco y Particiones](#-comandos-de-disco-y-particiones)
- [🧠 Comandos Avanzados / Administrativos](#-comandos-avanzados--administrativos)
- [📦 Comandos de Archivos y Compresión](#-comandos-de-archivos-y-compresión)

---

## 🧩 Comandos Básicos de Navegación y Archivos

| Comando | Descripción |
|----------|--------------|
| `dir` | Lista los archivos y carpetas del directorio actual. |
| `cd` | Cambia el directorio actual (por ejemplo: `cd C:\Windows`). |
| `cd..` | Sube un nivel en el árbol de directorios. |
| `md` / `mkdir` | Crea un nuevo directorio. |
| `rd` / `rmdir` | Elimina un directorio vacío. |
| `del` | Elimina uno o varios archivos. |
| `copy` | Copia archivos de un lugar a otro. |
| `xcopy` | Copia archivos y carpetas (más avanzado que `copy`). |
| `move` | Mueve archivos de una ubicación a otra. |
| `ren` / `rename` | Cambia el nombre de archivos o carpetas. |
| `type` | Muestra el contenido de un archivo de texto. |
| `attrib` | Muestra o cambia los atributos de un archivo. |

---

## ⚙️ Comandos del Sistema

| Comando | Descripción |
|----------|--------------|
| `systeminfo` | Muestra información detallada del sistema. |
| `hostname` | Muestra el nombre del equipo. |
| `ver` | Muestra la versión del sistema operativo. |
| `set` | Muestra o establece variables de entorno. |
| `echo` | Muestra mensajes o el valor de variables. |
| `time` | Muestra o cambia la hora del sistema. |
| `date` | Muestra o cambia la fecha del sistema. |
| `shutdown` | Apaga o reinicia el equipo (`shutdown /r /t 0` para reiniciar). |
| `tasklist` | Muestra los procesos en ejecución. |
| `taskkill` | Finaliza un proceso por nombre o PID (`taskkill /im notepad.exe /f`). |
| `cls` | Limpia la pantalla del CMD. |
| `exit` | Cierra la ventana del símbolo del sistema. |

---

## 🌐 Comandos de Red

| Comando | Descripción |
|----------|--------------|
| `ipconfig` | Muestra la configuración IP del equipo. |
| `ping` | Verifica la conectividad con otro host. |
| `tracert` | Rastrea la ruta hasta un destino. |
| `nslookup` | Realiza consultas DNS. |
| `netstat` | Muestra conexiones de red activas y puertos en uso. |
| `arp` | Muestra o modifica la tabla ARP. |
| `route` | Muestra o modifica la tabla de enrutamiento IP. |
| `netsh` | Configura interfaces, firewall, Wi-Fi, etc. |
| `net` | Administra usuarios, servicios y recursos compartidos (`net user`, `net share`). |
| `telnet` | Conecta a otros equipos mediante el protocolo Telnet (si está habilitado). |

---

## 🔒 Comandos de Usuarios y Seguridad

| Comando | Descripción |
|----------|--------------|
| `net user` | Muestra o administra cuentas de usuario. |
| `net localgroup` | Muestra o modifica grupos locales. |
| `whoami` | Muestra el usuario actual. |
| `runas` | Ejecuta un programa con credenciales diferentes. |
| `cipher` | Muestra o modifica el cifrado de archivos NTFS. |
| `icacls` | Muestra o cambia permisos de archivos y carpetas. |
| `gpupdate` | Actualiza las directivas de grupo. |
| `gpresult` | Muestra las directivas aplicadas al usuario o equipo. |

---

## 🧰 Comandos de Diagnóstico y Mantenimiento

| Comando | Descripción |
|----------|--------------|
| `chkdsk` | Verifica y repara errores en el disco. |
| `sfc /scannow` | Repara archivos del sistema. |
| `DISM /Online /Cleanup-Image /RestoreHealth` | Repara la imagen del sistema operativo. |
| `driverquery` | Lista los controladores instalados. |
| `wmic` | Consulta información del sistema (CPU, RAM, BIOS, etc.). |
| `powercfg` | Configura opciones de energía. |
| `eventvwr` | Abre el visor de eventos. |
| `perfmon` | Abre el monitor de rendimiento. |
| `msinfo32` | Muestra información del sistema (GUI). |

---

## 💽 Comandos de Disco y Particiones

| Comando | Descripción |
|----------|--------------|
| `diskpart` | Administra discos, particiones y volúmenes. |
| `label` | Cambia la etiqueta de un volumen. |
| `vol` | Muestra la etiqueta y número de serie de un volumen. |
| `format` | Formatea un disco o partición. |
| `wmic logicaldisk get name` | Lista las unidades de disco. |

---

## 🧠 Comandos Avanzados / Administrativos

| Comando | Descripción |
|----------|--------------|
| `sc` | Administra servicios del sistema. |
| `reg` | Modifica el registro de Windows. |
| `taskschd.msc` | Abre el programador de tareas. |
| `services.msc` | Abre el administrador de servicios. |
| `compmgmt.msc` | Abre la consola de administración de equipos. |
| `gpedit.msc` | Abre el editor de políticas de grupo (ediciones Pro/Enterprise). |
| `eventcreate` | Crea eventos personalizados en el visor de eventos. |

---

## 📦 Comandos de Archivos y Compresión

| Comando | Descripción |
|----------|--------------|
| `compact` | Muestra o cambia la compresión NTFS. |
| `expand` | Extrae archivos comprimidos del sistema (CAB). |
| `tar` | Comprime o extrae archivos `.tar` (Windows 10+). |
| `robocopy` | Copia archivos y carpetas de manera avanzada. |

---

## 🧾 Créditos

📘 **Autor:** Sebastián Peinador  
👨‍🏫 **Profesor de Seguridad Informática**  
🏥 **Jefe de Soporte y Sistemas - Hospital José M. Penna (CABA)**  
📍 **Argentina**

---

> 💡 *Este documento puede usarse libremente con fines educativos o de referencia técnica. Creado para estudiantes y profesionales de IT que deseen dominar el uso del CMD de Windows.*
