---
title: Class FileResponse
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.FileResponse. El objeto FileResponse representa un documento que ha sido subido a OpenAI
type: docs
weight: 400
url: /es/net/aspose.pdf.ai/fileresponse/
---
## Clase FileResponse

El objeto FileResponse representa un documento que ha sido subido a OpenAI.

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FileResponse](fileresponse/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | Obtiene o establece el tamaño del archivo, en bytes. |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se creó el archivo. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtiene o establece el detalle de la respuesta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtiene o establece el error de respuesta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtiene o establece la información del error. |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | Obtiene o establece el nombre del archivo. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtiene o establece los encabezados de respuesta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtiene o establece el código de estado HTTP. |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | Obtiene o establece el identificador del archivo, que puede ser referenciado en los puntos finales de la API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica si la respuesta fue exitosa. |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | Obtiene o establece el tipo de objeto, que siempre es archivo. |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | Obtiene o establece el propósito previsto del archivo. Los valores admitidos son assistants, assistants_output, batch, batch_output, fine-tune, fine-tune-results y vision. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtiene la frase de razón del error. |

### Véase también

* clase [BaseResponse](../baseresponse/)
* interfaz [IEntityId](../ientityid/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../)