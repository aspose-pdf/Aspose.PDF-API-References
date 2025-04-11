---
title: Class ThreadMessageCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.ThreadMessageCreateRequest. Representa una solicitud para crear un mensaje dentro de un hilo
type: docs
weight: 1120
url: /es/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## Clase ThreadMessageCreateRequest

Representa una solicitud para crear un mensaje dentro de un hilo.

```csharp
public class ThreadMessageCreateRequest
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | Obtiene o establece una lista de archivos adjuntos al mensaje. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | Obtiene o establece el contenido del mensaje. Puede ser una cadena o un arreglo de partes de contenido. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | Obtiene o establece un conjunto de 16 pares clave-valor que pueden ser adjuntados a un objeto. Esto puede ser útil para almacenar información adicional sobre el objeto en un formato estructurado. Las claves pueden tener un máximo de 64 caracteres y los valores pueden tener un máximo de 512 caracteres. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | Obtiene o establece el rol de la entidad que crea el mensaje. Los valores permitidos incluyen: "user", "assistant". |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | Crea una nueva `ThreadMessageCreateRequest` con el rol establecido en Asistente. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | Crea una nueva `ThreadMessageCreateRequest` con el rol establecido en Usuario. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | Establece los archivos adjuntos para la solicitud de mensaje del hilo. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | Agrega un contenido de mensaje a la solicitud de mensaje del hilo. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | Establece los contenidos del mensaje para la solicitud de mensaje del hilo. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | Establece los metadatos para la solicitud de mensaje del hilo. |

### Ver También

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)