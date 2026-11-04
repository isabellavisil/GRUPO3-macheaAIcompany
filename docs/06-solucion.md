# 06 · Solución y flujo de información

## Solución propuesta

**Qué cambia en el proceso con la solución (máximo 5 líneas):**

1. El interesado ya no deja solo nombre y teléfono: llena un formulario interactivo con IA que le muestra el inmueble y recoge sus necesidades y presupuesto.
2. Machea perfila y califica cada lead según su capacidad financiera; los curiosos pasan a seguimiento automático y no le quitan tiempo al asesor.
3. El agente de voz con IA llama al lead calificado, confirma su interés y agenda la cita.
4. El lead se asigna por turnos al asesor, que lo ve en «Mi día» con un reloj de respuesta y lo contacta con un clic.
5. El gerente ve en un panel el porcentaje de leads contactados en menos de 5 minutos y los que siguen esperando.

## Flujo de información

![Flujo de información](../assets/flujo-informacion.png)

Inicio: **Interesado deja sus datos**.

| Paso | Entrada (qué información llega) | Proceso (qué se hace) | Responsable (quién) | Salida (qué información sale) |
|---|---|---|---|---|
| 1 | Datos de contacto, tipo de inmueble, zona, presupuesto e ingresos del interesado | Diligenciar el formulario interactivo de vivienda | Interesado (cliente potencial) | Lead registrado con sus necesidades y datos financieros |
| 2 | Lead registrado con sus necesidades y datos financieros | Perfilar y calificar el lead con IA | Machea (IA) | Perfil del lead y puntaje de calificación (calificado / no calificado) |
| 3 | Lead no calificado (puntaje bajo) | Enviar información y dejar el lead en seguimiento automático | Machea (IA) | Lead en seguimiento (fin) |
| 4 | Lead calificado con su perfil | Llamar al lead y agendar la cita | Machea (agente de voz IA) | Interés confirmado y cita agendada |
| 5 | Lead calificado con cita agendada | Asignar el lead por turnos al asesor y enviarle un aviso | Machea (IA) | Lead asignado en «Mi día» del asesor y aviso enviado |
| 6 | Lead asignado con perfil, cita y reloj de respuesta | Contactar al lead con un clic y registrar el resultado | Asesor comercial | Lead contactado, resultado registrado y cita confirmada (fin) |
| 7 | Tiempos de respuesta y estado de los leads del equipo | Revisar en el panel los leads contactados a tiempo | Gerente comercial | Porcentaje de leads contactados en menos de 5 minutos y leads en espera (fin) |

**Decisión:** ¿El lead está calificado? **Sí:** Llamar al lead y agendar la cita (paso 4). **No:** Enviar información y dejar el lead en seguimiento automático (paso 3).

Después del paso 5, un paralelo (+) lanza a la vez el paso 6 y el paso 7.

Finales:
- **Lead en seguimiento** (tras el paso 3)
- **Cita confirmada** (tras el paso 6)
- **Tiempo de respuesta controlado** (tras el paso 7)

## Antes y después

| Proceso actual | Proceso con la solución |
|---|---|
| El interesado deja solo nombre y teléfono, sin información de sus necesidades ni de su capacidad financiera. | El formulario interactivo recoge necesidades, presupuesto e ingresos desde el primer contacto. |
| El asesor llama a todos los leads, incluidos los curiosos: de cada 10, solo 1 o 2 quieren comprar. | La IA califica cada lead y solo los calificados llegan al asesor; los curiosos quedan en seguimiento automático. |
| El primer contacto tarda horas o días, y el lead se enfría o se va con otra inmobiliaria. | El agente de voz llama al lead calificado, y el asesor lo contacta con un clic con un reloj que le exige responder en menos de 5 minutos. |
| Los leads se reparten de forma informal por WhatsApp y la agenda queda en el celular de cada asesor. | Cada lead se asigna por turnos al asesor, que recibe un aviso y lo ve en su pantalla «Mi día». |
| El asesor coordina la cita él mismo, con varias llamadas y mensajes. | El agente de voz deja la cita agendada antes de que el asesor contacte al lead. |
| El gerente no sabe cuánto tarda el equipo en responder ni cuántos leads se pierden. | El gerente ve en un panel el porcentaje de leads contactados a tiempo y los que siguen esperando. |
