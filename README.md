# Gojira-Mine Server Infrastructure 🦖

![Minecraft Version](https://img.shields.io/badge/Minecraft-1.20.1-green)
![Forge Version](https://img.shields.io/badge/Forge-47.4.10-orange)
![Status](https://img.shields.io/badge/Status-In_Production-blue)

## Descripción del Proyecto
**Gojira-Mine** es un entorno de servidor de Minecraft altamente modificado y optimizado, diseñado para ofrecer una experiencia de supervivencia estable y técnica. Este repositorio contiene la arquitectura de configuración, la gestión de dependencias (mods) y los perfiles de optimización del lado del servidor.

Este proyecto demuestra habilidades en **Administración de Sistemas (SysAdmin)**, gestión de entornos en la nube y control de versiones aplicado a servicios en tiempo real.

## Stack Tecnológico
* **Motor:** Minecraft Forge 1.20.1
* **Lenguaje:** Java 17
* **Infraestructura:** Desplegado actualmente en SwiftServers (con planes de migración a Oracle Cloud Infrastructure).
* **Control de Versiones:** Git / GitHub para la gestión de configuraciones críticas.

## Características Técnicas
* **Gestión de Dependencias:** Resolución de conflictos entre más de [NÚMERO_DE_MODS] mods, incluyendo optimizadores de renderizado y lógica de servidor.
* **Optimización de Recursos:** Configuración avanzada de la JVM para la gestión eficiente de memoria RAM y ciclos de CPU.
* **Seguridad y Mantenimiento:** Implementación de protocolos de protección de spawn, gestión de rangos (OP/Admin) y backups automatizados.
* **Troubleshooting:** Diagnóstico y resolución de errores de red (Gateway 504) y debugging de crash-reports.

## Estructura del Repositorio
* `/config`: Archivos de configuración de comportamiento de mods (.toml, .json).
* `/mods`: (Lista de referencia) Mods seleccionados para estabilidad y rendimiento.
* `.gitignore`: Configurado profesionalmente para excluir datos de usuario y mundos pesados, manteniendo el repo ligero y seguro.

## Desafíos Superados
1. **Conflicto de Shaders:** Resolución de incompatibilidades entre librerías de renderizado (Oculus/Rubidium) en el lado del servidor.
2. **Estabilidad de Red:** Gestión de tiempos de espera en el panel de control durante fallos de infraestructura externa.

---
**Contacto:** Brayan-Bazaldua
