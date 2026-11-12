# Inventario valorizado y cobertura

**Dato al 12/11/2026** · semana ISO en curso **46** (parcial, incompleta) · última semana cerrada con servicio medido: **45**  
*Generado automáticamente el 12/11/2026 12:22 — no editar a mano.*

Universo ampliado: **incluye PPA y stock bloqueado**, a diferencia del resto del DA.

> Datos del Dashboard de Abastecimiento (DA). Montos en pesos chilenos. Las definiciones y reglas de cada indicador están en la base de conocimiento del Asistente DA, no en este archivo.

## Inventario por categoría

| Categoría | SKU | Valor | % del total |
|---|---|---|---|
| MP HARINAS | 20 | $89,8 MM | 1,6% |
| MATERIAS PRIMAS (ZMPR) | 330 | $1.868,3 MM | 34,2% |
| EMPAQUES (ZEMP) | 359 | $659,5 MM | 12,1% |
| MMPP PPA | 89 | $528,3 MM | 9,7% |
| MERCADERÍA TERCEROS | 73 | $428,9 MM | 7,9% |
| INSUMOS | 270 | $215,1 MM | 3,9% |
| UNIFORMES | 518 | $136,4 MM | 2,5% |
| REPUESTOS | 3.893 | $1.046,0 MM | 19,2% |
| PT IMPORTADO | 7 | $483,3 MM | 8,9% |

- **Total G. Planificación: $4.273,4 MM · 1.148 SKU · 78,3% del total** — todas las categorías menos Uniformes y Repuestos. Es el perímetro del área.
- **TOTAL: $5.455,8 MM** (las 9 categorías).
- Fuera de esta tabla queda el producto terminado de producción propia y los semielaborados: suma lo *abastecido*, no el inventario total de planta.

## Evolución de las últimas 14 semanas

| Semana | Fecha | Inventario total | G. Planificación |
|---|---|---|---|
| 2026W34 | 20/08/2026 | $5.866,5 MM | $4.772,7 MM |
| 2026W35 | 28/08/2026 | $5.808,2 MM | $4.709,0 MM |
| 2026W36 | 04/09/2026 | $6.078,4 MM | $4.968,0 MM |
| 2026W37 | 11/09/2026 | $5.998,3 MM | $4.885,9 MM |
| 2026W38 | 17/09/2026 | $6.161,7 MM | $5.038,7 MM |
| 2026W39 | 25/09/2026 | $5.981,0 MM | $4.851,9 MM |
| 2026W40 | 02/10/2026 | $6.111,9 MM | $5.001,7 MM |
| 2026W41 | 08/10/2026 | $6.122,1 MM | $4.997,2 MM |
| 2026W42 | 16/10/2026 | $5.972,3 MM | $4.810,6 MM |
| 2026W43 | 23/10/2026 | $6.137,2 MM | $4.972,7 MM |
| 2026W44 | 30/10/2026 | $5.971,6 MM | $4.795,0 MM |
| 2026W45 | 05/11/2026 | $5.697,7 MM | $4.515,5 MM |
| 2026W46 | 09/11/2026 | $5.513,3 MM | $4.332,5 MM |
| 2026W47 | 12/11/2026 | $5.455,8 MM | $4.273,4 MM |

La etiqueta de semana de esta serie la pone el DA (hoy «W47»); la fecha de cada fila es la que manda. Ver la nota del índice.

## Cobertura por categoría (mediana del SKU)

| Categoría | Cobertura mediana | p25 | p75 | Promedio | Zona objetivo | SKU medidos |
|---|---|---|---|---|---|---|
| MP HARINAS | 2,6 sem | 1,0 | 4,0 | 4,1 | 1 a 3 sem | 9 |
| MATERIAS PRIMAS (ZMPR) | 4,5 sem | 2,5 | 8,0 | 8,3 | 2 a 8 sem | 294 |
| EMPAQUES (ZEMP) | 6,9 sem | 3,9 | 11,7 | 14,4 | 3 a 8 sem | 234 |
| MMPP PPA | 15,5 sem | 9,5 | 38,2 | 41,2 | estacional, sin rango | 47 |
| MERCADERÍA TERCEROS | 5,9 sem | 3,1 | 13,1 | 22,3 | 3 a 15 sem | 52 |
| INSUMOS | 6,9 sem | 2,8 | 17,3 | 18,8 | 3 a 8 sem | 55 |
| UNIFORMES | — | — | — | — | sin consumo medible | 0 |
| REPUESTOS | — | — | — | — | sin consumo medible | 0 |
| PT IMPORTADO | 11,5 sem | 10,1 | 21,0 | 15,1 | 5 a 15 sem | 7 |

Se usa **mediana, no promedio**: unos pocos SKU parados con cientos de semanas de cobertura secuestran el promedio. La distancia p25–p75 dice qué tan dispar es la categoría. La zona objetivo la fijó el negocio a criterio, no está derivada de lead time + stock de seguridad.

## Distribución del capital por tramo de cobertura

Cobertura = stock disponible (sin OC en tránsito) ÷ forecast promedio de las próximas 12 semanas. Sin PPA.

### ZMPR Nacional

| Tramo | SKU | Stock valorizado | % del capital |
|---|---|---|---|
| < 2 sem | 71 | $105,4 MM | 5,4% |
| 2 a 5 sem | 107 | $506,8 MM | 26,1% |
| 5 a 10 sem | 80 | $652,1 MM | 33,6% |
| 10 a 20 sem | 37 | $598,7 MM | 30,9% |
| 20 a 50 sem | 12 | $31,5 MM | 1,6% |
| 50 a 100 sem | 3 | $1,1 MM | 0,1% |
| Sobre 100 sem | 5 | $14,4 MM | 0,7% |
| Sin Plan c/Consumo | 8 | $21,7 MM | 1,1% |
| Sin Plan | 16 | $8,1 MM | 0,4% |

Metas: sub-cobertura (<10 sem) 80% · normal/alta 10% · Sin Plan 10%

### ZEMP Nacional

| Tramo | SKU | Stock valorizado | % del capital |
|---|---|---|---|
| < 2 sem | 25 | $13,4 MM | 2,1% |
| 2 a 5 sem | 66 | $96,6 MM | 15,1% |
| 5 a 10 sem | 75 | $199,1 MM | 31,1% |
| 10 a 20 sem | 42 | $77,7 MM | 12,1% |
| 20 a 50 sem | 23 | $50,1 MM | 7,8% |
| 50 a 100 sem | 5 | $16,1 MM | 2,5% |
| Sobre 100 sem | 4 | $21,7 MM | 3,4% |
| Sin Plan c/Consumo | 35 | $71,2 MM | 11,1% |
| Sin Plan | 82 | $94,1 MM | 14,7% |

Metas: sub-cobertura (<10 sem) 80% · normal/alta 10% · Sin Plan 10%

### Importados (cartera HECTOR)

Sin SKU en esta corrida — no es que no haya capital en el grupo: es que ningún SKU del universo de compra quedó clasificado acá.
