# Ubuntu 24 LTS
Implementación de un servidor Linux Ubuntu 24.04 LTS destnado a integrarse posteriormente en una infrestructura Windows basada en Active Directory.
Esta máquina será utilizada para prácticas de administración Linux, Samba, Kerberos, Winbind y compartición de recursos.

## Objetivos
- Instalar un sistema Operativo linux, creando una Máquina virtual
- Preparación inicial de un Servidor Linux.
- Familiarizarse con la administración de sistemas Linux.


### Tecnologías utilzadas
- Orcacle VirtualBox
- Ubuntu 24.04 LTS
- VirtualBox Guest Additions

### Configuración del Hardware
- Memoria RAM      4 GB
- CPU              2 vCPU
- Disco Virtual    40 GB
- Tipo de Disco    VDI

## Procedimiento de Instalación
### Creación de la máquina virtual
Se creo una nueva maquina virtual utilizando Oracle VirtualBox.
Durante la configuración inicial se seleccionó la Imagen ISO de Ubuntu 24.04 LTS y se habilitó la instalación desatendida para automatizar parte del proceso de instalación.
[!Configuración de Hardware](images/confi_sistema.png)


### Configuración del usuario
VirtualBox permite automatizar la creación del usuario inicial del sistema operativo.
Durante esta fase de configuración, se elige el nomrbe del equipo y se habilitó el montaje del disco para la instalación de las Guest Additions.


### Configuración del almacenamiento
Se creó un nuevo disco tipo VDI (VirtualBox Disk Image)
La asignación dinámica permite el uso del almacenamiento físico del equipo anfitrión, utilizando únicamente el espacio realmente necesario.

### Resultado
Se obtuvo una estación de trabajo Ubuntu 24.04 LTS completamente funcional y preparada para iniciar la configuración para la correcta integración de futuros proyectos del laboratorio.







