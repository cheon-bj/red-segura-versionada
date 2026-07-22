\# Reglas básicas de firewall



\## Reglas permitidas



| Origen | Destino | Puerto | Acción | Justificación |

|---|---|---|---|---|

| LAN escolar | Internet | 80 | Permitir | Navegación web |

| LAN escolar | Internet | 443 | Permitir | Navegación segura |

| IP administrativa | Servidor académico | 22 | Permitir | Administración remota autorizada |



\## Reglas denegadas



| Origen | Destino | Puerto | Acción | Justificación |

|---|---|---|---|---|

| Cualquier origen | Servidor académico | 22 | Denegar | Evitar intentos de fuerza bruta |

| Cualquier origen | Cámara IP | 80 | Denegar | Evitar exposición de interfaz web |

| Red invitados | Red administrativa | Todos | Denegar | Separación de segmentos |



\## Recomendación



No se deben exponer servicios administrativos a cualquier origen. El acceso a servicios críticos debe limitarse únicamente a las redes o direcciones IP autorizadas.





