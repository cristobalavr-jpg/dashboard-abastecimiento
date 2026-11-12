# Foto de hoy — titulares del DA

**Dato al 12/11/2026** · semana ISO en curso **46** (parcial, incompleta) · última semana cerrada con servicio medido: **45**  
*Generado automáticamente el 12/11/2026 12:22 — no editar a mano.*

> Datos del Dashboard de Abastecimiento (DA). Montos en pesos chilenos. Las definiciones y reglas de cada indicador están en la base de conocimiento del Asistente DA, no en este archivo.

## 1 · Servicio a producción (semana 45 cerrada)

| Indicador | Última semana | Promedio año | Referencia histórica | Qué mide |
|---|---|---|---|---|
| NDS-1b · Disponibilidad de MP (total semana) | 99,86% | 99,85% | 99,85% | incidencia de quiebres sobre todas las líneas de MP requeridas |
| NDS-1a · Disponibilidad de MP (por SKU) | 98,4% | 98,4% | 98,4% | de los SKU de MP que producción necesitó, cuántos faltaron |
| NDS-3 · Cumplimiento de producción | 92,7% | 90,6% | 86,2% | unidades fabricadas / planificadas (todas las causas) |
| NDS-4 · Impacto de falta de MP | 0,005% | 0,100% | 0,10% | % del plan que no se produjo por falta de MP |

- Año corrido: plan **93.660.795 unidades** de PT, de las cuales **88.432 unidades** (0,09% del plan) no se produjeron con una MP en quiebre el día exacto en que se necesitaba.
- Semanas del año bajo la referencia de disponibilidad: **21** de 45.
- El detalle de **qué PT no se fabricaron y por qué MP** está en `nds4_pt_por_semana.md`.

## 2 · Inventario y capital

| Indicador | Valor | Universo y nota |
|---|---|---|
| Inventario total valorizado | $5.455,8 MM | las 9 categorías · **incluye PPA y stock bloqueado** |
| Subtotal G. Planificación | $4.273,4 MM | 1.148 SKU · 78,3% del total · incluye PPA — **es el perímetro por el que responde el área** (todo menos Uniformes y Repuestos) |
| Variación vs. 12 semanas atrás | -6,1% | -$352,4 MM |
| Días de inventario (ponderado por capital) | 37 días | DOH |
| Vueltas al año | 9,9× | rotación |
| Capital en exceso sobre el umbral de sobrestock | $205,4 MM | 122 SKU sobre su umbral · ZMPR+ZEMP sin PPA |
| Stock de rotación lenta | $1.388,3 MM | 218 SKU bajo 6 vueltas/año · ZMPR+ZEMP sin PPA |
| Stock muerto (sin consumo en 8 semanas) | $104,4 MM | 110 SKU · ZMPR+ZEMP sin PPA — se subdivide a mano en Muerto vs Descontinuado |
| Stock bloqueado (almacén BL01) | $35,1 MM | 86 SKU sin PPA (con PPA: 97 SKU · $42,5 MM) |

## 3 · Merma del año corrido

| Tipo | Merma total | Merma sin nota de crédito | % sin NC | Merma / stock actual |
|---|---|---|---|---|
| Materias primas | $48,3 MM | $39,8 MM | 82,4% | 2,04% |
| Empaques | $5,4 MM | $5,4 MM | 100,0% | 0,74% |
| Insumos | $1,7 MM | $1,7 MM | 100,0% | 0,79% |

- La **merma sin NC es la pérdida real del negocio**; la que tiene nota de crédito se recupera del proveedor.
- La columna «merma / stock actual» mezcla un flujo con una foto: sirve para dimensionar, no para comparar contra otra planta. La tasa comparable es **merma / consumo**, y está por semana en `mermas.md`.

## 4 · Quiebres (registro diario del equipo)

| Indicador | Valor |
|---|---|
| Registros informados en el año | 1.049 |
| De ellos, quiebres reales | 803 (76,5% del total) |
| Promedio semanal de quiebres reales | 17,8 |
| Últimas 4 semanas vs. 4 anteriores | 57 vs 63 registros (14,2 vs 15,8 por semana) |
| Motivo más frecuente | Reposición Diaria — 234 casos (29,1%) |
| Concentración en frescos | 82,9% de los quiebres reales son verduras y frutas frescas |

## 5 · Estado de los SKU de compra hoy (ZMPR + ZEMP, sin PPA)

| Estado | SKU | Stock valorizado |
|---|---|---|
| Quiebre (stock 0) | 24 | $0,0 MM |
| Riesgo | 40 | $19,4 MM |
| Monitorear | 49 | $173,7 MM |
| Normal | 335 | $1.470,3 MM |
| Sobrestock | 122 | $769,6 MM |
| Sin forecast | 606 | $190,1 MM |

El detalle SKU a SKU está en `alertas_sku.md`.

## 6 · Carteras de compra (quién responde por qué)

| Comprador | SKU | Stock valorizado | En quiebre | En riesgo | En sobrestock |
|---|---|---|---|---|---|
| PAMELA | 8 | $855,3 MM | 0 | 0 | 5 |
| MATIAS | 549 | $751,2 MM | 13 | 11 | 65 |
| JOSE | 227 | $470,4 MM | 8 | 7 | 35 |
| VICENTE | 117 | $403,4 MM | 1 | 1 | 10 |
| JAVIERA | 81 | $66,0 MM | 2 | 21 | 5 |
| SIN ASIGNAR | 199 | $33,1 MM | 0 | 0 | 2 |

Esta nómina sale de `SKU_por_Comprador.xlsx` tal como está hoy — no de una lista fija. **SIN ASIGNAR** son SKU sin dueño en ese archivo: nadie los está gestionando por nombre.
