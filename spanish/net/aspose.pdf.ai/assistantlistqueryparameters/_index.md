---
title: Class AssistantListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.AssistantListQueryParameters. Representa el objeto de parámetros de consulta para listar asistentes
type: docs
weight: 110
url: /es/net/aspose.pdf.ai/assistantlistqueryparameters/
---
## Clase AssistantListQueryParameters

Representa el objeto de parámetros de consulta para listar asistentes.

```csharp
public class AssistantListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AssistantListQueryParameters](assistantlistqueryparameters/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Obtiene o establece un cursor para su uso en la paginación. after es un ID de objeto que define su lugar en la lista. Por ejemplo, si realiza una solicitud de lista y recibe 100 objetos, terminando con obj_foo, su llamada subsiguiente puede incluir after=obj_foo para obtener la siguiente página de la lista. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Obtiene o establece un cursor para su uso en la paginación. before es un ID de objeto que define su lugar en la lista. Por ejemplo, si realiza una solicitud de lista y recibe 100 objetos, terminando con obj_foo, su llamada subsiguiente puede incluir before=obj_foo para obtener la página anterior de la lista. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Obtiene o establece un límite en el número de objetos que se devolverán. Limit puede variar entre 1 y 100, y el valor predeterminado es 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Obtiene o establece el orden de clasificación por la marca de tiempo created_at de los objetos. asc para orden ascendente y desc para orden descendente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/assistantlistqueryparameters/getqueryparameters/)() | Obtiene los parámetros de consulta para listar asistentes. |

### Ver También

* clase [BaseListQueryParameters](../baselistqueryparameters/)
* interfaz [IQueryParameters](../iqueryparameters/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../)