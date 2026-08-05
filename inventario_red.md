\# Inventario de red escolar



| ID | Dispositivo | IP | Tipo | Ubicación | Servicio principal | Estado |

|---|---|---|---|---|---|---|

| 1 | Router principal | 192.168.10.1 | Router | Site principal | Gateway | Activo |

| 2 | Switch core | 192.168.10.2 | Switch | Site principal | Conmutación LAN | Activo |

| 3 | Servidor académico | 192.168.10.10 | Servidor | Centro de datos | Web / SSH | Activo |

| 4 | Equipo administrativo | 192.168.10.20 | PC | Dirección | Sistema escolar | Activo |

| 5 | Cámara IP | 192.168.10.30 | IoT | Pasillo | HTTP | Activo |



\## Observaciones



\- El servidor académico tiene SSH habilitado.

\- La cámara IP utiliza acceso HTTP.

\- El equipo administrativo pertenece a una zona crítica.



\##Propuesta de segmentación



\- VLAN 10: Equipos administrativos.

\- VLAN 20: Equipos académicos.

\- VLAN 30: Cámaras y dispositivos IoT.

\- VLAN 40: Red de invitados.

\- Bloquear la comunicación directa entre la red de invitados y la red administrativa.

