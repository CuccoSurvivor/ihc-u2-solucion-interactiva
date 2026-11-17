# 2. Diseño de alternativas

**Responsable:** Daniela Barrientos

## Alternativas propuestas

### A. Panel de accesibilidad integrado

Un botón fijo "Aa" en la barra superior de Blackboard (web y app) abre un panel con un interruptor de modo oscuro, botones A− / A+ para el tamaño de letra y un reproductor de lectura en voz alta con pausa y velocidad, que lee la página en línea, sin descargar. Cada campo de texto tiene un botón de micrófono para dictar. En la clase en vivo de Collaborate desde el celular, el contenido compartido se amplía con pellizco o doble toque. Las preferencias quedan guardadas en la cuenta, así que quien activa el modo oscuro un día con dolor de cabeza lo encuentra igual en el celular.

### B. Extensión de navegador complementaria

Una extensión para Chrome o Edge, desarrollada aparte, que oscurece las páginas de Blackboard, agranda la letra, lee el texto en voz alta y permite dictar. La plataforma no se modifica, pero cada estudiante tiene que instalarla.

### C. Potenciar Ally y difundirlo

No se desarrolla nada nuevo. La universidad da a conocer lo que ya existe con un aviso en cada curso y una guía sobre el ícono de Ally y sus descargas. Para el resto, el estudiante usa el modo oscuro del sistema, el zoom del navegador y el dictado del sistema operativo o del teclado del celular.

## Comparación de propuestas

| **Criterio** | **A. Panel integrado** | **B. Extensión de navegador** | **C. Potenciar Ally y difundirlo** |
|---|---|---|---|
| Modo oscuro | Sí, en toda la plataforma | Sí, pero puede fallar en PDF y videos | Parcial: solo en el archivo descargado |
| Lectura en voz alta con pausa y velocidad | Sí, en línea, con resaltado | Sí | Parcial: MP3 descargable, lento; pausa y velocidad sin comprobar |
| Tamaño de letra ajustable | Sí, solo el texto, sin desordenar | Sí | Parcial: el zoom del navegador amplía toda la página |
| Dictado por voz | Sí, en cualquier campo de texto | Sí, solo en computador | Parcial: dictado del sistema, si el usuario lo conoce |
| Zoom en clase en vivo (Collaborate) desde el celular | Sí | No: las extensiones no funcionan en la app móvil | No |
| Funciona en celular y app | Sí | No | Parcial |
| Fácil para alguien con poca experiencia digital | Sí: un botón visible, siempre en el mismo lugar | No: hay que instalar y mantener la extensión | No: varias herramientas distintas y descargas lentas |
| Dependencia del proveedor o de TI | Alta: requiere desarrollo o configuración en Blackboard | Media: desarrollo propio, se rompe si Blackboard cambia | Baja: Ally ya está activo |
| Costo de implementación | Medio-alto (puede reutilizar Ally) | Medio | Muy bajo |
| Requisitos cubiertos (de 13) | 13 | 9 (no RF6, RF7, RNF3; RNF1 solo en computador) | Ninguno completo; 5 parciales (RF1, RF2, RF3, RF8, RNF3) |

*Tabla 5: Comparación de propuestas (elaboración propia).*

Elegimos la alternativa A, un panel de accesibilidad integrado en Blackboard, porque es la única que cubre las cinco funciones en computador y celular sin que el estudiante tenga que instalar, descargar ni configurar nada.

## Justificación de la alternativa seleccionada

Elegimos la alternativa A, un panel de accesibilidad integrado en Blackboard, porque es la única que cubre las cinco funciones en computador y celular sin que el estudiante tenga que instalar, descargar ni configurar nada.

La alternativa A responde mejor al objetivo del trabajo: que Blackboard se adapte a la condición de cada usuario. Las cinco funciones quedan en un solo botón, siempre en el mismo lugar, algo clave para un compañero de 40 años que recién aprende a usar el computador o para alguien que ese día tiene un brazo lesionado. Es la única que cumple los 13 requisitos, incluidos el zoom en Collaborate (RF6) y las preferencias sincronizadas entre dispositivos (RF7).

Descartamos B porque el celular es central en el contexto de uso, las extensiones no funcionan en la app e instalar una es justo el tipo de paso que complica a quien tiene poca experiencia digital. C es la más barata, pero deja el problema igual: en la prueba, el audio de Ally tardó más de 10 minutos en descargarse y no hay forma de escucharlo en línea.

Que Ally ya esté contratado puede bajar el costo de A, si el panel usa su motor de voz y sus temas. Se puede implementar por etapas: primero modo oscuro y tamaño de letra, después la lectura en voz alta y el dictado, y al final el zoom en Collaborate.
