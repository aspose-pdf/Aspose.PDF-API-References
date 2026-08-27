---
title: "BaseOperatorCollection"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa la clase base para la colección de operadores."
type: docs
weight: 70
url: /es/python-net/aspose.pdf/baseoperatorcollection/
---

## BaseOperatorCollection class

Representa la clase base para la colección de operadores.

El tipo BaseOperatorCollection expone los siguientes miembros:
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
| suppress_update() | Suprime la actualización de los datos de contenido.<br/>            El flujo de contenido no se actualiza hasta que se llama a ResumeUpdate. |
| resume_update() | Reanuda la actualización del documento.<br/>            Actualiza el flujo de contenido en caso de que haya cambios pendientes. |
| insert(index, op) | Inserta un operador en la colección. |
| cancel_update() | Cancela la última actualización.<br/>            Este método puede llamarse cuando el cambio no debe generar una actualización de contenido. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

