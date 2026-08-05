---
title: "SetDash"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa el operador d (establece el patrón de guiones de línea)."
type: docs
weight: 580
url: /es/python-net/aspose.pdf.operators/setdash/
---

## SetDash class

Clase que representa el operador d (establece el patrón de guiones de línea).

El tipo SetDash expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| SetDash(pattern, phase) | Inicializa una nueva instancia de la clase SetDash |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| index | Índice del operador en la lista de operadores de la página. |
| pattern | Patrón de guiones. Los elementos del array deben ser números que especifican las longitudes de guiones y espacios alternados.<br/>            En caso de un array de un solo elemento, las longitudes de guión y espacio son iguales. |
| phase | Fase de guiones. Antes de comenzar a trazar una ruta, se debe recorrer el array de guiones, sumando las longitudes de guiones y espacios. <br/>            Cuando la longitud acumulada sea igual al valor especificado por la fase de guiones, comenzará el trazado de la ruta, <br/>            y el array de guiones se usará cíclicamente a partir de ese punto. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| accept(visitor) | Acepta un objeto visitante para procesar el operador. |
| is_text_show_operator(op) | Determina si el operador es el operador responsable de la salida de texto (Tj, TJ, etc) |

### Ver también

* namespace [aspose.pdf.operators](/pdf/python-net/aspose.pdf.operators/)
* assembly [Aspose.PDF](/pdf/python-net/)

