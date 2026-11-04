# Orchestrator — FA-production

> **Índice y guía de navegación del conocimiento del estudio.** Este archivo no es la fuente de los datos detallados: indica dónde están, qué función cumple cada documento y cuáles deben consultarse para cada tipo de tarea.

**Responsable del proyecto:** Freddy Villegas  
**Última actualización:** 2026-11-04

## 1. Protocolo de inicio

Para cualquier tarea relacionada con FA-production:

1. Leer `constitution.md` y seguir sus reglas de colaboración.
2. Leer este `orchestrator.md`.
3. Consultar los documentos señalados para el tema.
4. Si el documento requerido todavía no existe, indicarlo. No inventar su contenido.
5. Después de una decisión confirmada o un cambio verificado, actualizar el documento que sea dueño de esa información.
6. Si se crea, elimina o cambia la función de un documento, actualizar este índice.

El repositorio de GitHub es la fuente documental de referencia. La memoria de ChatGPT y las conversaciones anteriores pueden ayudar a dar contexto, pero nunca sustituyen la consulta de los archivos vigentes del repositorio.

El `README.md` es la introducción del repositorio; no sustituye este protocolo ni los documentos de datos.

## 2. Mapa de documentos

Los siguientes documentos forman la estructura objetivo. Los marcados como **Por crear** todavía no existen y no deben tratarse como fuentes consultadas.

| Documento | Responsabilidad | Estado |
|---|---|---|
| `constitution.md` | Reglas de colaboración Freddy–ChatGPT | Disponible |
| `orchestrator.md` | Índice, navegación y protocolo documental | Disponible |
| `data/studio.md` | Espacios, medidas, distribución y acondicionamiento acústico | Por crear |
| `data/equipment.md` | Inventario de equipo, instrumentos, computadoras y software | Disponible |
| `data/clients.md` | Registro general de grupos y clientes | Por crear |
| `data/projects.md` | Producciones, canciones, grabaciones y entregas | Por crear |
| `data/purchases.md` | Compras realizadas, pendientes, cotizaciones y prioridades | Disponible |
| `data/agenda.md` | Sesiones, citas y actividades programadas | Por crear |
| `history/changelog.md` | Historial cronológico de cambios y decisiones relevantes | Por crear |

Cada grupo o cliente podrá tener, cuando sea necesario, su propio documento dentro de `data/clients/` o una carpeta dedicada. El registro general `data/clients.md` funcionará como índice de esos perfiles.

## 3. Qué consultar según la tarea

| Si la tarea trata de… | Consultar primero |
|---|---|
| Medidas, distribución, sala, paneles, trampas, acústica o REW | `data/studio.md` |
| Micrófonos, interfaces, monitores, instrumentos, computadora, DAW o plugins | `data/equipment.md` |
| Un grupo, sus integrantes, estilo o responsable | `data/clients.md` y el perfil individual si existe |
| Una canción, grabación, mezcla, masterización o entrega | `data/projects.md` y el perfil del cliente relacionado |
| Qué comprar, presupuesto, cotizaciones o compras anteriores | `data/purchases.md` y `data/equipment.md` |
| Fechas, sesiones y compromisos | `data/agenda.md` y los documentos del proyecto correspondiente |
| Qué cambió o por qué se tomó una decisión | `history/changelog.md` y el documento temático afectado |

Consultar otros documentos cuando la tarea cruce varias áreas. Por ejemplo, preparar una grabación puede requerir clientes, proyectos, equipo y agenda.

## 4. Responsabilidad única de cada documento

- `studio.md` es la fuente principal para el espacio físico y su tratamiento acústico.
- `equipment.md` es la fuente principal para el inventario y el estado del equipo.
- `clients.md` es la fuente principal para el directorio de grupos y clientes.
- `projects.md` es la fuente principal para el avance de las producciones.
- `purchases.md` es la fuente principal para el seguimiento de compras y presupuestos.
- `agenda.md` es la fuente principal para fechas y actividades.
- `changelog.md` conserva el historial; no sustituye el estado actual en los documentos temáticos.

Si un dato necesita aparecer en más de un contexto, mantenerlo en su documento dueño y enlazarlo desde los demás cuando sea práctico.

## 5. Reglas para ampliar la estructura

- Crear documentos cuando exista información real que organizar o una necesidad concreta.
- No crear archivos vacíos solo para completar el árbol de carpetas.
- Antes de crear un documento, comprobar que no exista uno equivalente.
- Preferir un documento individual por grupo cuando su historial, proyectos o sesiones lo justifiquen.
- Mantener este orquestador actualizado cada vez que cambie el mapa documental.
- No guardar información privada innecesaria de clientes. Registrar datos de contacto solo si son necesarios y autorizados.

## 6. Estado y confiabilidad de los datos

En los documentos de información, distinguir según corresponda:

- **Confirmado:** Freddy lo informó o fue verificado.
- **Por verificar:** dato antiguo o cuyo estado actual no se conoce.
- **Estimado:** valor aproximado con supuestos identificables.
- **Pendiente:** información o tarea que falta.
- **Descartado:** opción que ya no se considera vigente.

No asumir que un dato histórico sigue siendo actual. Ante contradicciones, seguir la confirmación más reciente y explícita de Freddy; si no es suficiente, preguntar.

---

**Uso del orquestador:** es el mapa para encontrar y mantener la información correcta, no un sustituto de esa información.
