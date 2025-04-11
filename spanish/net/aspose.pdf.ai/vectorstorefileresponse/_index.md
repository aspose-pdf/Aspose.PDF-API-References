---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.VectorStoreFileResponse. Una respuesta de archivo de tienda de vectores
type: docs
weight: 1350
url: /es/net/aspose.pdf.ai/vectorstorefileresponse/
---
## Clase VectorStoreFileResponse

Una respuesta de archivo de tienda de vectores.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se creó el archivo de la tienda de vectores. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtiene o establece el detalle de la respuesta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtiene o establece el error de respuesta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtiene o establece la información del error. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtiene o establece los encabezados de respuesta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtiene o establece el código de estado HTTP. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | Obtiene o establece el identificador, que puede ser referenciado en los puntos finales de la API. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica si la respuesta fue exitosa. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Obtiene o establece el último error asociado con este archivo de tienda de vectores. Será nulo si no hay errores. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Obtiene o establece el tipo de objeto, que siempre es vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtiene la frase de razón del error. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Obtiene o establece el estado del archivo de la tienda de vectores, que puede ser in_progress, completed, cancelled o failed. El estado completed indica que el archivo de la tienda de vectores está listo para su uso. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Obtiene o establece el uso total de la tienda de vectores en bytes. Tenga en cuenta que esto puede ser diferente del tamaño del archivo original. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Obtiene o establece el ID de la tienda de vectores a la que está adjunto el archivo. |

### Ver También

* clase [BaseResponse](../baseresponse/)
* interfaz [IStatus](../istatus/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../)