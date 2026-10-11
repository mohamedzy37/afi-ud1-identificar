# Plan de identificación y preservación: Almadraba Diseño

**Lunes 20 de marzo, 10:45.** Inicio del registro de actuaciones.La única herramienta que voy a usar durante esta parte es mi lista de comprobación.

**Lo primero  que le digo a Elena es lo siguiente:**

1. Lo más valioso y frágil son el portátil encendido y bloqueado, y el móvil de empresa. Mientras sigan encendidos, no se tocan.
2. Hay más información más allá de la mesa, ademas es una información que tiene fecha de caducidad, que son tres el registro del cortafuegos (aguanta una semana), la rotación de copias del NAS (esta noche cae la más antigua) y la grabación del pasillo (no es vuestra).
3. Necesito que otros hagan cosas hoy: Bahía (congelar y exportar), la administración del edificio (grabación), Javier (pendrive), el cliente (original de la propuesta) y vuestra asesoría jurídica (qué puedo mirar y qué no).
4. No podemos aún saber a ciencia cierta quien el sospechoso hasta que no hayan pruebas que lo prueben.

---

## 1. Las fuentes de evidencia

### En la mesa de Marta (equipos vivos)
1. **Portátil Dell**, encendido y bloqueado, en el dock: memoria (claves de BitLocker, sesiones, conexiones), disco cifrado, cuenta `mgarcia` abierta.
2. **Dock USB-C**: qué está conectado y por dónde sale la red (cable o wifi).
3. **Disco externo negro de 2 TB**: posible destino de copias. Hay que saber de quién es.
4. **iPhone de empresa** (WhatsApp con clientes): mensajes, copias en la nube, posible borrado remoto.
5. **Monitores, teclado y ratón**: no guardan datos útiles, pero lo que muestran se fotografía.

### Cerca de Marta
6. **Bolso con el móvil personal de Marta**: es suyo, no de la empresa.
7. **Pendrive de Javier** (en su cajón): lo usó Marta esa semana.
8. **Pendrive propio de Marta** («no le funcionaba»): paradero desconocido.

### En la oficina
9. **Sobremesa compartido** (imprimir y escanear): sesión de Outlook abierta de otra compañera, historial de uso.
10. **Multifunción**: historial de trabajos y escaneos enviados por correo, de retención desconocida.
11. **Servidor de ficheros** (cuartito): proyectos, permisos de la carpeta del render, registros de acceso si hay auditoría.
12. **NAS de copias**: catorce copias nocturnas, en el mismo cuarto.
13. **Cortafuegos y VPN**: conexiones de la oficina y de los viernes de teletrabajo, aprox. una semana.
14. **El propio cuarto de informática**: quién entra y quién tiene llave.

### En la nube y en otras manos
15. **Cuentas Microsoft**: correo y OneDrive de `mgarcia`, registros de inicio de sesión y auditoría, y el portal donde están las claves de BitLocker.
16. **Cámara domo del pasillo y grabador de conserjería**: de la comunidad, apunta a la puerta de la oficina.
17. **Bahía Sistemas**: administra VPN, copias, claves y accesos. Es quien puede ejecutar casi todo, y cada cosa que haga cambia el sistema.
18. **El cliente hotelero**: tiene la propuesta del estudio de Sevilla con el render; su original (archivo, metadatos, correo con cabeceras) es evidencia, y también lo que el estudio le entregó hace dos semanas.
19. **Casa de Marta** (portátil los viernes, red doméstica, dispositivos personales): fuera de mi alcance.
20. **Estudio de Lucía Navarro**: fuera de mi alcance.

### Personas
21. **Marta, Elena, Javier, la compañera titular de la sesión de Outlook** y quien más tenga acceso a la carpeta del render. Lo que dicen, y a qué hora, es una fuente.

---

## 2. La prioridad

Criterio: valor probable, volatilidad real y esfuerzo (P17), y dentro de cada sistema, de más a menos volátil (P18). Contrastado con la hipótesis (P19).

| Orden | Fuente | Se pierde por | Plazo estimado | Por qué va aquí |
|---|---|---|---|---|
| 1 | Portátil vivo (1, 2) | Apagado, suspensión, reinicio forzado por actualización o gestión remota, batería, que Marta lo toque | Minutos u horas | La memoria guarda claves y sesiones que no se recuperan. Si se pierde la clave, el disco cifrado queda cerrado. |
| 2 | iPhone de empresa (4) | Borrado remoto, mensajes temporales, batería, que Marta lo use | Minutos u horas | Es lo más fácil de borrar a distancia y probablemente contiene los contactos con clientes. |
| 3 | Cuenta Microsoft de Marta y sus registros (15) | Que Marta borre desde cualquier dispositivo; retención limitada de los registros | Inmediato | Se puede preservar sin tocar nada de la mesa. Poco esfuerzo, valor alto. |
| 4 | Cortafuegos y VPN (13) | Se sobrescribe cada ~7 días | Mañana o esta semana (ver nota de fechas) | Los registros de los días clave empiezan a caducar. Los del viernes 10 de marzo probablemente ya no están. |
| 5 | NAS de copias (12) | La copia de esta noche borra la más antigua | Esta noche | Esa copia es de en torno a la fecha de la presentación en exclusiva. No hay vuelta atrás. |
| 6 | Cámara y grabador de la comunidad (16) | Sobrescritura por tiempo | Desconocido, suele ser corto | No es nuestro, así que hay que pedirlo ya. |
| 7 | Multifunción (10) | Retención desconocida | Desconocido | Esfuerzo bajo si se pide hoy. |
| 8 | Sobremesa compartido (9) | Lo usan 14 personas todo el día | Horas | Cada uso sobrescribe historial y ficheros temporales. |
| 9 | Pendrive de Javier (7) | Que se vuelva a conectar | Cualquier momento | Es una pieza concreta que Marta usó. Se asegura con una petición. |
| 10 | Servidor de ficheros (11) | Rotación de registros | Días | Los datos son estables, los registros de acceso no. |
| 11 | Disco externo y disco del portátil (3, 1) | Casi nada mientras nadie los toque | Estable | Valor alto, pero se pueden adquirir después. |
| 12 | Móvil personal de Marta (6) | Borrado en cualquier momento | Inmediato | Volátil y valioso, pero no es accesible (apartado 4). |
| 13 | Copia del cliente (18) | Casi nada | Estable | Valor alto, esfuerzo bajo: una petición de Elena. |
| 14 | Casa de Marta y estudio de Lucía (19, 20) | No controlo | — | Solo por vía legal. |

**Nota de fechas.** Javier dice «el día 14, un jueves», pero con el lunes 20 de marzo del propio relato, el jueves anterior es el 16 y el 14 fue martes. Hay que preguntarle cuál fue y dejar por escrito su respuesta (P6). Mientras tanto, pido los registros de **toda la semana del 13 al 17**.

---

## 3. Las medidas inmediatas

Se toman en este orden, y cada una se anota con hora (P3). Hasta tener decididos los límites del apartado 4, yo actúo como custodio de evidencia y Elena como testigo (P4).

| Fuente | Qué hago ahora | A quién se lo pido | Punto |
|---|---|---|---|
| **Portátil (1, 2)** | Dejarlo como está: encendido, bloqueado, en el dock y enchufado. Nadie toca teclado ni ratón. Fotografío la pantalla de bloqueo con la hora y la mesa completa con todos los cables. Anoto la hora que muestra cualquier reloj frente a la mía. | Bahía: parar reinicios, actualizaciones y políticas hacia este equipo, confirmar si hay gestión remota con borrado, y localizar ahora la clave de BitLocker de este portátil | P7, P8, P13, P14, P3, P11 |
| **Aislamiento de red del portátil** | **No lo corto a ciegas.** Primero averiguo cómo se conecta (cable o wifi) y si hay gestión remota. Luego decido con Elena y Bahía y anoto el motivo. | Bahía | P10, P20 |
| **iPhone de empresa (4)** | Fotografiar, no desbloquear. Meterlo en bolsa de aislamiento de radio con batería externa si la bolsa deja pasar el cable. Si no, dejarlo en carga y pedir que quien administra la cuenta bloquee comandos de borrado remoto. Etiquetar y registrar custodia. | Elena (confirma que es de empresa) | P12, P20, P23 |
| **Cuenta de Marta en la nube (15)** | Exportar en solo lectura los registros de inicio de sesión y auditoría (accesos a ficheros, descargas, reglas de reenvío, borrados) de `mgarcia` y de todos los usuarios con permiso a la carpeta del render. Activar conservación de su buzón y OneDrive. No desactivar la cuenta, cambiar contraseña ni licencias, y congelar cualquier trámite de baja por la excedencia. Pedir los plazos de papelera y versiones. | Bahía o quien administre Microsoft, con Elena autorizando | P11, P12, P20 |
| **Cortafuegos y VPN (13)** | Exportar hoy el registro completo tal cual, con hash, y anotar la hora del equipo frente a la real. No reiniciar. Si se puede ampliar la retención sin reiniciar, hacerlo. | Bahía | P11, P3, P23 |
| **NAS (12)** | Antes de que corra la tarea de esta noche, suspender la rotación o borrado de la copia más antigua, sin tocar ninguna copia. Anotar las fechas reales de las catorce. Si no se puede suspender, copiar primero las más antiguas. No restaurar nada encima. | Bahía | P11, P18, P22 |
| **Cámara y grabador (16)** | Pedir hoy y por escrito que conserven y exporten las grabaciones del 13 al 17 y de hoy, de la entrada y el pasillo. Preguntar plazo de conservación y hora del grabador frente a la real. No retiro el aparato. | Elena, a la administración de la comunidad | P11, P12, P3 |
| **Multifunción (10)** | Que no se apague ni se reinicie. Exportar historial de trabajos y escaneos a correo, y anotar su retención. | Bahía | P11, P13 |
| **Sobremesa compartido (9)** | Cartel y aviso: nadie lo usa desde ahora. Fotografiar la pantalla y la sesión de Outlook abierta sin interactuar. No apagar. | Elena (avisa a la plantilla) | P5, P8, P15, P20 |
| **Pendrive de Javier (7)** | Con su consentimiento, que no lo conecte a nada. Lo recojo en bolsa precintada con referencia, descripción, lugar (cajón de Javier), quién y cuándo. Nunca en un equipo normal. Registro su declaración con fecha y hora. | Javier | P6, P12, P23 |
| **Servidor de ficheros (11)** | No reiniciar. Pedir los permisos de la carpeta del render (quién podía abrirlo) y los registros de acceso si hay auditoría. | Bahía | P11, P19 |
| **Disco externo y dock (3, 2)** | Fotografiar modelo y número de serie. No desconectar mientras el portátil esté vivo. Preguntar a Elena si figura en el inventario del estudio. Adquisición después. | Elena | P7, P12, P22 |
| **Móvil personal de Marta (6)** | No tocar. Anoto textualmente lo que Marta dice de él. Si ella consiente, se registra por escrito; si no, se consulta a jurídico. | Marta, con Elena presente | P6, P12, P15 |
| **Copia del cliente (18)** | Que conserve el original de la propuesta recibida (archivo y correo con cabeceras) y de lo que el estudio le presentó. | Elena, al cliente | P11, P12 |
| **Cuarto de informática (14)** | Cerrar con llave y apuntar quién entra y quién tiene llave. | Elena | P5, P7 |

### Personas

- **Marta.** Elena, como testigo, le explica con tono neutro que no puede usar ni llevarse equipos de empresa ni acceder a cuentas de empresa. Si Elena decide que puede irse a casa, puede irse: no se la retiene ni se la acusa. Se le pide consentimiento para el móvil personal y, si es suyo, para el disco externo. Su frase sobre el móvil se apunta tal cual (P5, P6, P19).
- **Javier.** Declaración separada de Marta, y aclarar la fecha. Se le pide que no comente nada con ella (P5, P6).
- **Compañera de la sesión abierta.** Identificarla. Cuando haya fotografiado el estado, que cierre ella su sesión. No leo su correo (P8, P15).
- **Quién más tiene acceso a la carpeta del render.** Se saca de los permisos del servidor, no de preguntas por la oficina (P19).

---

## 4. Los límites

| Qué no hago | Por qué | Qué hago en su lugar | Punto |
|---|---|---|---|
| Apagar, suspender, reiniciar o desenchufar el portátil | Se pierden la memoria y la clave. BitLocker bloquea el disco. | Mantenerlo vivo, vigilado y enchufado. Pedir a Bahía que pare reinicios. | P14 |
| Desbloquearlo o adivinar la contraseña | Cambia el estado y puede alertar o borrar. Hay que decidir quién y con qué permiso. | Decidirlo con Elena y jurídico. Si se hace, lo ejecuta una persona, con herramientas de medio protegido y cada acción anotada. Hasta entonces, queda bloqueado. | P1, P2, P21, P22 |
| Cortar la red del portátil a ciegas | Puede activar mecanismos de borrado, pero dejarlo conectado permite cambios remotos. No sé aún cuál pesa más. | Averiguar primero cómo se conecta y si hay gestión remota, y decidir con motivo anotado. | P10, P20 |
| Mirar el bolso o el móvil personal de Marta | Es propiedad suya y la empresa no tiene derecho a revisarlo. | Pedir su consentimiento por escrito. Si no, jurídico y, si procede, vía policial. | P12, P15 |
| Mirar los archivos personales de Marta en el portátil | Hay datos privados sin relación con el caso. | Acotar la revisión a lo relevante, con el visto bueno de jurídico. | P1, P15 |
| Leer el correo abierto de la compañera | Es de otra persona, ajena al caso. | Fotografiar sin interactuar. | P8, P15 |
| Quitarle el pendrive a Javier sin su permiso | Es suyo. | Pedírselo y registrar su consentimiento. | P12 |
| Retirar la grabación de la comunidad | No es de Almadraba. | Petición formal de Elena. | P12 |
| Contactar con Lucía, acceder a la casa de Marta o a sus cuentas personales | No tengo autoridad ni permiso. | Si se denuncia, que lo gestionen jurídico y la policía. | P12, P21 |
| Acusar o confrontar a Marta | La hipótesis sigue abierta. | Dejar que Elena le comunique las restricciones y anotar todo. | P19 |
| Que Bahía «mire a ver» | Cada consulta cambia registros y puede borrar los que caducan. | Acciones solo por petición mía, en solo lectura, por escrito y con hora. | P21, P22 |
| Analizar nada todavía | Primero se recoge, después se analiza. | Preservar, hashear, etiquetar. Análisis solo sobre copias. | P22, P23 |

---

## 5. De dónde sale cada decisión

| Punto | Norma | Decisiones de este plan donde se aplica |
|---|---|---|
| P1 Autoridad y marco | RFC 3227 §2; NIST §3.1.2; ENFSI §8.2 | Consulta a jurídico antes de acceder al portátil o a datos personales |
| P2 Material listo | RFC 3227 §2.2; NIST §3.1.2; ENFSI §9.1 | Herramientas de medio protegido para memoria y adquisición |
| P3 Registro desde el minuto cero | RFC 3227 §2, §3.2 | Hora de inicio, relojes de cortafuegos, grabador y equipos frente a la real |
| P4 Custodio de evidencia | NIST §3.1.2 | Yo custodio, Elena testigo |
| P5 Aparta a las personas | ENFSI §8.2; NIST §3.1.3 | Marta fuera del puesto, Javier separado, cuarto cerrado, sobremesa fuera de uso |
| P6 Anota a las personas | RFC 3227 §3.2; NIST §3.1.3 | Declaraciones de Marta y Javier, fecha dudosa del 14 |
| P7 Foto y croquis | ENFSI §8.2; NIST §3.1.2 | Mesa completa, dock y disco, cuarto de informática |
| P8 Pantalla | NIST §3.1.2 | Pantalla de bloqueo del portátil, sesión de Outlook del sobremesa |
| P10 Conexiones y configuración | ENFSI §9.2; RFC 3227 §2.1; NIST §3.1.3 | Cómo se conecta el portátil, antes de decidir el aislamiento |
| P11 Fuera de la sala | RFC 3227 §2.1; NIST §3.1.1 | Cortafuegos, NAS, nube, servidor, multifunción, cámara, cliente |
| P12 Dueño y permisos | NIST §3.1.1 | Móvil de Marta, pendrive de Javier, disco externo, grabación de la comunidad, casa de Marta y Lucía |
| P13 Estado de cada equipo | ENFSI §8.2, §9.2 | Portátil vivo, multifunción encendida |
| P14 Qué se perdería al apagar | ENFSI §9.1, §9.2; RFC 3227 §2.2 | Portátil vivo, clave de BitLocker localizada de antemano |
| P15 Privacidad | RFC 3227 §2.3 | Móvil personal, archivos personales, correo de la compañera |
| P17 Valora cada fuente | NIST §3.1.2 | Tabla de prioridad (valor, volatilidad, esfuerzo) |
| P18 Ordena por volatilidad | RFC 3227 §2.1, §3.2; NIST §3.1.2 | Orden 1 a 14, y NAS antes de esta noche |
| P19 Contrasta con la hipótesis | ENFSI §8.2 | Registros de todos los usuarios con permiso a la carpeta, tono neutro con Marta |
| P20 Contención | RFC 3227 §2.2; NIST §3.1.3; ENFSI §8.2 | iPhone en bolsa con alimentación, decisión de red del portátil con motivo anotado |
| P21 Quién ejecuta | ENFSI §9.2; NIST §3.1.2 | Acciones de Bahía bajo mi petición, policía para lo ajeno |
| P22 Recoger antes de analizar | RFC 3227 §2, §2.2 | NAS sin restaurar, nada de análisis en originales |
| P23 Verifica y etiqueta | NIST §3.1.2; RFC 3227 §3.2; ENFSI §8.2 | Hash de registros exportados, pendrive y iPhone etiquetados con custodia |

**Dos decisiones donde las normas chocan y he elegido, con motivo:**

- **Aislar o no la red del portátil (P20).** La RFC 3227 §2.2 avisa de que desconectar puede activar un borrado; NIST §3.1.3 lo recomienda para evitar cambios remotos. No decido a ciegas: primero averiguo cómo se conecta y si hay gestión remota, y lo anoto.
- **Cuánto preservar (P16).** NIST §3.1.2 y la RFC 3227 §3.2 dicen que ante la duda se preserva. Aquí lo aplico a los registros que caducan (cortafuegos, NAS, grabación), porque son los únicos que no se pueden recuperar después. El resto se preserva en su sitio, sin adquirir todavía.