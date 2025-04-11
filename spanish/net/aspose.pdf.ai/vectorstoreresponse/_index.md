---
title: Class VectorStoreResponse
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.VectorStoreResponse. El objeto de almacenamiento de vectores
type: docs
weight: 1390
url: /es/net/aspose.pdf.ai/vectorstoreresponse/
---
## Clase VectorStoreResponse

El objeto de almacenamiento de vectores.

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se creó el almacenamiento de vectores. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtiene o establece el detalle de la respuesta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtiene o establece el error de respuesta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtiene o establece la información del error. |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | Obtiene o establece la política de expiración para un almacenamiento de vectores. |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando expirará el almacenamiento de vectores. |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | Obtiene o establece el número de archivos que han sido procesados. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtiene o establece los encabezados de respuesta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtiene o establece el código de estado HTTP. |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | Obtiene o establece el identificador, que puede ser referenciado en los puntos finales de la API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica si la respuesta fue exitosa. |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando el almacenamiento de vectores estuvo activo por última vez. |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | Obtiene o establece un conjunto de 16 pares clave-valor que pueden ser adjuntados a un objeto. Esto puede ser útil para almacenar información adicional sobre el objeto en un formato estructurado. Las claves pueden tener un máximo de 64 caracteres y los valores pueden tener un máximo de 512 caracteres. |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | Obtiene o establece el nombre del almacenamiento de vectores. |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | Obtiene o establece el tipo de objeto, que siempre es vector_store. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtiene la frase de razón del error. |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | Obtiene o establece el estado del almacenamiento de vectores, que puede ser expirado, en_progreso o completado. Un estado de completado indica que el almacenamiento de vectores está listo para su uso. |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | Obtiene o establece el número total de bytes utilizados por los archivos en el almacenamiento de vectores. |

### Ver También

* clase [BaseResponse](../baseresponse/)
* interfaz [IEntityId](../ientityid/)
* interfaz [IStatus](../istatus/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../)