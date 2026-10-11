# Tabla comparativa
| | **RFC 3227** | **NIST SP 800-86** | **ENFSI BPM** |
|---|---|---|---|
| **Qué entiende por identificar** | Es el primer paso del procedimiento de recogida: hay que hacer una  lista de los sistemas intervenidos en el incidente y de cuáles se recogerá evidencia. Decidir qué es lo más relevante y admisible,no dejar de preguntándose qué más puede ser evidencia mientras se trabaja. | Primera fase de la recogida. El analista debe saber recorrer un espacio físico y reconocer las fuentes de datos, y pensar también en las que están fuera. Debe considerar quién es el dueño de cada fuente y qué implica para obtenerla. | Una de las tres actividades en escena (identificar, incautar, procesar). Incluye la configuración de los dispositivos y de la red. No es un paso cerrado: procesar lo incautado puede llevar a nuevas incautaciones. |
| **Fuentes de evidencia que menciona** | Registros y caché, tabla de rutas, caché ARP, procesos, estadísticas del kernel, memoria, sistemas de archivos temporales, disco, logs remotos y de monitorización, configuración física y topología de red, medios de archivo. Añade a las personas presentes: quién estaba, qué hacía y qué observó. | Equipos, servidores, almacenamiento en red, medios externos y datos volátiles. También móviles, cámaras y grabadoras, logs de red y de aplicaciones de la organización, registros de terceros (por ejemplo, el ISP), equipos personales o de contratistas y el domicilio de un teletrabajador. Si una fuente no es accesible, busca fuentes alternativas con los mismos datos. | Dispositivos y configuraciones de red, memoria viva, cifrado activo, equipos conectados por radiofrecuencia, capturas de pantalla y datos lógicos recogidos a lo largo del tiempo. En lo físico, el lugar exacto del escenario donde se encontró cada objeto, documentado con fotos y croquis. |
| **Criterio para decidir qué se protege primero** | La volatilidad: de lo más volátil a lo menos. Recoger primero y analizar después. No apagar hasta terminar. | Tres factores combinados: valor probable de la fuente, volatilidad y esfuerzo necesario. Si hay demasiadas fuentes, no se adquieren todas. Si hay duda sobre si preservar, se preserva. |  Busca primero donde es más probable que esté la evidencia según lo que se alega. Protege lo que se perdería al incautar (memoria viva, cifrado, reinicio remoto), mantiene a sospechosos y testigos lejos de equipos y comunicaciones, y coordina con otras disciplinas según lo destructiva que sea cada una. |

## En qué coinciden

- Tratan la identificación como un paso en sí mismo, previo a tocar nada.
- Lo volátil es lo que se pierde primero.
- Ante la duda, se preserva.
- Todo debe documentarse con fecha, hora y responsable, porque lo recogido tiene que poder defenderse después.

## En qué se diferencian

- **Hasta dónde llega el equipo.** La RFC 3227 piensa en un administrador con una máquina comprometida. NIST amplía el mapa a terceros, a quién es dueño de cada dato y a las limitaciones legales. ENFSI parte de una escena física con personas y objetos. En los apartados leídos, ninguna menciona la nube como fuente.
- **Qué significa "primero".** La RFC usa un criterio técnico (volatilidad). NIST lo pondera con valor y coste. ENFSI se guía por la hipótesis del caso y por lo que se pierde al incautar. Una misma escena puede dar tres prioridades distintas.
- **Contención.** Se contradicen en parte:
  - La RFC avisa de que desconectar de la red puede activar mecanismos que borran evidencia.
  - NIST propone desconectar cables o apagar el punto de acceso para que nadie modifique datos desde fuera.
  - ENFSI plantea aislar con protección de radiofrecuencia, pero advierte de que puede agotar la batería y perder datos, y de que apagar un equipo no sirve si así se pierde todo.
- **Las personas.** La RFC pide anotar quién estaba y qué hacía. NIST pide listar a quienes tienen acceso, porque pueden dar contraseñas o indicar dónde están los datos. ENFSI pide apartar a sospechosos y testigos de los equipos. Son tres usos distintos de la misma fuente.
- **Cuánto recoger.** La RFC prefiere pecar de recoger de más. NIST admite que a veces no es práctico adquirirlo todo. ENFSI pide una búsqueda sistemática dirigida a las zonas más probables.

## Fuentes

- Brezinski, D. y Killalea, T. (2002). *RFC 3227: Guidelines for Evidence Collection and Archiving*. https://www.rfc-editor.org/info/rfc3227/
- Kent, K., Chevalier, S., Grance, T. y Dang, H. (2006). *NIST SP 800-86: Guide to Integrating Forensic Techniques into Incident Response*. https://doi.org/10.6028/NIST.SP.800-86
- ENFSI (2015). *Best Practice Manual for the Forensic Examination of Digital Technology (ENFSI-BPM-FIT-01, v01)*. https://enfsi.eu/wp-content/uploads/2016/09/1._forensic_examination_of_digital_technology_0.pdf
