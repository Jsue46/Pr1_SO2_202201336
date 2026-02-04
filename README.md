# Práctica 1 – Instalación del Virtualizador y Sistema Operativo GNU/Linux

## Curso
**Sistemas Operativos 2 – Sección A**  
Facultad de Ingeniería  
Universidad de San Carlos de Guatemala  

## Estudiante
- **Nombre:** Estuardo Josué Vaquiax Reyes  
- **Carnet:** 202201336  
## Auxiliar
- **Nombre:** Alan Rodrigo Pamal De León

---

## Descripción

Esta práctica tiene como objetivo la instalación y configuración de un entorno de virtualización utilizando un hipervisor de virtualización completa. Para ello, se emplea VMware Workstation como virtualizador y Linux Mint como sistema operativo invitado, el cual está basado en Debian.

El desarrollo de la práctica permite al estudiante adquirir experiencia en la creación de máquinas virtuales, asignación de recursos de hardware, instalación de sistemas operativos GNU/Linux, configuración de usuarios y verificación básica del correcto funcionamiento del sistema.

---

## Objetivo General

Instalar y configurar un entorno de virtualización que permita ejecutar un sistema operativo GNU/Linux basado en Debian dentro de una máquina virtual, utilizando VMware Workstation.

---

## Objetivos Específicos

- Instalar el virtualizador VMware Workstation en el sistema operativo anfitrión.
- Crear una máquina virtual asignando los recursos mínimos de hardware requeridos.
- Instalar el sistema operativo Linux Mint a partir de su imagen ISO oficial.
- Configurar usuarios dentro del sistema operativo, incluyendo un usuario no administrador.
- Verificar el funcionamiento del sistema mediante el comando `uname -r`.
- Documentar de forma clara y ordenada todo el proceso realizado.

---

## Tecnologías Utilizadas

- **Sistema Operativo Host:** Windows  
- **Virtualizador:** VMware Workstation  
- **Sistema Operativo Invitado:** Linux Mint (basado en Debian)  
- **Documentación:** Manual técnico en formato PDF  

---

## Requisitos del Sistema

### Hardware
- Procesador con soporte de virtualización (Intel VT-x o AMD-V)
- Mínimo 4 GB de memoria RAM
- Al menos 30 GB de espacio libre en disco

### Software
- VMware Workstation
- Imagen ISO oficial de Linux Mint

---

## Configuración de la Máquina Virtual

- **CPU:** 2 núcleos  
- **Memoria RAM:** 4 GB  
- **Disco duro:** 40 GB  
- **Red:** NAT  

---

## Actividades Realizadas

- Instalación del virtualizador VMware Workstation.
- Creación de una máquina virtual con Linux Mint.
- Asignación de recursos de hardware (CPU, RAM y disco).
- Instalación del sistema operativo GNU/Linux.
- Creación de un usuario administrador y un usuario estándar.
- Verificación del kernel mediante el comando `uname -r`.
- Verificación de conectividad a internet.
- Elaboración del manual técnico con evidencias del proceso.

---

## Conclusiones

- Se instaló y configuró correctamente el virtualizador VMware Workstation, permitiendo la ejecución de sistemas operativos invitados.
- Se creó una máquina virtual con Linux Mint cumpliendo con los requerimientos mínimos de hardware establecidos en la práctica.
- Se configuraron usuarios con distintos niveles de permisos, fortaleciendo la administración básica del sistema.
- Se verificó el correcto funcionamiento del sistema operativo mediante comandos del sistema y pruebas de conectividad.
- La documentación elaborada permitió registrar de manera clara cada una de las fases del proceso realizado.

---

## Estructura del Repositorio

- [README.md](README.md)
- [Enunciado/Practica 1.pdf](Enunciado/Practica%201.pdf)
- [Manual/Manual Tecnico.pdf](Manual/Manual%20Tecnico.pdf)

---

## Referencias

- Documentación oficial de VMware Workstation: https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion
- Documentación oficial de VirtualBox: https://www.virtualbox.org/manual/
- Guía de instalación de Linux Mint: https://linuxmint-installation-guide.readthedocs.io
- Introducción a la virtualización (Red Hat): https://www.redhat.com/es/topics/virtualization