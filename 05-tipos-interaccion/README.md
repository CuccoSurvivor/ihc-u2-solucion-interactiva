# 5. TIPOS DE INTERACCIÓN

Responsable: Ignacio Tabilo

Los tipos de interacción describen las formas en que una persona interactúa con un producto. Rogers et al. (2023, cap. 3) distinguen cinco: instruir, conversar, manipular, explorar y responder. No son excluyentes, y una misma solución suele combinar varios. En la siguiente tabla, la columna “En qué consiste” resume con nuestras palabras la definición de esos autores; las acciones concretas y la valoración de presencia son análisis propio del equipo.

| Tipo | En qué consiste | Acciones concretas del usuario en la propuesta | Presencia |
| :--- | :--- | :--- | :--- |
| Instruir | El usuario le da órdenes al sistema mediante botones, menús o comandos | Toca el botón “Aa” para abrir o cerrar el panel. Activa o desactiva el interruptor de modo oscuro (RF1). Presiona A+ o A− para cambiar el tamaño de letra (RF2). Presiona reproducir, pausar o retomar la lectura (RF3). Elige la velocidad de lectura, entre 0,75x y 2x (RF4). Toca el micrófono para iniciar o detener el dictado (RF8) | Principal |
| Conversar | El usuario y el sistema intercambian información como en un diálogo, por voz o por texto | Dicta en voz alta su respuesta en un foro y el sistema la escribe (RF8). Escucha el contenido que el sistema le lee en español (RF3, RNF4). Revisa y corrige lo dictado antes de enviar | Parcial |
| Manipular | El usuario actúa directamente sobre objetos en pantalla, con gestos parecidos a los del mundo físico | Pellizca el contenido compartido en Collaborate para ampliarlo o reducirlo (RF6). Arrastra con el dedo para mover la vista ampliada. Hace doble toque para ampliar y para volver al tamaño original | Secundaria |
| Explorar | El usuario se desplaza por un entorno virtual o físico | Recorre la presentación o pizarra ampliada para ubicar el detalle que muestra el docente. Sigue con la vista el texto resaltado mientras avanza la lectura (RF5) | Baja |
| Responder | El sistema toma la iniciativa y el usuario decide si responde | Al entrar desde otro dispositivo, ve el aviso de que se aplicaron sus ajustes y puede mantenerlos o deshacerlos (RF7). Acepta o rechaza el permiso de micrófono la primera vez que dicta. Si el sistema avisa que no captó su voz, reintenta o escribe con el teclado | Secundaria |

## 5.1. Análisis
El tipo predominante es instruir. Es coherente con la metáfora del tablero de control, porque el usuario da órdenes cortas y obtiene un resultado inmediato, y con el requisito de llegar a cada función en máximo dos toques (RNF1). También es el tipo más fácil de aprender para alguien con poca experiencia digital, porque cada botón hace una sola cosa.

Conversar está presente solo de forma parcial. La propuesta usa la voz como entrada (dictado) y como salida (lectura), pero el sistema no interpreta preguntas ni mantiene un diálogo. Descartamos un asistente conversacional porque el contexto de uso incluye transporte público y lugares con ruido, y porque hablarle a la plataforma para cambiar un ajuste toma más pasos que tocar un interruptor.

Manipular se concentra en el zoom de la clase en vivo, donde el gesto de pellizco es más directo que cualquier botón. Explorar tiene poca presencia: la solución no ofrece un entorno para recorrer y lo más cercano es moverse por el contenido ampliado. Responder aparece en los avisos del sistema; los mantenemos breves y siempre con la opción de deshacer, para que el usuario conserve el control.

## 5.2. Tipos de interacción en la tarea principal
Para comprobar que la tabla anterior calza con el uso real, recorrimos los pasos de la tarea principal y de las tareas secundarias definidas en el apartado de requisitos.

| Paso de la tarea | Acción del usuario | Tipo de interacción |
| :--- | :--- | :--- |
| 1. Entrar al curso | Navega por Blackboard como siempre; si ya tiene ajustes guardados, se aplican solos | Responder |
| 2. Abrir el contenido | Abre el material de la unidad y toca “Aa” | Instruir |
| 3. Ajustar la apariencia | Activa el modo oscuro y sube un nivel el tamaño de letra | Instruir |
| 4. Escuchar el texto | Presiona reproducir, pausa cuando quiere y cambia la velocidad | Instruir y conversar (parcial) |
| 5. Volver a la lectura visual | Pausa la lectura y sigue leyendo desde el texto resaltado | Instruir y explorar |
| Secundaria: responder en un foro | Toca el micrófono, dicta y corrige antes de enviar | Instruir y conversar (parcial) |
| Secundaria: seguir la clase desde el celular | Pellizca y arrastra el contenido compartido | Manipular y explorar |
