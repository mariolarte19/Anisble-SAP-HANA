# Anisble-SAP-HANA 💻

### 1. Información Básicos: 📌
Este playbook configura el sistema Operativo (OS) SUSE SLES for SAP Business Applications 15.0 de acuerdo con las notas SAP aplicables para que se pueda instalar cualquier software SAP. Además Instala SAP HANA EXPRESS EDITION en un Bare metal con (OS) SUSE SLES.
### 2. Pre-Requisitos 📋

#### A).Sistema operativo :
* SUSE SLES
#### B).CPU soportada:
* Intel 64/AMD64
* IBM POWER 8 (with PowerVM)
* IBM POWER 9 (with PowerVM)

#### C).Disco duro
Para instalar SAP HANA, necesita:
* Una máquina certificada por SAP BusinessOne
* Una máquina compatible que cumple con los requisitos de SAP HANA TDI (Tailored
Integración de centros de datos). Es decir, necesita las siguientes cantidades de espacio libre en disco
además del espacio necesario para el sistema operativo:
* 52 GB de espacio libre en disco para la partición /usr/sap
  Espacio para tres particiones para datos de SAP HANA: /hana/data (mismo tamaño que RAM),/hana/log (mismo tamaño que RAM hasta un         máximo de 512 GB) y /hana/ (del mismo tamaño que la RAM hasta un máximo de 1 TB).

#### D).RAM 
El sistema operativo SUSE Linux Enterprise Server requiere un mínimo de 1024 MB de RAM total o un mínimo de 512 MB de RAM por núcleo de CPU (elija el que sea mayor). Cualquier software SAP que instale requerirá RAM adicional. Para instalar SAP HANA, su máquina necesita un mínimo de 24 GB de RAM.





### 3.Descripción de Tareas Playbook 🚀

#### 3.1 Crea directorio
#### 3.2 Instalar grupo de paquetes sap-hana
#### 3.3 Instalar una lista de paquetes
#### 3.4 solución saptune aplicar HANA	
#### 3.5 saptune daemon start
#### 3.6 Gestor de descargas
#### 3.7 Descargar instalador de sap hana
#### 3.8 Descomprimir instalador
#### 3.9 Procesar la plantilla de archivo de configuración de HANA"	
#### 3.10 Instalar SAP HANA

##  Construido con 🛠️
IBM Cloud, Ansible.



## Wiki 📖
Para más información [Watson-Visual Recognition](https://www.ibm.com/co-es/cloud/watson-visual-recognition)


## Autores ✒️
Team IBM Cloud



