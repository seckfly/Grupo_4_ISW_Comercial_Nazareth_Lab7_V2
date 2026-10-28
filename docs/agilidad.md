# Adaptación ágil de Comercial Nazareth (V2)

La adaptación parte de la [línea base v1.1](https://github.com/seckfly/Grupo_4_ISW_Comercial_Nazareth_Lab7_V2/tree/v1.1) del [laboratorio de gestión del cambio y trazabilidad](https://github.com/seckfly/Grupo_4_ISW_Comercial_Nazareth_Lab7). Conserva los cinco requisitos, sus casos de uso y el modelo de clases.

## 1. Validez del trabajo con agilidad

Los identificadores permiten dividir una mejora y seguir sus efectos sin rehacer todos los documentos. La matriz muestra qué requisito, caso de uso, clase y prueba se relacionan. Los cambios pueden revisarse en una rama y entregarse mediante un PR.

En Comercial Nazareth, la regla de registrar un motivo en los ajustes manuales pertenece a REQ-015 y CU-006. Esa relación permite ampliar una prueba concreta conservando las reglas de ventas, catálogo y clientes. La documentación se actualiza junto con el incremento para mantener la trazabilidad.

## 2. Prácticas aplicadas

Se organiza el trabajo en seis tarjetas pequeñas, ordenadas por dependencia y prioridad. Cada una tiene criterios de aceptación y enlaces al repositorio. Los criterios se marcan después de contrastarlos con los archivos o registros correspondientes.

Se limita En curso a una tarjeta. Al revisar se comprueban el alcance, los identificadores, los enlaces y los resultados esperados. Una corrección devuelve la tarjeta a En curso. El cierre exige comprobar los criterios y conservar su evidencia.

## 3. Kanban en Trello

[Tablero Comercial Nazareth — Kanban V2](https://trello.com/b/9LEaT3KG/comercial-nazareth-kanban-v2).

| Estado | Regla de trabajo |
|---|---|
| Por hacer | Tarjetas priorizadas y con criterios de aceptación definidos. |
| En curso | Una tarjeta a la vez; la siguiente se toma cuando queda libre este estado. |
| En revisión | Contraste del cambio con sus criterios, la trazabilidad y la base v1.1. |
| Terminado | Criterios comprobados y evidencias enlazadas. |

| Prioridad | Tarjeta |
|---|---|
| 1 | [Preparar base V2 y alcance ágil](https://trello.com/c/DrED8dls) |
| 2 | [Definir prioridades y criterios de aceptación](https://trello.com/c/RfHgERQk) |
| 3 | [Aplicar Kanban y registrar el recorrido](https://trello.com/c/2DwyXuC1) |
| 4 | [Comprobar fallo al guardar un ajuste](https://trello.com/c/AfN5TOU6) |
| 5 | [Actualizar matriz y comprobar cobertura](https://trello.com/c/dH7rxo0F) |
| 6 | [Documentar y revisar la adaptación V2](https://trello.com/c/gYZf9zeq) |

## 4. Flujo real aplicado

El incremento documenta PRU-019 para el fallo de guardado de un ajuste manual de REQ-015 y CU-006. La prueba parte de stock 10, un historial previo y un motivo válido. Tras un fallo antes de confirmar la transacción, exige stock 10, conservación de los registros anteriores y ausencia de movimientos o motivos guardados parcialmente.

La [tarjeta de PRU-019](https://trello.com/c/AfN5TOU6) registra los siguientes movimientos. Fechas y horas de Lima (UTC−5), tomadas del historial de Trello:

| Fecha y hora | Movimiento |
|---|---|
| 27/10/2026 21:02:50 | Por hacer → En curso |
| 27/10/2026 21:03:20 | En curso → En revisión |
| 27/10/2026 21:03:25 | En revisión → Terminado |

Antes de trasladar la tarjeta a Terminado se contrastó el texto guardado con sus tres criterios de aceptación. El [commit de PRU-019](https://github.com/seckfly/Grupo_4_ISW_Comercial_Nazareth_Lab7_V2/commit/9db12638a8ab1ed74c3ac9144542fda12ab3ad56) contiene el escenario, y el [commit de la matriz](https://github.com/seckfly/Grupo_4_ISW_Comercial_Nazareth_Lab7_V2/commit/347a84070c39863c5a8ce8a0af36fa1f7f4f8d7e) vincula la prueba con REQ-015.

La configuración del tablero también tiene su registro en la [tarjeta de prioridades y criterios](https://trello.com/c/RfHgERQk), con sus tres comprobaciones completas. Las tarjetas conservan sus movimientos y listas de aceptación como evidencia del trabajo.

## Resultados de la adaptación

| Métrica | Base v1.1 | Adaptación V2 |
|---|---|---|
| Requisitos | 5 | 5 |
| Casos de uso | 4 | 4 |
| Clases | 6 | 6 |
| Pruebas documentadas | 8 | 9 |
| Requisitos con prueba documentada | 5 | 5 |
| Cobertura por requisitos | 100 % | 100 % |

Cobertura: (5 requisitos con prueba documentada ÷ 5 requisitos totales) × 100 = 100 %.

PRU-019 amplía los escenarios documentados de REQ-015 y conserva los identificadores de los elementos existentes. La matriz mantiene CR-001 como último cambio de ese requisito: la regla de guardado conjunto procede de la base v1.1.

El [reporte v1.1](https://github.com/seckfly/Grupo_4_ISW_Comercial_Nazareth_Lab7_V2/blob/v1.1/reportes/reporte-v1.1.md) corresponde a la línea base de ocho pruebas. Los resultados de la adaptación V2 se registran en esta tabla.
