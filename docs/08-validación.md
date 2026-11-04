# 08 · Validación

## 1. Comparativa de métodos de testeo Lean UX

Analizamos cinco métodos de testeo para decidir cuál se ajusta mejor a nuestro prototipo: un panel web (CRM) en versión 0.1 con tres pantallas: «Mi día» del asesor, el reparto automático por turnos y el panel del gerente.

| Método | Qué valida | Cómo se aplica | Ventaja | Limitación | ¿Aplica a nuestro prototipo? |
|---|---|---|---|---|---|
| **Prueba de usabilidad** | Si el usuario logra completar tareas reales con el producto y dónde se confunde. | Se pide a asesores y gerente que hagan tareas concretas en el panel mientras observamos, medimos tiempos y registramos dificultades. | Muestra el comportamiento real y permite medir nuestra métrica de 5 minutos. | Con pocos participantes los resultados son cualitativos y no estadísticos. | **Sí.** El prototipo ya es funcional y registra la hora del primer contacto. |
| **Mago de Oz** | Si la solución genera valor antes de automatizarla, con una persona que simula el sistema por detrás. | El usuario cree que el sistema funciona solo, pero una persona del equipo realiza manualmente la parte que aún no está construida. | Permite probar ideas complejas sin desarrollarlas. | Exige esfuerzo manual del equipo y no escala a varios usuarios al mismo tiempo. | **Parcial.** Sirve para simular llamadas de la asistente de voz, pero el panel ya funciona y no requiere simulación. |
| **Test A/B** | Cuál de dos versiones de una pantalla o función da mejores resultados. | Se muestran dos variantes a grupos distintos y se compara una métrica. | Da evidencia cuantitativa para decidir entre alternativas. | Necesita muchos usuarios y leads; con 2 o 3 asesores no hay volumen suficiente. | **No.** Nuestra muestra es pequeña y todavía tenemos una sola versión. |
| **Prueba de 5 segundos** | Si una pantalla comunica su propósito y lo importante a primera vista. | Se muestra la pantalla durante 5 segundos y luego se pregunta qué recuerdan y entendieron. | Es rápida y barata, y sirve para evaluar claridad visual. | No evalúa el flujo completo ni el uso real durante la jornada. | **Parcial.** Puede servir como complemento para «Mi día», pero no mide el tiempo de respuesta. |
| **Puerta falsa** | Si existe interés en una función antes de construirla. | Se ofrece la función con un botón o página que aún no existe y se mide cuántos la usan. | Valida demanda con muy poco esfuerzo. | Mide interés, no uso ni satisfacción, y puede frustrar a quien intenta usarla. | **No.** Ya construimos el prototipo y necesitamos validar su uso, no el interés. |

## 2. Método elegido y por qué

Elegimos la **prueba de usabilidad** remota con leads de prueba, porque nuestro panel ya es funcional y registra la hora del primer contacto.
Nos permite observar si el asesor entiende «Mi día», contacta con un clic y si el gerente interpreta su panel.
Además, mide directamente nuestra métrica: que al menos 8 de cada 10 leads se contacten en menos de 5 minutos.

## 3. Plan de testeo

| Elemento | Detalle |
|---|---|
| **Hipótesis** | Creemos que el asesor comercial podrá dejar de perder leads por responderles tarde si usa una página donde ve cada lead nuevo con un reloj de respuesta y lo contacta con un clic. |
| **Participantes** | Dos o tres asesores comerciales de una inmobiliaria o constructora de Bogotá, de los gerentes con los que ya tenemos cita, y su gerente, que revisa el panel del equipo. |
| **Tarea 1** | Al recibir el aviso de asignación, abrir «Mi día», identificar el lead que lleva más tiempo esperando y contactarlo con el botón Llamar o WhatsApp. |
| **Tarea 2** | Registrar el resultado del contacto en el lead con el botón «Registrar resultado». |
| **Tarea 3** | (Gerente) En el panel del gerente, indicar el porcentaje de leads contactados a tiempo y señalar qué leads siguen esperando. |
| **Métrica de éxito** | En los 5 días de prueba, al menos 8 de cada 10 leads nuevos se contactan en menos de 5 minutos, medidos entre la llegada del lead y el primer clic en Llamar o WhatsApp. Además, al menos 2 de los participantes completan las tres tareas sin ayuda del equipo. |
| **Indicadores de apoyo** | Tiempo mediano de respuesta, porcentaje de leads contactados en la semana y leads con más de 15 minutos de espera. |
| **Reglas de medición** | El reloj solo corre en horario permitido para contacto comercial: lunes a viernes de 7:00 a 19:00 y sábados de 8:00 a 15:00. Los leads de prueba son enviados por el equipo si aún no hay leads reales, y el resultado indicará cuál fue el caso. |
| **Lugar** | A distancia. Los asesores usan el panel desde su celular y su computador, en su trabajo normal. Las tareas guiadas se hacen por videollamada con pantalla compartida. |
| **Fecha** | Del lunes 9 al viernes 13 de noviembre de 2026. Las tareas guiadas se realizan el lunes 9; revisamos los tiempos de respuesta al final de cada día y cerramos con una conversación breve el viernes 13. |
| **Materiales** | Enlace al panel v0.1, al menos 20 leads de prueba, guía con las tres tareas, formato de observación, registro de horas del panel, videollamada con grabación de pantalla (con consentimiento de los participantes) y preguntas de cierre. |
| **Responsables por rol** | **Facilitador:** guía las tareas y conduce la conversación de cierre. **Observador:** anota dificultades, comentarios y tiempos. **Responsable del panel y los datos:** envía los leads de prueba, verifica el reparto y los avisos, y revisa los tiempos cada día. **Responsable del video:** graba las sesiones y edita el video final. |

## 4. Resultados

### Qué observamos

### Qué dijo el usuario

### Qué vamos a cambiar

Video: [ENLACE]

