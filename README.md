# [Nombre del Proyecto: ej. Análisis de Tráfico de Red y Detección de Anomalías]

## 🎯 Objetivo
Este ejercicio tiene como objetivo analizar un incidente de seguridad ficticio que comprometió la red interna de la compañía durante dos horas. El equipo de seguridad respondió bloqueando el trafico de paquetes ICMP entrantes y se llevo a cabo una investigación para determinar la causa, solucionar el problema y tomar medidas para evitar futuros ataques similares.

🛠️ Herramientas y Entorno
Marco de ciberseguridad del Instituto Nacional de Estadares y Tecnología (NIST)
Ataque de denegación de servicio (DoS)

🔍 Metodología y Procedimiento
-Identificación: El equipo de seguridad identifico una vulnerabilidad en uno de los cortafuegos de la red.
-Protección: El equipo de seguridad configuro correctamente el cortafuegos en cuestión para detener el trafico de paquetes ICMP entrantes y se implemento un sistema IPS/IDS.
-Detección: Para detectar nuevos ataques, hemos implementado la verificación de la dirección IP de origen en el cortafuegos con el fin de identificar direcciones IP suplantadas en los paquetes ICMP entrantes.
-Respuesta: El equipo bloqueo todos los paquetes ICMP entrantes y se restauro el servicio de la red critica de la empresa.
-Recuperación: El equipo de seguridad informo que los sistemas y la red de la compañía regresaron a su funcionamiento normal y se han tomado las medidas necesarias para evitar futuros ataques de denegación de servicios (DoS).


🛡️ Mitigación y Recomendaciones
La correcta configuracion de los cortafuegos es fundamental para evitar ataques DoS así como el uso de sistemas de detección de intrusos que analicen el trafico de la red en busca de anomalías. Se recomienda mantener estas herramientas al día mediante un constante monitoreo así como realizar copias de respaldo frecuentemente que se puedan usar en caso de que la información o los datos sean comprometidos.


 
 📌 Conclusiones
 Este ejercicio nos enseña la importancia de las herramientas que un analista de seguridad debe manejar en su trabajo. El marco de ciberseguridad del instituto de estándares y tecnología (NIST) es una herramienta muy útil para mitigar ataques, amenazas y vulnerabilidades. El correcto uso de estas herramientas garantizan que los profesionales de la seguridad tengan éxito en sus tareas.
