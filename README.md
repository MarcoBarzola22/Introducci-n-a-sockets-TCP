# Sistemas Distribuidos y Paralelos - Trabajos Prácticos

Repositorio con las resoluciones de los trabajos prácticos de la materia Sistemas Distribuidos y Paralelos de la Universidad Nacional de Villa Mercedes.

## Trabajo Práctico N° 1: Introducción a sockets TCP
Implementación de un modelo cliente-servidor básico en Python utilizando el módulo estándar `socket`[cite: 3].

**Características implementadas:**
* Creación de un servidor *Echo* TCP local (puerto 65432)[cite: 3].
* Gestión del ciclo de vida del socket (`bind`, `listen`, `accept`, `connect`, `close`)[cite: 3].
* Envío y recepción de flujos de bytes bidireccionales (`encode` y `decode`)[cite: 3].
* Medición del tiempo de ida y vuelta (RTT) para cada solicitud[cite: 3].
* Cierre ordenado de la conexión al recibir un comando específico ("SALIR")[cite: 3].

**Instrucciones de ejecución:**
1. Iniciar el servidor: `python tp1/servidor_echo.py`
2. En una terminal secundaria, iniciar el cliente: `python tp1/cliente_echo.py`