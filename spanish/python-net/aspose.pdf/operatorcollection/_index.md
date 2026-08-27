---
title: "OperatorCollection"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "La clase representa una colección de operadores"
type: docs
weight: 1010
url: /es/python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

La clase representa una colección de operadores

El tipo OperatorCollection expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| is_fast_text_extraction_mode | Indica si la colección está limitada a la extracción rápida de texto |
## Indexer
| Nombre | Descripción |
| :- | :- |
| [index] | Obtiene el operador por su índice. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| insert(index, op) | Inserta un operador en la colección. |
| insert(at, ops) | Inserta operadores en la posición dada. |
| insert(at, ops) | Inserta un operador en la colección. |
| delete(index) | Elimina un operador de la colección. |
| delete(ops) | Elimina operadores de la colección. |
| delete(list) | Ninguno |
| add(ops) | Añade operadores al final de los operadores de contenido. |
| add(ops) | Añade un nuevo operador a la colección. |
| suppress_update() | Suprime la actualización de los datos de contenido.<br/>            El flujo de contenido no se actualiza hasta que se llama a ResumeUpdate. |
| resume_update() | Reanuda la actualización del documento.<br/>            Actualiza el flujo de contenido en caso de que haya cambios pendientes. |
| cancel_update() | Cancela la última actualización.<br/>            Este método puede llamarse cuando el cambio no debe generar una actualización de contenido. |
| accept(visitor) | Acepta un objeto visitante IOperatorSelector para procesar operadores. |
| replace(operators) | Reemplazar operadores en la colección con otros operadores. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

