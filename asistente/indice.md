# Datos en vivo del DA — índice

**Dato al 12/11/2026** · semana ISO en curso **46** (parcial, incompleta) · última semana cerrada con servicio medido: **45**  
*Generado automáticamente el 12/11/2026 12:26 — no editar a mano.*

Un archivo por tema; cada uno se lee solo.

> Datos del Dashboard de Abastecimiento (DA). Montos en pesos chilenos. Las definiciones y reglas de cada indicador están en la base de conocimiento del Asistente DA, no en este archivo.

| Archivo | Qué contiene | URL |
|---|---|---|
| kpis.md | Foto de hoy: servicio, inventario, cobertura, merma, capital, quiebres. **Partir siempre por acá.** | `https://castano-abastecimiento.github.io/dashboard-abastecimiento/asistente/kpis.md` |
| nds_semanal.md | NDS semana por semana (disponibilidad de MP, cumplimiento de producción, impacto de MP) y desglose por línea productiva. | `https://castano-abastecimiento.github.io/dashboard-abastecimiento/asistente/nds_semanal.md` |
| nds4_pt_por_semana.md | **Qué productos terminados no se fabricaron por falta de materia prima, semana por semana**, con las unidades y la MP que lo frenó. | `https://castano-abastecimiento.github.io/dashboard-abastecimiento/asistente/nds4_pt_por_semana.md` |
| quiebres.md | Quiebres por semana (informados vs reales), motivos, atribución por área, categorías y SKU reincidentes. | `https://castano-abastecimiento.github.io/dashboard-abastecimiento/asistente/quiebres.md` |
| mermas.md | Merma por semana con tasa sobre consumo, y los SKU que más mermaron en cada semana. | `https://castano-abastecimiento.github.io/dashboard-abastecimiento/asistente/mermas.md` |
| inventario_cobertura.md | Inventario valorizado por categoría, evolución, cobertura mediana por categoría vs zona objetivo y distribución del capital por tramo de cobertura. | `https://castano-abastecimiento.github.io/dashboard-abastecimiento/asistente/inventario_cobertura.md` |
| alertas_sku.md | SKU en quiebre y en riesgo hoy, mayor sobrestock, stock muerto y bloqueado. | `https://castano-abastecimiento.github.io/dashboard-abastecimiento/asistente/alertas_sku.md` |

Los mismos archivos quedan publicados en: `https://cristobalavr-jpg.github.io/dashboard-abastecimiento/asistente/`

## Cómo usar estos datos

1. **Cita siempre la fecha del dato** (`12/11/2026`) y la semana. Un número sin fecha no sirve para decidir.
2. **La semana en curso (46) está incompleta.** Nunca la compares contra semanas cerradas ni la uses para declarar una tendencia.
3. **Si una cifra no está en estos archivos, se mira en el DA** (`https://castano-abastecimiento.github.io/dashboard-abastecimiento/dashboard.html`) — no se estima.
4. Salvo que el archivo diga lo contrario, los **SKU de Pan de Pascua (PPA) están excluidos**, igual que en el DA por defecto. La excepción es el inventario valorizado por categoría, que siempre los incluye.
5. Los montos son **pesos chilenos**; `MM` = millones.

> **Si el encabezado del DA muestra otra semana:** el DA rotula la semana con el máximo de semana presente en los movimientos de SAP, y una fecha de contabilización adelantada lo deja por delante del calendario. Hoy el DA dice «Semana 47» y la semana ISO real del dato es la **46**. Para responderle a gerencia manda el calendario.
