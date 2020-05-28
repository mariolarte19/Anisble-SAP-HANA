# Anisble-SAP-HANA 💻

### 1. Información Básicos: 📌
Este playbook configura el sistema Operativo (OS) SUSE SLES for SAP Business Applications 15.0 de acuerdo con las notas SAP aplicables para que se pueda instalar cualquier software SAP. Además Instala SAP HANA EXPRESS 2.0 en un Bare metal con (OS) SUSE SLES.
### 2. Pre-Requisitos 📋
#### 2.1 Requisitos de software.
Compruebe si su sistema tiene el software requerido para instalar y ejecutar con éxito SAP HANA 2.0, edición express
#### A).Sistema operativo :
* SUSE Linux Enterprise Server para aplicaciones SAP, 12.1, 12.2, 12.3 (SPS 02 Rev 23 o superior)
* Java Runtime Environment (JRE) 8 o superior : si planea utilizar el Administrador de descargas de edición expresa de SAP HANA 2.0 para Windows o Linux, necesita el JRE de 64 bits. Si planea usar el Administrador de descargas independiente de la plataforma, puede usar las versiones de 32 o 64 bits. Puede descargar SAP JVM (64 bits) desde https://tools.hana.ondemand.com/#cloud .
#### 2.1 Requisitos de hardware.
Compruebe si su sistema tiene el hardware requerido para instalar y ejecutar con éxito SAP HANA 2.0, edición express.
##### A).CPU soportada:
* Intel 64/AMD64
* IBM POWER 8 (with PowerVM)
* IBM POWER 9 (with PowerVM)

##### B).Disco duro
Para instalar SAP HANA, necesita:
* Disco duro de 120 GB recomendado
##### C).RAM 
El sistema operativo SUSE Linux Enterprise Server requiere un mínimo de 1024 MB de RAM total o un mínimo de 512 MB de RAM por núcleo de CPU (elija el que sea mayor). Cualquier software SAP que instale requerirá RAM adicional. Para instalar SAP HANA, su máquina necesita un mínimo de 16 GB mínimo (se recomiendan 24 GB).
Nota: Si está instalando en un sistema con 16 GB de RAM, aumente la cantidad de espacio de intercambio a al menos 32 GB.
##### D).Nucleos
*	2 núcleos (se recomiendan 4)



### 3. Regístrese en SAP HANA edición express.

##### A).Complete el formulario de registro
Vaya a la página de [registro-Descargar](https://www.sap.com/cmp/td/sap-hana-express-edition.html) y haga clic en Registrarse para obtener su versión gratuita.
##### B).Elige un administrador de descargas.
Haga clic en el administrador de descargas que coincida con su sistema: Linux DM o Windows DM.
##### C).Elige un administrador de descargas.
Guarde el archivo del administrador de descargas en su computadora portátil y ábralo. Si su sistema muestra una advertencia de seguridad cuando abre el archivo, ignore la advertencia.
### 3.Descripción de Tareas Playbook 🚀

#### 3.1 Crea directorio
#### 3.2 Instalar grupo de paquetes sap-hana
util-linux, util-linux-systemdy uuidd
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



