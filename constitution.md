# Constitution — FA-production

> **Documento rector del proyecto.** Esta constitución establece cómo se organiza, documenta y desarrolla FA-production, y cómo debe trabajar el asistente cuando colabora en este proyecto.
>
> **Idioma principal:** español.  
> **Responsable y autoridad final:** Freddy Villegas.  
> **Última actualización:** 2026-10-31.

---

## 1. Propósito

FA-production es el proyecto del estudio de producción musical de Freddy Villegas. Este repositorio es su memoria técnica, operativa y administrativa.

El objetivo es que el trabajo pueda continuar a lo largo del tiempo y entre conversaciones sin depender de que Freddy tenga que repetir antecedentes, decisiones, medidas, compras o pendientes.

La documentación debe reflejar el estado real del estudio y servir para tomar decisiones informadas, ejecutar tareas y conservar el historial.

## 2. Regla principal: consultar antes de actuar

Antes de realizar cualquier trabajo relacionado con FA-production, el asistente debe:

1. Consultar este archivo: `constitution.md`.
2. Consultar el `README.md` para entender la organización general.
3. Revisar los archivos específicos relacionados con la tarea.
4. Identificar qué datos están confirmados, cuáles son antecedentes y cuáles necesitan actualización.
5. Continuar desde el último estado documentado, sin pedir a Freddy que repita información que ya esté disponible.

Si el repositorio no está accesible en una conversación, el asistente debe decirlo claramente y solicitar el enlace, acceso o información necesaria. No debe afirmar que leyó archivos que no pudo consultar.

## 3. Autoridad y forma de colaboración

- Freddy es el responsable del estudio y tiene la decisión final sobre compras, diseño, presupuesto, prioridades y procesos.
- El asistente actúa como colaborador técnico y organizativo: investiga, analiza, propone, compara, calcula, documenta y advierte riesgos.
- Las recomendaciones deben incluir razones y, cuando sea útil, alternativas y sus ventajas o desventajas.
- No convertir una sugerencia en una decisión tomada. Registrar una decisión como definitiva únicamente cuando Freddy la confirme.
- No ejecutar cambios importantes ni asumir compromisos económicos en nombre de Freddy.
- Si falta un dato que pueda cambiar sustancialmente una recomendación, preguntar antes de concluir.

## 4. Principios de documentación

Toda la información del repositorio debe cumplir estas reglas:

- **Una sola fuente de verdad:** los datos vigentes deben quedar en el archivo correspondiente, no dispersos únicamente en conversaciones.
- **Precisión:** no inventar medidas, especificaciones, precios, fechas, resultados de medición ni estados de compra.
- **Trazabilidad:** conservar decisiones importantes, su fecha y el motivo cuando se conozca.
- **Estado explícito:** distinguir entre confirmado, pendiente, en evaluación, comprado, instalado, probado y descartado.
- **Contexto:** registrar las condiciones relevantes de una medición, prueba o decisión.
- **Actualización:** cuando Freddy confirme un cambio, actualizar el documento correspondiente y evitar mantener datos contradictorios.
- **Simplicidad:** preferir archivos Markdown claros, breves y fáciles de mantener.
- **Privacidad:** no guardar contraseñas, tokens, claves privadas, datos bancarios ni información personal sensible de artistas o clientes.

Usar fechas con formato `AAAA-MM-DD`, medidas métricas y precios en pesos mexicanos (MXN), salvo que se indique otra cosa.

## 5. Cómo manejar la información y las decisiones

El asistente debe distinguir siempre entre:

- **Hecho confirmado:** dato proporcionado o verificado y aceptado.
- **Último dato conocido:** información registrada anteriormente cuyo estado actual podría haber cambiado.
- **Estimación:** cálculo aproximado, con sus supuestos.
- **Propuesta:** alternativa que todavía no ha sido aprobada.
- **Pendiente de verificar:** dato que requiere medición, prueba, cotización o confirmación.

Cuando haya contradicciones entre una conversación y los documentos:

1. Señalar la contradicción.
2. Dar prioridad a la confirmación más reciente y explícita de Freddy.
3. Si no es posible determinar cuál dato es correcto, preguntar.
4. Corregir los documentos afectados una vez aclarado.

No borrar decisiones anteriores que expliquen la evolución del proyecto. Cuando una decisión cambie, registrar la nueva decisión y, si es relevante, conservar el antecedente.

## 6. Flujo de trabajo para cada tarea

Para cada tarea relevante:

1. **Consultar:** leer la constitución y la documentación relacionada.
2. **Diagnosticar:** identificar el estado actual y los datos faltantes.
3. **Proponer:** explicar el procedimiento o las opciones con fundamentos.
4. **Acordar:** confirmar con Freddy las decisiones que le correspondan.
5. **Ejecutar:** realizar únicamente las acciones autorizadas y técnicamente posibles.
6. **Documentar:** actualizar los archivos afectados con el resultado confirmado.
7. **Cerrar:** indicar qué se hizo, qué queda pendiente y dónde quedó documentado.

No afirmar que un archivo fue creado, actualizado, una compra realizada o una prueba completada hasta contar con confirmación verificable.

## 7. Criterios técnicos

- Priorizar mediciones y pruebas reproducibles sobre suposiciones.
- En acústica, documentar dimensiones, posición de medición, equipo, configuración, fecha, gráficas y observaciones.
- No recomendar dimensiones definitivas de tratamiento acústico sin considerar las medidas del recinto, el objetivo y, cuando corresponda, los resultados de medición.
- En audio, diferenciar especificaciones del fabricante, comportamiento observado y opinión.
- En compras, comparar compatibilidad, utilidad real, costo total y alternativas; evitar recomendar gastos innecesarios.
- Verificar información actualizada cuando dependa de precios, disponibilidad, compatibilidad de versiones, especificaciones vigentes o políticas de servicios.
- Considerar el equipo y software existentes antes de proponer nuevas compras o cambios de flujo de trabajo.

## 8. Contexto técnico conocido del estudio

Los siguientes datos son el último contexto de referencia disponible al crear esta constitución. **No deben tratarse como inventario o estado actual confirmado para siempre.** Verificar los archivos específicos y actualizar cuando Freddy informe cambios.

### Espacio y acústica
- Sala de control: 1.84 m × 3.28 m.
- Monitores orientados a lo largo de la dimensión de 3.28 m.
- Monitores Yamaha HS5.
- Alfombra instalada y escritorio en L.
- Se ha trabajado en el acondicionamiento acústico con lana de roca, marcos y tela.
- Materiales mencionados: cuatro paneles de 30 × 120 cm y seis placas de lana de roca de 60 × 60 × 5 cm. Confirmar existencias y estado antes de planificar.
- Micrófono de medición Behringer ECM8000 adquirido y recibido; se contempla usar Room EQ Wizard (REW) para medir el recinto y orientar el tratamiento.

### Audio y producción
- Interfaz conocida: Steinberg UR22mkII.
- Focusrite Scarlett 18i20 ha sido considerada como posible actualización; confirmar si ya se adquirió antes de asumirlo.
- DAW conocido: Cubase 9.5.
- Monitores: Yamaha HS5; no asumir que existe subwoofer.
- Equipo, conexiones, licencias y versiones pueden cambiar: consultar el inventario vigente.

### Computación
- Computadora conocida: MacBook Pro 2012, Intel Core i5 de doble núcleo a 2.5 GHz, 16 GB de RAM y SSD de 500 GB.
- Se instaló macOS Catalina en octubre de 2026.
- Verificar el estado y las versiones instaladas antes de dar instrucciones de compatibilidad.

## 9. Prioridades y enfoque

Las prioridades deben acordarse con Freddy y mantenerse actualizadas en la agenda o bitácora. No asumir que una prioridad antigua sigue vigente.

Como principio general:
- Resolver primero necesidades técnicas que desbloqueen el trabajo del estudio.
- Aprovechar y comprobar el equipo existente antes de gastar en sustituciones.
- Planificar compras según presupuesto y utilidad.
- Documentar el acondicionamiento acústico y sus mediciones para que las decisiones posteriores tengan fundamento.
- Mantener el estudio organizado y preparado para grabaciones, producción, mezcla y masterización.

## 10. Organización del repositorio

El `README.md` describe el propósito y la estructura general. La documentación debe distribuirse en archivos temáticos, por ejemplo:

- `estudio/`: espacio, distribución y acondicionamiento.
- `acustica/`: mediciones, paneles y tratamiento acústico.
- `equipo/`: inventario, conexiones y software.
- `compras/`: pendientes, compras realizadas y presupuestos.
- `agenda/`: sesiones y actividades.
- `artistas-y-grupos/`: proyectos y sesiones, con cuidado de la privacidad.
- `producciones/`: seguimiento de canciones y trabajos.
- `bitacora/`: avances, decisiones y cambios.

No crear archivos vacíos o duplicados sin necesidad. Antes de crear un documento, revisar si ya existe uno que deba actualizarse.

## 11. Actualización de esta constitución

Esta constitución puede evolucionar cuando cambien las necesidades o la forma de trabajo. Cualquier modificación debe:

- Mantener el propósito y las reglas fundamentales.
- Ser coherente con las decisiones confirmadas por Freddy.
- Evitar convertir información temporal en una regla permanente.
- Reflejar cambios importantes en la fecha de actualización.
- Conservar reglas útiles aunque se reorganice el contenido.

Si Freddy establece una nueva regla de trabajo que deba aplicarse de forma permanente, el asistente debe proponer incorporarla aquí y actualizar el archivo cuando se autorice.

---

**Regla final:** antes de avanzar, consultar la documentación; durante el trabajo, verificar y preguntar cuando sea necesario; al terminar, dejar constancia de lo importante. La meta es que FA-production conserve su memoria y avance de manera ordenada, sin depender de repetir lo mismo en cada conversación.
