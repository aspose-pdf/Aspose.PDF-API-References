---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.CreateEmbeddingRequest. Representa una solicitud para el endpoint Crear Embeddings
type: docs
weight: 260
url: /es/net/aspose.pdf.ai/createembeddingrequest/
---
## Clase CreateEmbeddingRequest

Representa una solicitud para el endpoint Crear Embeddings.

```csharp
public class CreateEmbeddingRequest
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Obtiene o establece el número de dimensiones que deben tener las embeddings de salida resultantes. Solo es compatible con modelos text-embedding-3 y posteriores. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Obtiene o establece el formato para devolver las embeddings. Puede ser float o base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Obtiene o establece el texto de entrada para incrustar, codificado como una cadena o un arreglo de tokens. Para incrustar múltiples entradas en una sola solicitud, pase un arreglo de cadenas o un arreglo de arreglos de tokens. La entrada no debe exceder el máximo de tokens de entrada para el modelo (8192 tokens para text-embedding-ada-002), no puede ser una cadena vacía y cualquier arreglo debe tener 2048 dimensiones o menos. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Obtiene o establece el modelo para generar la embedding. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Obtiene o establece un identificador único que representa a su usuario final, lo que puede ayudar a OpenAI a monitorear y detectar abusos. |

### Ver También

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)