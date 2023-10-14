
## Segmentos:
### Compras:
Para el diseño de registro de compras:
Entendido. Haré el ajuste en la columna de "Longitud" para el campo 4 y corregiré el "Segmento del Texto" correspondiente. A continuación, la tabla actualizada:

| Número de Campo | Nombre del Campo                                                      | Ejemplo de Valor          | Longitud | Segmento del Texto                     |
|-----------------|-----------------------------------------------------------------------|---------------------------|----------|----------------------------------------|
| 1               | Fecha de comprobante o fecha de oficialización                        | 20200731                  | 8        | 20200731                               |
| 2               | Tipo de Comprobante                                                   | 001                       | 3        | 001                                    |
| 3               | Punto de Venta                                                        | 00007                     | 5        | 00007                                  |
| 4               | Número de Comprobante                                                 | 00000000000000011123     | 20       | 00000000000000011123                   |
| 5               | Despacho de importación                                               | 0000000000000000                | 16       |                                    |
| 6               | Código de documento del vendedor                                      | 80                        | 2        | 80                                     |
| 7               | Número de identificación del vendedor                                 | 00000000030708948571               | 20       | 00000000030708948571                            |
| 8               | Apellido y nombre o denominación del vendedor                         | 000000000000000000000000000000  | 30       | GNC DE LA COSTA S.R.L.                 |
| 9               | Importe total de la operación                                         | 000000000000000           | 15       | 000000000137545                        |
| 10              | Importe total de conceptos que no integran el precio neto gravado     | 000000000000000           | 15       | 000000000000000                        |
| 11              | Importe de operaciones exentas                                        | 000000000000000           | 15       | 000000000000000                        |
| 12              | Importe de percepciones o pagos a cuenta del Impuesto al Valor Agregado| 000000000000000           | 15       | 000000000000000                        |
| 13              | Importe de percepciones o pagos a cuenta de otros impuestos nacionales | 000000000000000           | 15       | 000000000000000                        |
| 14              | Importe de percepciones de Ingresos Brutos                            | 000000000000000           | 15       | 000000000000000                        |
| 15              | Importe de percepciones impuestos municipales                         | 000000000000000           | 15       | 000000000000000                        |
| 16              | Importe de Impuestos Internos                                         | 000000000000000           | 15       | 000000000000000                        |
| 17              | Código de Moneda                                                      | PES                       | 3        | PES                                    |
| 18              | Tipo de cambio                                                        | 0001000000                | 10       | 0001000000                             |
| 19              | Cantidad alícuotas IVA                                                | 1                        | 1        | 1                                     |
| 20              | Código de Operación                                                   | 1                         | 1        | 1                                      |
| 21              | Crédito Fiscal Computable                                             | 000000000000000           | 15       | 000000000018117                        |
| 22              | Otros Tributos                                                        | 000000000000000           | 15       | 000000000000000                        |
| 23              | CUIT Emisor / Corredor                                                | 00000000000               | 11       | 00000000000                            |
| 24              | Denominación Emisor / Corredor                                        | 000000000000000000000000000000  | 30       |                                        |
| 25              | IVA Comisión                                                          | 000000000000000           | 15       | 000000000000000                        |


He corregido la longitud y el segmento del texto para el campo 4 según lo solicitado. Si hay algún otro ajuste, no dudes en decírmelo.   
### Alícuotas:
Para el diseño de registro de alícuotas de compras:

| Campo                       | Valor                 | Caracteres |
|-----------------------------|-----------------------|------------|
| Tipo de comprobante         | 001                   | 3          |
| Punto de venta              | 00007                 | 5          |
| Número de comprobante       | 0000000000000111238   | 20         |
| Codigo de Documento del Vendedor| 80  | 2         |
| Numero de indentificacion del Vendedor| 00000000000000000000  | 20         |
| Importe neto gravado        | 00000000003070894857  | 20         |
| Alícuota de IVA             | 10                    | 2          |
| Impuesto Liquidado          | 0000000000086272      | 15         |
