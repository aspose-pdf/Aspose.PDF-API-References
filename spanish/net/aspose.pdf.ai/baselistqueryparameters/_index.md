---
title: Class BaseListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.BaseListQueryParameters. Parámetros de consulta base para listar objetos
type: docs
weight: 160
url: /es/net/aspose.pdf.ai/baselistqueryparameters/
---
## Clase BaseListQueryParameters

Parámetros de consulta base para listar objetos.

```csharp
public class BaseListQueryParameters
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BaseListQueryParameters](baselistqueryparameters/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Obtiene o establece un cursor para usar en la paginación. after es un ID de objeto que define tu lugar en la lista. Por ejemplo, si haces una solicitud de lista y recibes 100 objetos, terminando con obj_foo, tu llamada subsiguiente puede incluir after=obj_foo para obtener la siguiente página de la lista. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Obtiene o establece un cursor para usar en la paginación. before es un ID de objeto que define tu lugar en la lista. Por ejemplo, si haces una solicitud de lista y recibes 100 objetos, terminando con obj_foo, tu llamada subsiguiente puede incluir before=obj_foo para obtener la página anterior de la lista. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Obtiene o establece un límite en el número de objetos a devolver. Limit puede variar entre 1 y 100, y el valor predeterminado es 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Obtiene o establece el orden de clasificación por la marca de tiempo created_at de los objetos. asc para orden ascendente y desc para orden descendente. |

### Ver También

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)