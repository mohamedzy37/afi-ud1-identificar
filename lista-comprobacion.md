# Lista de comprobación de escena: identificar antes de tocar

Fuentes: **RFC 3227** (§2, §3), **NIST SP 800-86** (§3.1) y **ENFSI BPM-FIT-01** (§8.2, §9.1, §9.2). Cada punto indica de dónde sale.

**Pregunta que se repite en cada paso:** ¿qué más puede ser evidencia? [RFC 3227 §3.2]

---

## 1. Al llegar (asegurar y registrar, sin tocar equipos)

- [ ] **1. Autoridad y marco.** ¿Quién autoriza? ¿Qué política del sitio o guía policial rige? ¿A quién aviso (respuesta a incidentes, fuerzas de seguridad, jurídico)? [RFC 3227 §2; NIST §3.1.2; ENFSI §8.2]
- [ ] **2. Material listo.** Herramientas de recogida en medio protegido, cámara, medios vacíos, bolsas, etiquetas y formularios de custodia. Plan previsto para memoria viva, cifrado activo y reinicio remoto. [RFC 3227 §2.2; NIST §3.1.2; ENFSI §9.1]
- [ ] **3. Registro desde el minuto cero.** Notas con fecha y hora, indicando si es UTC o local, y desfase del reloj del sistema. Transcripción automática, nunca en un medio que sea evidencia. [RFC 3227 §2, §3.2]
- [ ] **4. Un custodio de evidencia.** Una sola persona fotografía, documenta y etiqueta cada elemento y anota quién hizo qué, dónde y cuándo. [NIST §3.1.2]
- [ ] **5. Aparta a las personas de equipos y comunicaciones.** Sospechosos y testigos lejos de los exhibits y de cualquier dispositivo que pueda interactuar con ellos. [ENFSI §8.2; NIST §3.1.3]
- [ ] **6. Anota a las personas.** Quién estaba, qué hacía, qué observó, cómo reaccionó. Lista de usuarios con acceso al equipo: pueden dar claves o decir dónde están los datos. [RFC 3227 §3.2; NIST §3.1.3]
- [ ] **7. Foto y croquis de la escena** con ubicación y estado de cada elemento relevante. Registros hechos en el momento. [ENFSI §8.2; NIST §3.1.2]

## 2. Antes de tocar nada (mirar, preguntar, enumerar)

- [ ] **8. Pantalla.** Anota o fotografía lo visible (documentos, programas en marcha) y si hay salvapantallas, que puede tener contraseña. [NIST §3.1.2]
- [ ] **9. Fuentes físicas.** Recorre el espacio y enumera equipos, servidores, almacenamiento en red, portátiles, soportes externos (USB, tarjetas, discos), móviles, cámaras y grabadoras. [NIST §3.1.1; ENFSI §9.2]
- [ ] **10. Conexiones y configuración.** Cables, wifi, puntos de acceso al alcance, topología, configuración de dispositivos y de red. [ENFSI §9.2; RFC 3227 §2.1; NIST §3.1.3]
- [ ] **11. Fuentes fuera de la sala.** Logs de red y de aplicaciones, logs centralizados y remotos, copias de seguridad, controles de monitorización (IDS, antivirus), registros del ISP. [RFC 3227 §2.1; NIST §3.1.1]
- [ ] **12. Dueño y permisos de cada fuente.** Equipo personal, de contratista, teletrabajo, ISP (suele exigir orden judicial), otras jurisdicciones. Si una fuente no es alcanzable, busca otra que tenga los mismos datos. [NIST §3.1.1]
- [ ] **13. Estado de cada equipo.** ¿Encendido? ¿Conectado a la red o por radio? ¿Con batería? ¿Activo ahora mismo? [ENFSI §8.2, §9.2]
- [ ] **14. Qué se perdería al apagar o incautar.** Memoria viva, cifrado activo, sesiones, reinicio remoto. Apagar no sirve si destruye lo relevante. [ENFSI §9.1, §9.2; RFC 3227 §2.2]
- [ ] **15. Privacidad.** No entres en zonas sin motivo habitual (archivos personales) salvo indicio suficiente de incidente real, y comprueba que el procedimiento te respalda. [RFC 3227 §2.3]

## 3. Al decidir qué se adquiere y en qué orden

- [ ] **16. ¿Hay que preservar para un proceso legal o disciplinario?** Decídelo antes de recoger, con dirección y asesoría jurídica. Si hay duda, preserva: mejor recoger de más que de menos. [NIST §3.1.2; RFC 3227 §3.2]
- [ ] **17. Valora cada fuente** por valor probable, volatilidad y esfuerzo. Si son demasiadas para adquirirlas todas, deja el plan escrito. [NIST §3.1.2]
- [ ] **18. Ordena dentro de cada sistema de más a menos volátil:** registros y caché; tablas de red, procesos y memoria; temporales; disco; logs remotos; topología; archivo. Es un orden de ejemplo: revisa si hay logs que se sobrescriben. [RFC 3227 §2.1, §3.2; NIST §3.1.2]
- [ ] **19. Contrasta con la hipótesis.** ¿Es esto lo más probable según lo que se alega? Si hay otras disciplinas (ADN, huellas), pacta la secuencia según lo destructiva que sea cada una. [ENFSI §8.2]
- [ ] **20. Contención: decídela con el equipo y anota el motivo.** Pesa tres riesgos: interruptores que borran al perder la red [RFC 3227 §2.2], cambios remotos si no se aísla [NIST §3.1.3], y pérdida de datos por batería o por la radio [ENFSI §8.2]. No apagues hasta terminar. [RFC 3227 §2.2]
- [ ] **21. Quién ejecuta.** Tú, un administrador de confianza o la policía (ISP, equipos ajenos). Si tomas el control de un sistema, respondes de lo que pase. [ENFSI §9.2; NIST §3.1.2]
- [ ] **22. Recoger antes de analizar.** Paso a paso en cada sistema (en paralelo entre sistemas), con herramientas de medio protegido y sin programas que cambien los tiempos de acceso (como `tar` o `xcopy`). [RFC 3227 §2, §2.2]
- [ ] **23. Verifica y etiqueta.** Hash del original y de la copia, análisis solo sobre copia. Etiqueta con referencia única, descripción, lugar, quién y cuándo, y custodia documentada. [NIST §3.1.2; RFC 3227 §3.2; ENFSI §8.2]