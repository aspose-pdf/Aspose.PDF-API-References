---
title: Class RunListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.RunListQueryParameters. Objeto de parámetros de consulta para listar ejecuciones
type: docs
weight: 990
url: /es/net/aspose.pdf.ai/runlistqueryparameters/
---
## Clase RunListQueryParameters

Objeto de parámetros de consulta para listar ejecuciones.

```csharp
public class RunListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RunListQueryParameters](runlistqueryparameters/)() | El constructor predeterminado. |

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
| [GetQueryParameters](../../aspose.pdf.ai/runlistqueryparameters/getqueryparameters/)() | Obtiene los parámetros de consulta para listar ejecuciones. |

### Ver También

* clase [BaseListQueryParameters](../baselistqueryparameters/)
* interfaz [IQueryParameters](../iqueryparameters/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../)