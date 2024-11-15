# firewall-opnsense
Configuración de un firewall utilizando OPNsense en un entorno virtualizado
# Firewall con OPNsense

Este proyecto implementa un firewall funcional utilizando **OPNsense** para proteger una red local en un entorno virtualizado. 

## **Objetivos del proyecto**
- Implementar reglas de acceso para proteger redes internas.
- Configurar NAT para permitir la salida de tráfico a internet.
- Analizar y monitorear tráfico de red utilizando herramientas integradas.

## **Tecnologías utilizadas**
- **OPNsense:** Sistema operativo para firewall de código abierto.
- **Proxmox:** Plataforma de virtualización utilizada para el entorno de pruebas.
- **Herramientas adicionales:** Wireshark, Nmap.

## **Configuración del Proyecto**
### 1. Entorno inicial
- Máquina virtual con OPNsense instalada en Proxmox.
- Red virtual configurada con subredes internas y externas.

### 2. Reglas implementadas
- **Regla 1:** Bloqueo de tráfico entrante desde redes no autorizadas.
- **Regla 2:** Permitir navegación HTTP/HTTPS a usuarios internos.

### 3. NAT
- Configuración de NAT para redirigir tráfico de redes internas hacia internet.

## **Pasos para reproducir**
1. Descarga OPNsense desde su página oficial: [opnsense.org](https://opnsense.org).
2. Instala y configura una máquina virtual en Proxmox.
3. Sigue la guía de instalación y configura las reglas según la documentación incluida.

## **Capturas de pantalla**
*(Aquí puedes añadir capturas del panel de OPNsense, diagramas de red, o configuraciones relevantes).*

## **Autor**
*Nicolas Diaz C.*  
*www.linkedin.com/in/nicolas-fabian-94aa1a270*  
