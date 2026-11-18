# 4. MÉTAFORA DE INTERFAZ

Responsable: Ignacio Tabilo

Una metáfora de interfaz aprovecha lo que la persona ya sabe de un objeto o de una actividad conocida para que entienda más rápido un sistema que ve por primera vez (Rogers et al., 2023, cap. 3). En nuestro caso importa especialmente, porque entre los usuarios hay compañeros que recién aprenden a usar un computador y la solución debe poder usarse sin capacitación previa (RNF5).

## 4.1. Metáfora seleccionada
Elegimos la metáfora del tablero de control, tomando como referente el panel de ajustes rápidos del celular, llamado “Quick Settings” en Android (Google, s.f.) y “Centro de control” en iPhone (Apple, 2026). Es el panel que se abre deslizando el dedo desde el borde de la pantalla y donde se enciende el wifi, se baja el brillo o se pausa la música con un toque. El botón “Aa” es la entrada al tablero y cada función del panel es un control que se ve, se toca y muestra en qué estado quedó.

Esta elección da continuidad al modelo conceptual, donde ya se indicó que el panel de accesibilidad se apoya en el conocimiento previo del panel de ajustes rápidos del celular (Tabla 9). Aquí la convertimos en la metáfora que ordena toda la interfaz.

*(Insertar Figura 3: Correspondencia entre los ajustes rápidos del celular y el panel “Aa”)*

## 4.2. Correspondencia entre la metáfora y la solución
La siguiente tabla muestra qué elemento conocido del tablero corresponde a cada elemento de la propuesta y qué entiende el usuario gracias a esa relación.

| En el tablero que ya conoce | En nuestra solución | Qué entiende el usuario |
| :--- | :--- | :--- |
| El panel aparece siempre desde el mismo lugar | Botón “Aa” fijo en la barra superior, en web y app | Sabe dónde ir sin buscar, desde cualquier página (RNF1) |
| Interruptor de encendido y apagado (wifi, linterna) | Interruptor de modo oscuro | Hay dos estados y se ve cuál está activo (RF1) |
| Control de brillo o volumen, que sube y baja | Botones A− / A+ con indicador de nivel | El texto cambia de a un paso y se puede volver atrás (RF2) |
| Controles de música: reproducir, pausar | Reproductor de lectura en voz alta con pausa y velocidad | La lectura se maneja igual que una canción o un podcast (RF3, RF4) |
| El cambio se nota al instante, sin botón “Guardar” | Cada ajuste se aplica de inmediato sobre la página | Puede probar sin miedo a equivocarse |
| Los ajustes siguen ahí al volver a abrir el panel | Preferencias guardadas en la cuenta | No tiene que configurar todo de nuevo (RF7) |

El dictado por voz y el zoom en la clase en vivo no están dentro del panel, porque se usan en el lugar donde se necesitan. Para ellos mantenemos las metáforas complementarias definidas en el modelo conceptual: el micrófono de los mensajes de voz para dictar y el pellizco con que se amplían fotos y mapas para el zoom.

## 4.3. Por qué esta metáfora ayuda al usuario
*   **Se aprende sin instrucciones.** El usuario reconoce interruptores, niveles y botones de reproducción que ya usa en otras aplicaciones, por lo que no tiene que aprender conceptos nuevos. Esto responde directamente a RNF5.
*   **Reconoce en vez de recordar.** Todas las opciones están a la vista en una sola pantalla y cada control muestra su estado, como recomiendan las heurísticas de “reconocer en lugar de recordar” y de “visibilidad del estado del sistema” (Nielsen, 1994). Es lo contrario de lo que ocurre hoy con Ally, cuyas opciones están detrás de un ícono pequeño y archivo por archivo.
*   **Da sensación de control.** Todo cambio es inmediato y reversible con el mismo toque, en línea con la heurística de “control y libertad del usuario”, que pide ofrecer siempre una forma de deshacer (Nielsen, 1994). Para alguien como Camila, que llega con dolor de cabeza después del trabajo, significa activar el modo oscuro en dos toques y desactivarlo igual de fácil.
*   **Calza con la forma real de uso.** Las funciones son independientes entre sí y se usan según la condición del momento, que puede cambiar durante el mismo día. Un tablero permite tocar solo lo que se necesita, sin seguir un orden.
*   **Es la misma en computador y celular.** Un panel con controles grandes funciona con mouse y con el dedo, lo que apoya RNF3.

Reconocemos un supuesto: que el estudiante con poca experiencia en computador sí está familiarizado con el celular. Es razonable dentro del contexto de uso descrito, pero debe confirmarse cuando se pruebe el prototipo con usuarios.

## 4.4. Metáforas que evaluamos y descartamos

| Metáfora | Cómo se vería | Evaluación | Decisión |
| :--- | :--- | :--- | :--- |
| Tablero de control | Un panel con todos los controles visibles y efecto inmediato | Acceso directo a cada función, en cualquier orden y en máximo 2 toques | Seleccionada |
| Asistente paso a paso | Una secuencia de pantallas que pregunta cómo se quiere leer y escuchar | Guía bien la primera vez, pero obliga a recorrer pasos para un cambio rápido y no cumple RNF1 | Descartada como metáfora principal |
| Ficha de preferencias | Un formulario en el perfil del usuario, con botón “Guardar” | Queda lejos del contenido y el efecto no se ve hasta guardar y volver | Descartada |
| Agenda o mapa | Contenido ordenado por fechas o por recorridos | La solución no organiza tiempo ni lugares; no hay relación con la tarea | No aplica |

## 4.5. Límites de
