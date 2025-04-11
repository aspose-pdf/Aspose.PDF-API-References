---
title: Class VectorStoreFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.VectorStoreFileListQueryParameters. Objeto de parámetros de consulta para listar archivos de la tienda de vectores
type: docs
weight: 1330
url: /es/net/aspose.pdf.ai/vectorstorefilelistqueryparameters/
---
## Clase VectorStoreFileListQueryParameters

Objeto de parámetros de consulta para listar archivos de la tienda de vectores.

```csharp
public class VectorStoreFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VectorStoreFileListQueryParameters](vectorstorefilelistqueryparameters/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Obtiene o establece un cursor para su uso en la paginación. after es un ID de objeto que define tu lugar en la lista. Por ejemplo, si haces una solicitud de lista y recibes 100 objetos, terminando con obj_foo, tu llamada subsiguiente puede incluir after=obj_foo para obtener la siguiente página de la lista. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Obtiene o establece un cursor para su uso en la paginación. before es un ID de objeto que define tu lugar en la lista. Por ejemplo, si haces una solicitud de lista y recibes 100 objetos, terminando con obj_foo, tu llamada subsiguiente puede incluir before=obj_foo para obtener la página anterior de la lista. |
| [Filter](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/filter/) { get; set; } | Obtiene o establece un filtro por estado de archivo. Uno de in_progress, completed, failed, cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Obtiene o establece un límite en el número de objetos a devolver. Limit puede variar entre 1 y 100, y el valor predeterminado es 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Obtiene o establece el orden de clasificación por la marca de tiempo created_at de los objetos. asc para orden ascendente y desc para orden descendente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/getqueryparameters/)() | Obtiene los parámetros de consulta para listar archivos de la tienda de vectores. |

### Ver También

* clase [BaseListQueryParameters](../baselistqueryparameters/)
* interfaz [IQueryParameters](../iqueryparameters/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../)