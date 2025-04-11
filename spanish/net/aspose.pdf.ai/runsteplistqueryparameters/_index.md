---
title: Class RunStepListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.RunStepListQueryParameters. Objeto de parámetros de consulta para listar pasos de ejecución
type: docs
weight: 1040
url: /es/net/aspose.pdf.ai/runsteplistqueryparameters/
---
## Clase RunStepListQueryParameters

Objeto de parámetros de consulta para listar pasos de ejecución.

```csharp
public class RunStepListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RunStepListQueryParameters](runsteplistqueryparameters/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Obtiene o establece un cursor para usar en la paginación. after es un ID de objeto que define tu lugar en la lista. Por ejemplo, si haces una solicitud de lista y recibes 100 objetos, terminando con obj_foo, tu llamada subsiguiente puede incluir after=obj_foo para obtener la siguiente página de la lista. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Obtiene o establece un cursor para usar en la paginación. before es un ID de objeto que define tu lugar en la lista. Por ejemplo, si haces una solicitud de lista y recibes 100 objetos, terminando con obj_foo, tu llamada subsiguiente puede incluir before=obj_foo para obtener la página anterior de la lista. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Obtiene o establece un límite en el número de objetos a devolver. Limit puede variar entre 1 y 100, y el valor predeterminado es 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Obtiene o establece el orden de clasificación por la marca de tiempo created_at de los objetos. asc para orden ascendente y desc para orden descendente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/runsteplistqueryparameters/getqueryparameters/)() | Obtiene los parámetros de consulta para listar pasos de ejecución. |

### Ver También

* clase [BaseListQueryParameters](../baselistqueryparameters/)
* interfaz [IQueryParameters](../iqueryparameters/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../)