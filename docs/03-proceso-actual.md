# Proceso actual

## 1. BPMN de práctica

![BPMN de práctica](../assets/bpmn-taller.png)

**Declaración de IA:** Claude (Claude Sonnet 5.5) – 26/10/2026 – prompt registrado en docs/11-uso-ia.md

## 2. El proceso elegido

**Nombre del proceso:** Inscripción de asistentes a cada taller (Fundación Semillas del Barrio)

**Carriles (responsables):**
- Coordinadora de talleres
- Asistente (joven)
- Formulario QR + hoja de cálculo

**Fuente (contacto, cargo y fecha):** [nombre del contacto], [cargo], [dd/mm/aaaa]

## 3. Pasos del proceso

Inicio: **Taller programado**.

| # | Paso (verbo + objeto) | Responsable |
|---|---|---|
| 1 | Definir el cupo máximo del taller y generar el código QR | Coordinadora de talleres |
| 2 | Publicar el código QR en la convocatoria del taller | Coordinadora de talleres |
| 3 | Escanear el código QR con el celular | Asistente (joven) |
| 4 | Diligenciar y enviar el formulario de inscripción | Asistente (joven) |
| 5 | Registrar la inscripción en la hoja de cálculo | Formulario QR + hoja de cálculo |
| 6 | Confirmar la inscripción y descontar un cupo | Formulario QR + hoja de cálculo |
| 7 | Enviar la confirmación de inscripción al asistente | Formulario QR + hoja de cálculo |
| 8 | Consultar la lista de inscritos y los cupos disponibles | Coordinadora de talleres |
| 9 | Informar al asistente que el cupo está agotado | Formulario QR + hoja de cálculo |

**Decisión:** ¿Hay cupos disponibles? **Sí:** Confirmar la inscripción y descontar un cupo (paso 6). **No:** Informar al asistente que el cupo está agotado (paso 9).

Después del paso 6, un paralelo (+) lanza a la vez el paso 7 y el paso 8.

Finales:
- **Inscripción confirmada** (tras el paso 7)
- **Lista revisada** (tras el paso 8)
- **Inscripción no realizada** (tras el paso 9)

## 4. Diagrama BPMN

![BPMN proceso actual](../docs/assets/Diagrama ghant.png)

Archivo editable: [bpmn-actual.bpmn](../assets/bpmn-actual.bpmn)

## 5. Puntos críticos

Son hipótesis tomadas del diagrama. Falta la evidencia del contacto.

| PC | Qué pasa (se demora, se repite o se pierde) | Evidencia (dato o frase del contacto, con fecha) |
|---|---|---|
| PC1 | El registro y el descuento del cupo dependen de una hoja de cálculo. Si dos jóvenes se inscriben a la vez, el cupo puede quedar mal descontado o la inscripción duplicada. | [dato o frase – dd/mm/aaaa] |
| PC2 | Cuando el cupo se agota, el proceso termina en «Inscripción no realizada». No hay lista de espera ni otra opción, y se pierde al joven interesado. | [dato o frase – dd/mm/aaaa] |
| PC3 | La coordinadora solo conoce los inscritos y los cupos cuando consulta la lista. No recibe un aviso al llenarse el taller. | [dato o frase – dd/mm/aaaa] |

## 6. Uso de IA

| Herramienta y versión | Fecha | Prompt |
|---|---|---|
| Claude (Claude Sonnet 5.5) | 26/10/2026 | «Genera de nuevo en este formato y devuélvelo, según el diagrama» (imagen del BPMN «Inscripción de asistentes a cada taller» más la plantilla de «Proceso actual») |
