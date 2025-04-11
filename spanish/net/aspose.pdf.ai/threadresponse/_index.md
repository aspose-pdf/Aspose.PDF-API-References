---
title: Class ThreadResponse
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.ThreadResponse. Representa un hilo que contiene mensajes
type: docs
weight: 1180
url: /es/net/aspose.pdf.ai/threadresponse/
---
## Clase ThreadResponse

Representa un hilo que contiene mensajes.

```csharp
public class ThreadResponse : BaseResponse
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ThreadResponse](threadresponse/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) de cuándo se creó el hilo. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtiene o establece el detalle de la respuesta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtiene o establece el error de respuesta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtiene o establece la información del error. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtiene o establece los encabezados de respuesta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtiene o establece el código de estado HTTP. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | Obtiene o establece el identificador, que puede ser referenciado en los puntos finales de la API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica si la respuesta fue exitosa. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | Obtiene o establece un conjunto de 16 pares clave-valor que pueden ser adjuntados a un objeto. Esto puede ser útil para almacenar información adicional sobre el objeto en un formato estructurado. Las claves pueden tener un máximo de 64 caracteres y los valores pueden tener un máximo de 512 caracteres. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | Obtiene o establece el tipo de objeto, que siempre es hilo. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtiene la frase de razón del error. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | Obtiene o establece un conjunto de recursos que están disponibles para las herramientas del asistente en este hilo. Los recursos son específicos del tipo de herramienta. Por ejemplo, la herramienta code_interpreter requiere una lista de IDs de archivos, mientras que la herramienta file_search requiere una lista de IDs de almacenes de vectores. |

### Ver También

* clase [BaseResponse](../baseresponse/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../)