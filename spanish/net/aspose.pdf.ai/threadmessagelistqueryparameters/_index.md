---
title: Class ThreadMessageListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.ThreadMessageListQueryParameters. Objeto de parámetros de consulta para listar mensajes de hilo
type: docs
weight: 1130
url: /es/net/aspose.pdf.ai/threadmessagelistqueryparameters/
---
## Clase ThreadMessageListQueryParameters

Objeto de parámetros de consulta para listar mensajes de hilo.

```csharp
public class ThreadMessageListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ThreadMessageListQueryParameters](threadmessagelistqueryparameters/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Obtiene o establece un cursor para su uso en la paginación. after es un ID de objeto que define su lugar en la lista. Por ejemplo, si realiza una solicitud de lista y recibe 100 objetos, terminando con obj_foo, su llamada subsiguiente puede incluir after=obj_foo para obtener la siguiente página de la lista. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Obtiene o establece un cursor para su uso en la paginación. before es un ID de objeto que define su lugar en la lista. Por ejemplo, si realiza una solicitud de lista y recibe 100 objetos, terminando con obj_foo, su llamada subsiguiente puede incluir before=obj_foo para obtener la página anterior de la lista. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Obtiene o establece un límite en el número de objetos que se devolverán. Limit puede variar entre 1 y 100, y el valor predeterminado es 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Obtiene o establece el orden de clasificación por la marca de tiempo created_at de los objetos. asc para orden ascendente y desc para orden descendente. |
| [RunId](../../aspose.pdf.ai/threadmessagelistqueryparameters/runid/) { get; set; } | Filtra mensajes por el ID de ejecución que los generó. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/threadmessagelistqueryparameters/getqueryparameters/)() | Obtiene los parámetros de consulta para listar mensajes de hilo. |

### Véase también

* clase [BaseListQueryParameters](../baselistqueryparameters/)
* interfaz [IQueryParameters](../iqueryparameters/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../)