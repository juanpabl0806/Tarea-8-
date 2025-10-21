# Tarea-8-
maquinas virtuales
Este documento explica el proceso paso a paso para la instalación y configuración de **máquinas virtuales usando QEMU** como gestor principal.  
Se realizaron pruebas con distintos sistemas operativos: **Kali Linux**, **Windows** y **Rocky Linux**.

## Paso a Paso de la instalacion 
-**Primer paso** 
Descargar e instalar **QEMU**, el gestor de máquinas virtuales.  
Este software permite crear y administrar entornos virtualizados para distintos sistemas operativos.
<img width="602" height="639" alt="image" src="https://github.com/user-attachments/assets/bb210d2b-8636-4e05-b66e-0dcc0714db27" />

-**Segundo Paso**
Descargar las **imágenes ISO** de los sistemas operativos que se van a virtualizar (por ejemplo, Kali, Windows o Rocky Linux).

<img width="549" height="292" alt="image" src="https://github.com/user-attachments/assets/5406c886-97b1-4ef7-8f16-c56b29f35e57" />

-**Tercer Paso** 
Configurar una nueva máquina virtual en QEMU, asignando:
- **Memoria RAM**
- **Espacio en disco**
- **Núcleos de CPU**
- **Archivo ISO** para instalación

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/c9ef1afe-727f-4e09-b015-b7761affa857" />

<img width="789" height="500" alt="image" src="https://github.com/user-attachments/assets/78f3cb40-9816-4133-861e-2993313ec6e4" />

Una vez definidos los recursos, se inicia el proceso de instalación del sistema operativo seleccionado.

## Instalaciones completadas 

A continuación se muestran las máquinas virtuales correctamente configuradas y operativas:

Imagen de kali

<img width="1600" height="904" alt="image" src="https://github.com/user-attachments/assets/970a382f-1d42-4263-98c8-f99985b5a4b4" />

Imagen de windows

<img width="1024" height="825" alt="image" src="https://github.com/user-attachments/assets/eea6ac15-3ee8-499e-8dc9-333f7c1b1221" />

Imagen de Rocky linux

<img width="1087" height="758" alt="image" src="https://github.com/user-attachments/assets/79bd06da-64ed-48a9-abd6-b4bd66549866" />

## Conclusiones

- QEMU permite virtualizar distintos sistemas operativos de manera ligera y eficiente.  
- Es una alternativa libre a otros gestores como VirtualBox o VMware.  
- La correcta asignación de recursos garantiza el rendimiento de cada máquina.  
- Se logró la instalación satisfactoria de entornos Linux y Windows en un mismo host.

---

## Referencias

- [Documentación oficial de QEMU](https://www.qemu.org/documentation/)
- [Rocky Linux ISO Downloads](https://rockylinux.org/download/)
- [Kali Linux Downloads](https://www.kali.org/get-kali/)
- [Microsoft Evaluation Center](https://www.microsoft.com/en-us/evalcenter/)
