# Ejercicio CiberKillChain - Defensa

## Alumno
Alejandro Anselmi

## Enunciado
Desarrollar la defensa en función del ataque planteado en orden inverso. No es una respuesta a un incidente, hay que detectar el ataque independientemente de la etapa.

Para cada etapa elegir una sola defensa, la más importante, considerar recursos limitados.

## Resolución
* Actions on Objectives 
- Identificar y corregir cualquier manipulación de datos en la base de datos, restaurando la integridad de los registros.
- Realizar análisis para determinar la extensión del daño y cómo se llevó a cabo la manipulación

* Command & Control

- Desactivar las comunicaciones encubiertas con los dispositivos comprometidos para cortar la conexión del atacante.
- Identificar los dispositivos comprometidos y aislarlos de la red para prevenir futuras comunicaciones.

* Installation

- Eliminar cualquier malware presente en los dispositivos comprometidos.
- Reforzar las medidas de seguridad para prevenir la instalación no autorizada de software y firmware.

* Exploit

- Corregir las vulnerabilidades conocidas o desconocidas que el atacante pudo haber aprovechado para obtener acceso.
- Implementar medidas de seguridad adicionales para dificultar futuros intentos de explotación.

* Delivery

- Identificar y bloquear las fuentes de los ataques de phishing y de ingeniería social utilizados para la entrega del malware.
- Reforzar la educación en seguridad cibernética para reducir la probabilidad de que el personal sea engañado nuevamente.

* Weaponization
- Monitorear y bloquear el tráfico malicioso que intenta comunicarse con los servidores de comando y control del atacante.
- Implementar soluciones de seguridad para detectar y prevenir malware en tiempo real.

* Reconnaissance
- Implementar controles más estrictos de acceso y autenticación para proteger la información confidencial.
- Restringir el acceso a información de contacto sensible de los coordinadores.
