# Base macroeconómica histórica de Colombia, 1905–2022

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)
[![Licencia: CC BY 4.0](https://img.shields.io/badge/Licencia-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/deed.es)

Series históricas de inflación, agregados monetarios, base monetaria, reservas internacionales, PIB, gasto público y sector externo de Colombia, compiladas y armonizadas para el libro **_Ensayos de historia económica. Cien años del Banco de la República_** (Banco de la República, 2023).

**Compilación y construcción:** Luis Eduardo Castellanos Rodríguez, asistente de investigación del libro.

---

## Contexto

El Banco de la República publicó en noviembre de 2023, con motivo de su centenario, el libro _Ensayos de historia económica. Cien años del Banco de la República_ ([DOI: 10.32468/Ebook.664-473-0](https://doi.org/10.32468/Ebook.664-473-0)). Esta base reúne los datos que construí como asistente de investigación de Antonio Hernández Gamarra, Carlos Caballero Argáez y María del Pilar Esguerra Umaña para dos de sus capítulos:

| Capítulo | Título | Páginas |
|---|---|---|
| 2 | Cien años de regímenes cambiarios en Colombia: 1923–2023 | 53–214 |
| 4 | Cien años de inflación en Colombia: evolución y control | 253–412 |

"CAI", en el nombre del archivo, viene de **C**ien **A**ños de **I**nflación. La base incluye las series del ejercicio econométrico del capítulo 4 sobre la relación entre inflación y exceso de medios de pago.

La recopilación implicó digitalizar series de las _Revistas del Banco de la República_ y de publicaciones históricas, empalmar series con distintos años base, unificar unidades y calcular indicadores derivados (deflactores, índices, descomposiciones de la base monetaria, estadísticas por periodo). Esta versión la pone a disposición de cualquier persona interesada en la historia económica y monetaria de Colombia.

## Archivo

```
data/base_cai_libro_100_anos.xlsx
```

Un libro de Excel con 29 hojas (27 visibles y 2 ocultas). La mayoría de las celdas contienen valores, no fórmulas.

## Periodización

Las estadísticas resumen usan los cinco grandes periodos del capítulo 4:

| Periodo | Caracterización |
|---|---|
| 1923–1928 | Patrón oro e inflación alta |
| 1929–1935 | Caída del nivel de precios y abandono del patrón oro |
| 1936–1972 | Inflación moderada y cambio institucional |
| 1973–1999 | Inflación alta y manejo monetario expansivo |
| 2000–2022 | Inflación baja y estabilidad |

Varias hojas reportan además promedios quinquenales y subperiodos.

## Contenido

### Precios e inflación

| Hoja | Contenido | Cobertura | Frecuencia |
|---|---|---|---|
| `IPC` | Inflación del IPC, índice (base 2004), tasa de cambio nominal y devaluación; medias aritméticas y geométricas, desviación estándar, cuartiles, máximos y mínimos por periodo | 1905–2022 | Anual |
| `Deflactor` | PIB nominal y real encadenado, deflactor implícito e inflación medida con el deflactor | 1905–2022 | Anual |
| `IPC vs Deflactor` | Comparación entre ambas medidas de inflación y su correlación | 1923–2022 | Anual |
| `IPC vs TPM` | Inflación anual, tasa de política monetaria (TPM) y tasa interbancaria (TIB) | 1999–2022 | Mensual |
| `SMLV y UPAC` | Salario mínimo urbano y UPAC en términos reales | 1970–2022 | Anual |

### Dinero y base monetaria

| Hoja | Contenido | Cobertura | Frecuencia |
|---|---|---|---|
| `Medios de pago anual` | M1, M2, M3 y su relación con el PIB | 1923–2021 | Anual (diciembre) |
| `M trimestral` | M1, M2, M3, crecimientos anuales, razones entre agregados e índices (base dic. 1950) | 1923–2021 | Trimestral |
| `Crecimiento M1`, `Crecimiento M2`, `Crecimiento M3` | Tasas de crecimiento y estadísticas por periodo | 1923–2021/22 | Anual y trimestral |
| `M1 relativo M2` | M1/M2 como indicador de profundización financiera | 1923–2021 | Anual |
| `Componentes B y M` | Base monetaria, reservas internacionales, efectivo, reserva bancaria, velocidad de M1, multiplicador (_m_, _e_, _r_), descomposición del crecimiento de M1 e impuesto inflación | 1905–2022 | Anual |
| `IEMP prom anual`, `IEMP dic` | Índice de exceso de medios de pago (IEMP) y exceso de crecimiento de los medios de pago (ECMP), medidos con M1 y M2; series en niveles y logaritmos | 1923–2021 | Anual |

### Origen de la base monetaria y reservas

| Hoja | Contenido | Cobertura | Frecuencia |
|---|---|---|---|
| `Origen contable B` | Variación de la base descompuesta en reservas internacionales y crédito interno | 1928–2000 | Anual |
| `Origen B_ampliado` | Origen ampliado de la base: balanza de pagos ajustada, financiación monetaria del déficit fiscal y crédito interno al sector privado | 1936–2022 | Anual |
| `CIB y sus componentes` | Crédito interno del Banco de la República por sector | 1936–1972 | Anual |
| `RI y sus compentes` | Variación de reservas internacionales y sus componentes, en dólares y pesos | 1936–2022 | Anual |

### Actividad, gasto y sector externo

| Hoja | Contenido | Cobertura | Frecuencia |
|---|---|---|---|
| `PIB` | PIB nominal, crecimiento real (empalme de bases 1950, 1980 y 2000), índices de Ocampo y GRECO | 1905–2022 | Anual |
| `Estructura del PIB` | Consumo de gobierno y hogares, exportaciones e importaciones: niveles, crecimiento, participación y contribución al crecimiento | 1925–2021 | Anual |
| `Gasto del gobierno` | Gasto de funcionamiento, inversión y total del Gobierno Nacional; como porcentaje del PIB y en términos reales | 1924–2022 | Anual |
| `Balanza Cambiaria` | Exportaciones, importaciones y balanza comercial en dólares y pesos | 1905–2022 | Anual |
| `Exportaciones_componentes` | Exportaciones totales, de café y de hidrocarburos; precio del petróleo | 1970–2022 | Anual |
| `Precios café` | Precio del café en Nueva York y reservas internacionales brutas | 1905–2000 | Anual |
| `Cartera del sist. Bancario` | Cartera del sistema bancario | 1923–1968 | Anual |

### Hojas auxiliares

| Hoja | Contenido |
|---|---|
| `Resumen` | Estadísticas por gran periodo de inflación (IPC y deflactor), crecimiento del PIB, crecimiento de M1, gasto público y M1/M2 |
| `Gráficas por CAP y colores` | Guía de colores y formato de las gráficas del libro. No contiene datos |
| `Gráficas` (oculta) | Gráficas y correlaciones de trabajo |
| `Gasto del gobierno-PIB_V2` (oculta) | Versión alternativa del gasto público como porcentaje del PIB |

## Abreviaturas

| Sigla | Significado |
|---|---|
| B | Base monetaria |
| M1, M2, M3 | Medios de pago y agregados monetarios amplios |
| RI, RIN | Reservas internacionales (netas) |
| BPA | Balanza de pagos ajustada |
| X − M | Balanza comercial |
| ΔEEPr, ΔEEPu | Variación del endeudamiento externo privado y público |
| FMDF | Financiación monetaria del déficit fiscal |
| CIB | Crédito interno del Banco de la República |
| CIBPu, CIBPr | Crédito interno del Banco al sector público y al sector privado |
| IEMP | Índice de exceso de medios de pago |
| ECMP | Exceso de crecimiento de los medios de pago |
| II, IIPu, IIPr | Impuesto inflación (total, sector público, sector privado) |
| _e_, _r_, _m_ | Razón efectivo/depósitos, razón reservas/depósitos y multiplicador monetario |
| TPM, TIB | Tasa de política monetaria y tasa interbancaria |
| SMLV | Salario mínimo legal vigente |
| UPAC | Unidad de poder adquisitivo constante |

## Fuentes principales

- Banco de la República: _Revista del Banco de la República_ (varios números), _Principales indicadores económicos 1923–1997_, la revista conmemorativa de los 75 años del Banco y series estadísticas en línea (consultadas en 2022).
- GRECO (Grupo de Estudios del Crecimiento Económico Colombiano), Banco de la República (1999): empalmes de base monetaria, M1, IPC, tasa de cambio y PIB.
- Ocampo, J. A. y Romero, C. A. (2023), _Desarrollo económico y social colombiano 1905–2019_, Banco de la República.
- DANE: cuentas nacionales (bases 2005 y 2015), IPC y comercio exterior (con la DIAN).
- CEPAL y ONU (revisiones 2 y 3), para las cuentas nacionales de 1923–1996.
- Ministerio de Hacienda y Crédito Público, para el gasto del Gobierno Nacional desde 2001.
- Ministerio de la Protección Social (2008), para el salario mínimo.
- López (1990), McGreevey (1965) y Beyer (1947), para la tasa de cambio y el precio del café antes de 1923.
- Banco Mundial, para el precio del petróleo.

Cada hoja indica al pie la fuente específica y las notas metodológicas de sus series.

## Advertencias

- **Empalmes.** Las series largas combinan fuentes con distintos años base y metodologías. Las notas de cada hoja explican cómo se empalmaron.
- **Datos preliminares.** Los valores de 2022 marcados con `*` eran preliminares en 2022, cuando se construyó la base. No se han actualizado.
- **Formato de trabajo.** Algunas hojas contienen tablas dinámicas, columnas auxiliares y varias tablas en paralelo. Conviene leer los encabezados antes de importar los datos de forma automática.
- **Errores conocidos.** La hoja `Balanza Cambiaria` tiene celdas `#REF!` en la columna A y `Componentes B y M` tiene dos celdas con error. Ninguna afecta las series principales.

Si encuentras un error, abre un [issue](../../issues).

## Cómo citar

Si usas esta base, cita tanto la base como el libro.

**Base de datos**

> Castellanos Rodríguez, L. E. (2026). _Base macroeconómica histórica de Colombia, 1905–2022_ [Conjunto de datos]. Compilada para _Ensayos de historia económica. Cien años del Banco de la República_. https://doi.org/10.5281/zenodo.XXXXXXX

**Libro**

> Banco de la República (2023). _Ensayos de historia económica. Cien años del Banco de la República_. Bogotá: Banco de la República. https://doi.org/10.32468/Ebook.664-473-0

GitHub muestra la cita en formato APA y BibTeX en el botón **"Cite this repository"**, a partir del archivo [`CITATION.cff`](CITATION.cff).

## Licencia

La compilación se distribuye bajo [Creative Commons Atribución 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.es). Puedes usarla, modificarla y redistribuirla siempre que des el crédito correspondiente. Los datos originales conservan las condiciones de uso de sus fuentes.

## Agradecimientos

A Antonio Hernández Gamarra, Carlos Caballero Argáez y María del Pilar Esguerra Umaña, por la oportunidad de trabajar en este proyecto.

## Contacto

Luis Eduardo Castellanos Rodríguez
le.castellanos10@uniandes.edu.co
lecastero@gmail.com
[@LuisECastR](https://x.com/LuisECastR)

---

### English summary

Historical macroeconomic dataset for Colombia (1905–2022) covering inflation (CPI and GDP deflator), money aggregates (M1–M3), the monetary base and its sources, international reserves, GDP, government spending and the external sector. It was compiled by Luis Eduardo Castellanos Rodríguez as research assistant for chapters 2 (exchange rate regimes) and 4 (one hundred years of inflation) of _Ensayos de historia económica. Cien años del Banco de la República_ (Banco de la República, 2023). Data are in Spanish. Licensed under CC BY 4.0.
